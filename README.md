# vue-krpano

A Vue component for [krpano](http://www.krpano.com) player.

## Installation

```
npm install vue-krpano --save
```

## Dependency

* [vuejs@2.0](http://vuejs.org)
* A Krpano player globally referenced by `<script>`


## Instruction

page.js

```js
{
    "template": require("./page.html"),
    "components": {
        "krpano": require("vue-krpano")
    }
}
```

page.html

```html
<krpano :xml="'krpano.xml'" :lazy-load="true" style="width:100%;height:400px"></krpano>
```

## Props

|Name|Description|Example|
|:--|:--|:--|
|`xml`|Krpano configuration XML path|`krpano.xml`|
|`scene`|Scene index|`1`|
|`lazyLoad`|A Boolean setting to lazy load pano objects|`true`|
|`mwheel`|A Boolean setting to control the mouse-wheel usage|`false`|
|`focus`|A Boolean setting to give the viewer the input / keyboard focus on startup.|`true`|
|`consolelog`|A Boolean setting that defines if krpano log/trace-messages should be sent also to the browser Javascript console.|`false`|
|`noPlugin`|A Boolean setting to remove all plugins|`false`|
|`debug`|Debug mode|`false`|

## About

For any question, please feel free to write email to 261934121@qq.com
