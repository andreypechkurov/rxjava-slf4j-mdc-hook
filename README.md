# rxjava2-slf4j-mdc-hook

A port of
[rxjava-slf4j-mdc-hook](https://github.com/bmcstdio/rxjava-slf4j-mdc-hook)
with RxJava 2 support.

An
[RxJava](https://github.com/ReactiveX/RxJava)
[hook](https://github.com/ReactiveX/RxJava/wiki/What%27s-different-in-2.0#runtime-hooks)
which enables
[SLF4J](https://github.com/qos-ch/slf4j)'s
[`MDC`](http://www.slf4j.org/api/org/apache/log4j/MDC.html)
propagation.

## Usage

```java
RxJavaPlugins.setScheduleHandler(new MdcPropagatingOnScheduleFunction());
```

<!--
## Binaries

`rxjava-slf4j-mdc-hook` is available from both JCenter and Maven Central:

**Gradle:**

```
compile 'io.github.bmcstdio:rxjava-slf4j-mdc-hook:1.1.2'
```

**Maven:**

```
<dependency>
  <groupId>io.github.bmcstdio</groupId>
  <artifactId>rxjava-slf4j-mdc-hook</artifactId>
  <version>1.1.2</version>
</dependency>
```

## Building

```
$ git clone https://github.com/brunomcustodio/rxjava-slf4j-mdc-hook.git
$ cd rxjava-slf4j-mdc-hook
$ ./gradlew build
```
-->

## License

Copyright 2018 andreypechkurov
Copyright 2016-2017 brunomcustodio

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
