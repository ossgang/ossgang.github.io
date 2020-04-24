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


### [ossgang-spring-wonderland](ossgang-spring-wonderland)
A simple mechanism to load a certain collection of beans in a spring-based application, 
based on naming conventions. This is particularly useful for situations, where a very flexible 
approach is required, e.g. for testing and commissioning. 

# Other projects

### [tensorics](https://tensorics.org)
A library for dealing comfortably with multidimensional objects in java.

### minifx: https://minifx.org
A set of minimalistic libraries for structuring JavaFx GUIs within spring.

Here is an overview of the actually available versions:

| library | latest release | bintray/jcenter | maven central |
|:---------|:-------:|:----------:|:----------------:|
|minifx-fxml| [![Latest release](https://img.shields.io/github/release/minifx/minifx-fxml.svg?maxAge=1000)](https://github.com/minifx/minifx-fxml/releases) |[![Bintray](https://img.shields.io/bintray/v/minifx/minifx-repo/minifx-fxml)](https://bintray.com/minifx/minifx-repo/minifx-fxml/_latestVersion)|[![Maven Central](https://img.shields.io/maven-central/v/org.minifx/minifx-fxml)](https://search.maven.org/search?q=a:minifx-fxml)|
|minifx-workbench| [![Latest release](https://img.shields.io/github/release/minifx/minifx-workbench.svg?maxAge=1000)](https://github.com/minifx/minifx-workbench/releases) |[![Bintray](https://img.shields.io/bintray/v/minifx/minifx-repo/minifx-workbench)](https://bintray.com/minifx/minifx-repo/minifx-workbench/_latestVersion)|[![Maven Central](https://img.shields.io/maven-central/v/org.minifx/minifx-workbench)](https://search.maven.org/search?q=a:minifx-workbench)|

### molr: https://molr.io

A framework (not only java) for producing remote (and/or local) side effects (called "missions" ;-). 
Currently it supports particular java missions and quite generic python missions.
A prototype for very generic java missions also exists (using the java debugging interface).

Here is an overview of the actually available versions:

| library | latest release | bintray/jcenter | maven central |
|:---------|:-------:|:----------:|:----------------:|
|molr-commons|[![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases)|  [ ![Bintray](https://img.shields.io/bintray/v/molr/molr-repo/molr-commons) ](https://bintray.com/molr/molr-repo/molr-commons/_latestVersion) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-commons)](https://search.maven.org/search?q=a:molr-commons)|
|molr-mole-core | [![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases) | [ ![Bintray](https://img.shields.io/bintray/v/molr/molr-repo/molr-mole-core) ](https://bintray.com/molr/molr-repo/molr-mole-core/_latestVersion) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-mole-core)](https://search.maven.org/search?q=a:molr-mole-core)
|molr-mole-remote |  [![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases)| [ ![Bintray](https://img.shields.io/bintray/v/molr/molr-repo/molr-mole-remote) ](https://bintray.com/molr/molr-repo/molr-mole-remote/_latestVersion) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-mole-remote)](https://search.maven.org/search?q=a:molr-mole-remote) |
|molr-mole-server | [![Latest release](https://img.shields.io/github/release/molr/molr.svg?maxAge=1000)](https://github.com/molr/molr/releases) | [ ![Bintray](https://img.shields.io/bintray/v/molr/molr-repo/molr-mole-server) ](https://bintray.com/molr/molr-repo/molr-mole-server/_latestVersion) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-mole-server)](https://search.maven.org/search?q=a:molr-mole-server)|
|molr-gui-fx| [![Latest release](https://img.shields.io/github/release/molr/molr-gui-fx.svg?maxAge=1000)](https://github.com/molr/molr-gui-fx/releases)| [ ![Bintray](https://img.shields.io/bintray/v/molr/molr-repo/molr-gui-fx) ](https://bintray.com/molr/molr-repo/molr-gui-fx/_latestVersion) | [![Maven Central](https://img.shields.io/maven-central/v/io.molr/molr-gui-fx)](https://search.maven.org/search?q=a:molr-gui-fx) |


### [streamingpool](https://streamingpool.org/)
A set of libraries to manage long-living reactive streams in java.

### [jmad](https://jmad.io/)
A quite specialized topic: A java API for [MadX](http://mad.web.cern.ch/mad/), a simulation software for [particle accelerators](https://en.wikipedia.org/wiki/Particle_accelerator), 
mainly developed and used at [CERN](https://home.cern/).


