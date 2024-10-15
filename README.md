Content Framework
==============

A basic Project to identify patterns in content generation, can be included in projects to make content delivery much more streamlined.


## Running with Maven

This project can be build with [Apache Maven](http://maven.apache.org/). The project uses [Liberty Maven Plug-in][] to automatically download and install Liberty profile runtime from the [Liberty repository](https://developer.ibm.com/wasdev/downloads/). Liberty Maven Plug-in is also used to create, configure, and run the application on the Liberty server. 

Use the following steps to run the application with Maven:

1. Execute full Maven build. This will cause Liberty Maven Plug-in to download and install Liberty profile server.
    ```bash
    $ mvn clean install
    ```

# Notice

© Copyright IBM Corporation 2014.

# License

```text
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
````

[Liberty Maven Plug-in]: https://github.com/WASdev/ci.maven

