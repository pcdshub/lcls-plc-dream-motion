# lcls-plc-dream-motion


For more documentation on integrating TwinCAT3 and git, please see our confluence page:
https://confluence.slac.stanford.edu/display/PCDS/TwinCAT+3+Git+Setup+and+Best+Practices

## When starting a new project



Settings -> Environments -> New Environment -> name it "gh-pages" -> "Configure environment" -> "Save protection rules".

### Naming

* Libraries should be named: ``lcls-twincat-(function)``. Examples: ``lcls-twincat-general``, ``lcls-twincat-motion``
* PLC projects should be named: ``lcls-plc-(area)-(function)``. Examples: ``lcls-plc-kfe-motion``, ``lcls-plc-las-bts``
* Development or testing-focused PLC projects should be named: ``lcls-plc-test-(area)-(function)`` or ``lcls-plc-test-(name)``. Examples: ``lcls-plc-test-arbiter``, acceptance testing: ``lcls-plc-test-sat-m1l1``, ``lcls-plc-test-pmps``
* Template PLC projects should be named: ``lcls-plc-template-(name)``.
* Example PLC projects should be named: ``lcls-plc-example-(name)``.
