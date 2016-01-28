# batik
Batik library for generating images from SVG

Batik is an open source library. It has many jar files. For example batik-core, batik-dom, batik-css... etc.

This repo has only batik-bridge.jar's souce folder.

This jar has some bugs. We have fix the bug in the source folder and build new batik-bridge jar.
Build file also modified a little bit to build only the batik-bridge.jar

please use the following command to build this jar.
ant -f build.xml bridge-jar
