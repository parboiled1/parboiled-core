parboiled-core
==============

Parboiled1; core mechanics, without Scala support

This is a brand new fork - the purpose is to continue Java development. For now the goals are the following:

* Modularized packages
* Remove Scala support
* Gradlew support
* Ease parboiled1 (java) development
* Provide a separate package for examples
* Publish!

Going forwards, maybe we will:

* Add more rules
* Fix bugs!
* Write more tests.

If you are looking for a Scala version, perhaps you will be more interested in Parboiled2.

## How to build

**You must have a JDK version 6 or 7 for this package to work**. Make sure that
you use the same version to build this package and the other two:

* [parboiled-java](https://github.com/parboiled1/parboiled-java).
* [parboiled-examples](https://github.com/parboiled1/parboiled-examples).

Use these commands to build and install in your local maven repository:

```
# Unix
./gradlew clean test install
# Windows
gradlew.bat clean test install
```

