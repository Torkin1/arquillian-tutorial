# arquillan-example

This is an implementation of the minimal MWE described at the [Arquillan getting started guide](https://arquillian.org/guides/getting_started/#open_the_project_in_eclipse)

## Known working setup

```
java version "1.8.0_202"
Java(TM) SE Runtime Environment (build 1.8.0_202-b08)
Java HotSpot(TM) 64-Bit Server VM (build 25.202-b08, mixed mode)
```
```
Apache Maven 3.9.9 (Red Hat 3.9.9-14)
Maven home: /usr/share/maven
Java version: 1.8.0_202, vendor: Oracle Corporation, runtime: /usr/java/jdk1.8.0_202-amd64/jre
Default locale: en_DK, platform encoding: UTF-8
OS name: "linux", version: "6.15.8-200.fc42.x86_64", arch: "amd64", family: "unix"
```

The library seems susceptible to the java version *and vendor*. The above configuration works on my machine.

To run test:
```sh
mvn test
```

