---
bref: ""
date: 2017-05-16T15:58:18+01:00
description: ""
draft: false
menu:
  sidenav:
    pre: <i class='fa fa-fw fa-rocket'></i>
    weight: -200
  topnav:
    name: AtlasMap
    identifier: AtlasMap 
    weight: -200
sidebar: sidenav
title: "Introducing AtlasMap"
toc: true
weight: 20
---

AtlasMap is a data mapping solution with interactive web based user interface, that simplifies configuring integrations between Java, XML, and JSON data sources. You can design your data mapping with AtlasMap Data Mapper UI canvas, and then run that data mapping via runtime engine.

In addition to plain Java API provided by runtime engine, AtlasMap also provides [camel-atlasmap Component](http://docs.atlasmap.io/#camel-atlasmap) to perform data mapping as a part of [Apache Camel](http://camel.apache.org/) route.

AtlasMap Data Mapper UI is primarily designed to work within [Syndesis UI](https://syndesis.io/). The easiest way to install and run Data Mapper UI is to install and run [Syndesis](https://syndesis.io/). Simply follow the [Syndesis Developer Handbook](https://doc.syndesis.io/) to install, and run Syndesis UI. You will find the Data Mapper UI under the integrations panel after selecting or adding an integration with a data mapping step involved in the integration.


![datamapper](images/datamapper.png)


![mappinglist](images/mappinglist.png)

