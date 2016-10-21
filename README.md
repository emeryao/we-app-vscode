# we-app-vscode
VS code extension for WeApp development using [TypeScript](http://www.typescriptlang.org/)  
微信小程序插件 for [TypeScript](#TypeScript) / [wxml](#wxml) / [config json](#JSON)

> BTW: you can get the declaration file for WeApp API [here](https://github.com/Emeryao/typed-we-app)

## Snippets
> prefix **`wa-`** stands for WeApp  
> base on the official WeApp [documents](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html)

* [TypeScript](http://www.typescriptlang.org/)
  * **`wa-page`** :
  ```typescript
    let self;
    let param: PageParam = {
        data: {
            message: 'hello world'
        },
        onLoad: function () {
            self = this;
        }
    };
    Page(param);
  ```
  * **`wa-app`** :
  ```typescript
    let param: AppParam = {
        onLaunch: function () {

        },
        onShow: function () {

        },
        onHide: function () {

        }
    };
    App(param);
  ```

* wxml

|snippets|output|
|--------|--------|
|`wa-block`|`<block></block>`|
|`wa-view`|`<view></view>`|
|`wa-scroll-view`|`<scroll-view></scroll-view>`|
|`wa-swiper`|`<swiper></swiper>`|
|`wa-swiper-item`|`<swiper-item></swiper-item>`|
|`wa-icon`|`<icon></icon>`|
|`wa-text`|`<text></text>`|
|`wa-progress`|`<progress></progress>`|
|`wa-button`|`<button></button>`|
|`wa-checkbox-group`|`<checkbox-group></checkbox-group>`|
|`wa-checkbox`|`<checkbox></checkbox>`|
|`wa-form`|`<form></form>`|
|`wa-input`|`<input></input>`|
|`wa-label`|`<label></label>`|
|`wa-picker`|`<picker></picker>`|
|`wa-radio-group`|`<radio-group></radio-group>`|
|`wa-radio`|`<radio></radio>`|
|`wa-slider`|`<slider></slider>`|
|`wa-switch`|`<switch></switch>`|
|`wa-action-sheet`|`<action-sheet></action-sheet>`|
|`wa-action-sheet-item`|`<action-sheet-item></action-sheet-item>`|
|`wa-action-sheet-cancel`|`<action-sheet-cancel></action-sheet-cancel>`|
|`wa-modal`|`<modal></modal>`|
|`wa-toast`|`<toast></toast>`|
|`wa-loading`|`<loading></loading>`|
|`wa-navigator`|`<navigator></navigator>`|
|`wa-audio`|`<audio></audio>`|
|`wa-image`|`<image></image>`|
|`wa-video`|`<video></video>`|
|`wa-map`|`<map></map>`|
|`wa-canvas`|`<canvas></canvas>`|

* JSON
  * wa-page
  * wa-app-window
  * wa-app-page
  * wa-app-tab
  * wa-app-network
  * wa-app-debug

## Last Update
2016.10.19
