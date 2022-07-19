# We are ...

We are a bunch of open-source enthusiasts and we like to write readable and reusable code. 
Within our core github organization, we work currently on the following projects (currently mainly java focused):

# Core Projects

.. there are a few things, which we consider quite 'core' and general for our java work. 
These are the things we maintain within this [github organization](https://github.com/ossgang).


### [ossgang-commons](ossgang-commons)
This is a set of java classes, which we felt we were mission in other libraries. Currently, the main components there are:
* a generic `Maybe` object, which contains either a value or an error (exception).
* a property mechanism, quite similar to the one known from javafx, but not bound to any GUI framework.

Here is an overview of actually available versions:

| library | latest release |  maven central |
|:---------|:-------:|:----------------:|
|ossgang-commons| [![Latest release](https://img.shields.io/github/release/ossgang/ossgang-commons.svg?maxAge=1000)](https://github.com/ossgang/ossgang-commons/releases)| [![Maven Central](https://img.shields.io/maven-central/v/org.ossgang/ossgang-commons)](https://search.maven.org/artifact/org.ossgang/ossgang-commons) |

### [ossgang-spring-wonderland](ossgang-spring-wonderland)
A simple mechanism to load a certain collection of beans in a spring-based application, 
based on naming conventions. This is particularly useful for situations, where a very flexible 
approach is required, e.g. for testing and commissioning. 

| library | latest release |  maven central |
|:---------|:-------:|:----------------:|
|ossgang-spring-wonderland| [![Latest release](https://img.shields.io/github/release/ossgang/ossgang-spring-wonderland.svg?maxAge=1000)](https://github.com/ossgang/ossgang-spring-wonderland/releases)| [![Maven Central](https://img.shields.io/maven-central/v/org.ossgang/ossgang-spring-wonderland)](https://search.maven.org/artifact/org.ossgang/ossgang-spring-wonderland) |

# Other projects

### tensorics: [https://tensorics.org](https://tensorics.org)
A library for dealing comfortably with multidimensional objects in java.

| library | latest release |  maven central |
|:---------|:-------:|:----------------:|
|tensorics-core| [![Latest release](https://img.shields.io/github/release/tensorics/tensorics-core.svg?maxAge=1000)](https://github.com/tensorics/tensorics-core/releases)| [![Maven Central](https://img.shields.io/maven-central/v/org.tensorics/tensorics-core)](https://search.maven.org/artifact/org.tensorics/tensorics-core) |

### minifx: [https://minifx.org](https://minifx.org)
A set of minimalistic libraries for structuring JavaFx GUIs within spring.

Here is an overview of the actually available versions:
 
| library | latest release |  maven central |
|:---------|:-------:|:----------------:|
|minifx-fxml| [![Latest release](https://img.shields.io/github/release/minifx/minifx-fxml.svg?maxAge=1000)](https://github.com/minifx/minifx-fxml/releases) |[![Maven Central](https://img.shields.io/maven-central/v/org.minifx/minifx-fxml)](https://search.maven.org/artifact/org.minifx/minifx-fxml)|
|minifx-workbench| [![Latest release](https://img.shields.io/github/release/minifx/minifx-workbench.svg?maxAge=1000)](https://github.com/minifx/minifx-workbench/releases) |[![Maven Central](https://img.shields.io/maven-central/v/org.minifx/minifx-workbench)](https://search.maven.org/artifact/org.minifx/minifx-workbench)|

### molr: [https://molr.io](https://molr.io)

A framework (not only java) for producing remote (and/or local) side effects (called "missions" ;-). 
Currently it supports particular java missions and quite generic python missions.
A prototype for very generic java missions also exists (using the java debugging interface).

Here is an overview of the actually available versions:

| library | latest release |maven central |
|:---------|:-------:|:----------------:|
|molr-commons|[![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases)|  [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-commons)](https://search.maven.org/artifact/io.molr/molr-commons)|
|molr-mole-core | [![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-mole-core)](https://search.maven.org/artifact/io.molr/molr-mole-core)
|molr-mole-remote |  [![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases)|  [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-mole-remote)](https://search.maven.org/artifact/io.molr/molr-mole-remote) |
|molr-mole-server | [![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-mole-server)](https://search.maven.org/artifact/io.molr/molr-mole-server)|
|molr-gui-fx| [![Latest release](https://img.shields.io/github/release/molr/molr-gui-fx.svg?maxAge=1000)](https://github.com/molr/molr-gui-fx/releases)| [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-gui-fx)](https://search.maven.org/artifact/io.molr/molr-gui-fx) |


### streamingpool: [https://streamingpool.org](https://streamingpool.org/)
A set of libraries to manage long-living reactive streams in java.

| library | latest release |  maven central |
|:---------|:-------:|:----------------:|
|streamingpool-core| [![Latest release](https://img.shields.io/github/release/streamingpool/streamingpool-core.svg?maxAge=1000)](https://github.com/streamingpool/streamingpool-core/releases)| [![Maven Central](https://img.shields.io/maven-central/v/org.streamingpool/streamingpool-core)](https://search.maven.org/artifact/org.streamingpool/streamingpool-core) |

### jmad: [https://jmad.io](https://jmad.io/)
A quite specialized topic: A java API for [MadX](http://mad.web.cern.ch/mad/), a simulation software for [particle accelerators](https://en.wikipedia.org/wiki/Particle_accelerator), 
mainly developed and used at [CERN](https://home.cern/).

| library | latest release |  maven central |
|:---------|:-------:|:----------------:|
|jmad-core| [![Latest release](https://img.shields.io/github/release/jmad/jmad-core.svg?maxAge=1000)](https://github.com/jmad/jmad-core/releases)| [![Maven Central](https://img.shields.io/maven-central/v/io.jmad/jmad-core)](https://search.maven.org/artifact/io.jmad/jmad-core) |
|jmad-gui| [![Latest release](https://img.shields.io/github/release/jmad/jmad-gui.svg?maxAge=1000)](https://github.com/jmad/jmad-gui/releases)| [![Maven Central](https://img.shields.io/maven-central/v/io.jmad/jmad-gui)](https://search.maven.org/artifact/io.jmad/jmad-gui) |
|jmad-modelpack-service| [![Latest release](https://img.shields.io/github/release/jmad/jmad-modelpack-service.svg?maxAge=1000)](https://github.com/jmad/jmad-modelpack-service/releases)| [![Maven Central](https://img.shields.io/maven-central/v/io.jmad/jmad-modelpack-service)](https://search.maven.org/artifact/io.jmad/jmad-modelpack-service) |
|jmad-modelpack-swing| [![Latest release](https://img.shields.io/github/release/jmad/jmad-modelpack-swing.svg?maxAge=1000)](https://github.com/jmad/jmad-modelpack-swing/releases)| [![Maven Central](https://img.shields.io/maven-central/v/io.jmad/jmad-modelpack-swing)](https://search.maven.org/artifact/io.jmad/jmad-modelpack-swing) |
|jmad-modelpack-fx| [![Latest release](https://img.shields.io/github/release/jmad/jmad-modelpack-fx.svg?maxAge=1000)](https://github.com/jmad/jmad-modelpack-fx/releases)| [![Maven Central](https://img.shields.io/maven-central/v/io.jmad/jmad-modelpack-fx)](https://search.maven.org/artifact/io.jmad/jmad-modelpack-fx) |

