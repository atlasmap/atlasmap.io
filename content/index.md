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
toc: false 
weight: 20
---
[![Runtime @ Maven Central](https://maven-badges.herokuapp.com/maven-central/io.atlasmap/atlas-parent/badge.svg?style=flat-square)](https://maven-badges.herokuapp.com/maven-central/io.atlasmap/atlas-parent/)
&nbsp;[![UI @ NPM](https://badge.fury.io/js/%40atlasmap%2Fatlasmap-data-mapper.svg)](https://badge.fury.io/js/%40atlasmap%2Fatlasmap-data-mapper)
&nbsp;[![Netlify Status](https://api.netlify.com/api/v1/badges/08a56260-a890-4ffb-9c6d-7b7be24f0cc7/deploy-status)](https://app.netlify.com/sites/atlasmap/deploys)
&nbsp;[![Gitter chat](https://badges.gitter.im/atlasmap/community.png)](https://gitter.im/atlasmap/community)

[Google Group](https://groups.google.com/d/forum/atlasmap)

AtlasMap is a data mapping solution with interactive web based user interface, that simplifies configuring integrations between Java, XML, and JSON data sources. You can design your data mapping with AtlasMap Data Mapper UI canvas, and then run that data mapping via runtime engine.

In addition to plain Java API provided by runtime engine, AtlasMap also provides [camel-atlasmap Component](http://docs.atlasmap.io/developer-guide/#camel-atlasmap) to perform data mapping as a part of [Apache Camel](http://camel.apache.org/) route.

AtlasMap Data Mapper UI is primarily designed to work within [Syndesis UI](https://syndesis.io/). The easiest way to install and run Data Mapper UI is to install and run [Syndesis](https://syndesis.io/). Simply follow the [Syndesis Developer Handbook](https://doc.syndesis.io/) to install, and run Syndesis UI. You will find the Data Mapper UI under the integrations panel after selecting or adding an integration with a data mapping step involved in the integration.


![datamapper](images/datamapper.png)


![mappinglist](images/mappinglist.png)

<p align="center">
  <a href="https://www.netlify.com">
    <img src="https://www.netlify.com/img/global/badges/netlify-color-accent.svg" alt="Deploys by Netlify" />
  </a>
</p>

