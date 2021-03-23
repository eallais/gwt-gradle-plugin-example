# gwt-gradle-plugin-example

Here is the bug with GWT Gradle plugin:

For some reason `commons-logging-1.2` dependency is missing from Gradle container classpath (i.e. Project and External Dependencies in Eclipse IDE) but not guava dependency which is added correctly.

This bug seems to happen only for version **1.2** of commons-logging !

![commons-loggins-missing](./gwt-gradle-plugin-eclipse-classpath.png)

Any ideas why ?

