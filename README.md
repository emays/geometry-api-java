[![Build](https://github.com/emays/esri-geometry-api/actions/workflows/maven.yml/badge.svg)](https://github.com/emays/esri-geometry-api/actions/workflows/maven.yml)

This is a fork of the [Esri Geometry API for Java](https://github.com/Esri/geometry-api-java)

Primary changes:

* Implement modules (JPMS)
* Java 25
* Note: groupId is io.github.emays

Available at [Maven Central](https://central.sonatype.com/artifact/io.github.emays/esri-geometry-api)

# geometry-api-java

The Esri Geometry API for Java can be used to enable spatial data processing in 3rd-party data-processing solutions.  Developers of custom MapReduce-based applications for Hadoop can use this API for spatial processing of data in the Hadoop system.  The API is also used by the [Hive UDF’s](https://github.com/Esri/spatial-framework-for-hadoop) and could be used by developers building geometry functions for 3rd-party applications such as [Cassandra]( https://cassandra.apache.org/), [HBase](http://hbase.apache.org/), [Storm](http://storm-project.net/) and many other Java-based “big data” applications.

## Features
* API methods to create simple geometries directly with the API, or by importing from supported formats: JSON, WKT, and Shape
* API methods for spatial operations: union, difference, intersect, clip, cut, and buffer
* API methods for topological relationship tests: equals, within, contains, crosses, and touches

## Documentation
* [geometry-api-java/Wiki](https://github.com/Esri/geometry-api-java/wiki/)
* [geometry-api-java/Javadoc](http://Esri.github.io/geometry-api-java/javadoc/)

## Resources

* [ArcGIS Geodata Resource Center]( http://resources.arcgis.com/en/communities/geodata/)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@esri](http://twitter.com/esri)


## Licensing
Copyright 2013-2019 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.github.com/Esri/geometry-api-java/master/license.txt) file.
