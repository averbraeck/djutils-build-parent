# djutils-build-parent

The Maven build parent pom with default conventions.

### Purpose

Shared build conventions for projects in the djunits, djutils, dsol, sim0mq, opentrafficsim family.

Provides:
- Java version
- compiler settings
- test execution
- code coverage
- formatting
- Checkstyle
- SpotBugs
- PMD

Used by:
- DJUTILS
- DJUNITS
- DSOL
- OpenTrafficSim
- SIM0MQ


### Working

The project offers a parent pom with default settings that can be kept constant across projects. 
Projects can still override every setting.