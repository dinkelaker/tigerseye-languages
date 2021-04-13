This is the source code release of the TigersEye DSL Framework's "Languages" component group.

The TigersEye DSL Framework helps language developers to build domain-specific languages (DSLs) in form of libraries, also called internal or embedded DSLs. The languages derived in the framework are enabled for further composition through so-called combiners that compose the syntax, semantics and pragmatics of the language components.



Apache License
Version 2.0, January 2004
https://www.apache.org/licenses/LICENSE-2.0.html




# INSTALLATION
To complete the installation of the languages parts, first, you follow the installation of the core part: 




# GETTING STARTED
To build TigersEye, simply use the embedded gradle wrapper.
In the root directory "tigerseye-languages" in which the build.gradle file is located,
you need to run from command line the following:
> gradlew build test 

To set up the project structure execute:
> gradlew cleanEclipse eclipse

To install the component group for customizations of the core library to be used in dependent projects execute:
> gradlew clean publishToMavenLocal

The project currently uses Groovy compiler version 2.5.1+ and Eclipse as IDE support.



# CONTRIBUTING
You may contribute to the project via github:
https://github.com/dinkelaker/tigerseye-core

You can access the git SCM via:
git@github.com:dinkelaker/tigerseye-core.git




# PITFALLS

None so far.