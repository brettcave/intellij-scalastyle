intellij-scalastyle
===================

Scalastyle IntelliJ IDEA support


How to configure it in IDEA (currently it's for IDEA 12, build 122.519, but it so simple that I'm sure it's compatible with IDEA 11 as well):

1. Open project.

2. Add global library "scala-plugin" containing only scala-plugin.jar from Scala plugin repository. (I'm sure this dependency is not necessary, but I think it's impossible to use Scalastyle plugin without Scala plugin and also probably this will be necessary in future, so I created this hard dependency).

3. Add IDEA SDK in your SDKs.
