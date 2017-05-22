# WeApp Extension for VS Code  

[![Visual Studio Marketplace](http://vsmarketplacebadge.apphb.com/version/emeryao.we-app-vscode.svg?style=flat-square&color=09BB07)](https://marketplace.visualstudio.com/items?itemName=emeryao.we-app-vscode)
![](http://vsmarketplacebadge.apphb.com/installs/emeryao.we-app-vscode.svg?style=flat-square&color=09BB07)
[![GitHub stars](https://img.shields.io/github/stars/Emeryao/we-app-vscode.svg?style=flat-square)](https://github.com/Emeryao/we-app-vscode)

> VS code extension for WeApp development  
> 微信小程序插件 for [TypeScript](#typescript) / [wxml](#wxml) / [config json](#json)

## Welcome
It's nice to see you here getting this extension, cause you're using or gonna use the GREAT **[TypeScript](http://www.typescriptlang.org)** to develop your WeApp  
You can aslo take advantage of this extension for `wxml` and `json` even if you are using javascript

BTW: It is **strongly recommeded** to get the TypeScript declaration file for WeApp API:  
* With [`npm`](https://www.npmjs.com/) installed  

    ```batch
    npm install typed-we-app --save-dev
    ```

* With [`typings`](https://github.com/typings/typings) installed  

    ```batch
    typings install github:Emeryao/typed-we-app -SG
    ```

## Contact Me
[![Twitter](https://img.shields.io/twitter/url/https/github.com/Emeryao/we-app-vscode.svg?style=flat-square)](https://twitter.com/luyao1206)

Please feel free to contact me via [email](mailto:luyao1206@live.cn) or Github [issue](https://github.com/Emeryao/we-app-vscode/issues)

## Snippets
> prefix **`wa-`** stands for WeApp  
> based on the official WeApp [documentation](https://mp.weixin.qq.com/debug/wxadoc/dev/index.html)

### [TypeScript](http://www.typescriptlang.org/)
* **`wa-page`** :
```typescript
    let mainPage: WeApp.Page;
    
    Page({
        data: {
            message: 'hello world'
        },
        onLoad: function (): void {
            mainPage = this;
        }
    });
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

### wxml

|snippets|output|
|--------|--------|
|`wa-block`|`<block></block>`|
|`wa-view`|`<view></view>`|
|`wa-scroll-view`|`<scroll-view></scroll-view>`|
|`wa-swiper`|`<swiper></swiper>`|
|`wa-swiper-item`|`<swiper-item></swiper-item>`|
|`wa-icon`|`<icon></icon>`|
|`wa-text`|`<text></text>`|
|`wa-textarea`|`<textarea></textarea>`|
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
|`wa-navigator`|`<navigator></navigator>`|
|`wa-audio`|`<audio></audio>`|
|`wa-image`|`<image></image>`|
|`wa-video`|`<video></video>`|
|`wa-map`|`<map></map>`|
|`wa-canvas`|`<canvas></canvas>`|
|`wa-movable-area`|`<movable-area></movable-area>`|
|`wa-movable-view`|`<movable-view></movable-view>`|


### JSON  

* wa-page
* wa-app-window
* wa-app-page
* wa-app-tab
* wa-app-network
* wa-app-debug

## Where to get

* Extension@[Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=emeryao.we-app-vscode)
* Source@[Github](https://github.com/Emeryao/we-app-vscode)

## Last Update
`2017.05.22`  
WeApp Dev Tool Version: `0.17.171900`
