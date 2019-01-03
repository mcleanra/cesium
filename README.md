<p align="center">
<img src="https://github.com/AnalyticalGraphicsInc/cesium/wiki/logos/Cesium_Logo_Color.jpg" width="50%" />for SharePoint
</p>

[![Build Status](https://travis-ci.org/AnalyticalGraphicsInc/cesium.svg?branch=master)](https://travis-ci.org/AnalyticalGraphicsInc/cesium)&nbsp;

[![Docs](https://img.shields.io/badge/docs-online-orange.svg)](http://cesiumjs.org/tutorials.html) [![Greenkeeper badge](https://badges.greenkeeper.io/AnalyticalGraphicsInc/cesium.svg)](https://greenkeeper.io/)

### This fork of Cesium has been modified so that it can be used inside SharePoint.  This just means that the .json files have been renamed to .txt files.

-   All JSON files have been changed to .txt
-   iFrame in the infoBox has been replaced with a div

Cesium is a JavaScript library for creating 3D globes and 2D maps in a web browser without a plugin. It uses WebGL for hardware-accelerated graphics, and is cross-platform, cross-browser, and tuned for dynamic-data visualization.

http://cesiumjs.org/

### :rocket: Get Started

Clone the repository.

<pre>git clone https://github.com/mcleanra/cesium.git</pre>

Install dependencies.

<pre>cd cesium<br />npm install</pre>

Build a release.

<pre>npm run release</pre>

To deploy: drop the cesium/Build/Cesium folder into SharePoint and reference these files from your page:

```html
<link rel="stylesheet" href="./cesium/Widgets/widgets.css" />
<link rel="stylesheet" href="./cesium/Widgets/CesiumWidget/CesiumWidget.css" />
<link
    rel="stylesheet"
    href="./cesium/Widgets/BaseLayerPicker/BaseLayerPicker.css"
/>
<script src="./cesium/Cesium.js"></script>
```

### Updating this fork

<pre>git remote add upstream https://github.com/AnalyticalGraphicsInc/cesium.git</pre>
<pre>git fetch upstream</pre>
<pre>git merge upstream/master</pre>
<pre>git push</pre>
