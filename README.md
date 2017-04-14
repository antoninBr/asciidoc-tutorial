# asciidoc-tutorial

A humble project to show all the benefits of using [asciidoc](http://www.methods.co.nz/asciidoc/) (+ some [plantUML](http://plantuml.com/) magic as well) in a java project with maven.

[![Run Status](https://api.shippable.com/projects/58f07de99755e8070035ed26/badge?branch=master)](https://app.shippable.com/github/antoninBr/asciidoc-tutorial)

## Requirements

Simply have java and maven installed on its local dev environment for asciidoc.
Some PlantUML feature such as Components Diagram need to have a [Graphviz](http://www.graphviz.org/) installation (or at least an ENV variable called GRAPHVIZ_DOT pointing toward the dot executable).

## Recommendations

[Intellij IDEA](https://www.jetbrains.com/idea/) comes with two usefull plugins for creating asciidoc files and plantUML diagrams.

| Plugin        | Description                                                     |
| ------------- |:---------------------------------------------------------------:| 
| AsciiDoc      | https://github.com/asciidoctor/asciidoctor-intellij-plugin      |
| plantUML      | https://plugins.jetbrains.com/plugin/7017-plantuml-integration  | 



## Documentation generation

Performing a simple :
```
mvn clean install
```
Will generate all the documentation sources (html, png, ...) in this tutorial _target_ folder.

## Online Generated Documentation

All the generated documentation of this tutorial is available [here](https://www.jetbrains.com/idea/).
