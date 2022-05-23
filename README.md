# babylonjs_webpack_template
# 背景
Babylon.js + webpackのサンプルを目指しました。

# 動作環境

- Node.js v16.14.1

# Setup

clone
``` 
git git@github.com:iwaken71/babylonjs_webpack_template.git
cd babylonjs_webpack_template
```

SetUp

```
npm install
```

Dev実行

```
npm run dev
```

Build
./dist以下にbundleファイルができる
```
npm run build
```

dist以下のファイルをホスティングするとWebページとして動作する。

# 使い方

src/index.jsの[createScene関数](https://github.com/iwaken71/babylonjs_webpack_template/blob/70d01c58ff437c1d10187a58b3b992fd0f7b95e7/src/index.js#L10)

```js
const createScene = async function () {
    //PlayGroundと同じ内容を書く
}
```

Inspectorの表示。不要ならば消す。([source code](https://github.com/iwaken71/babylonjs_webpack_template/blob/70d01c58ff437c1d10187a58b3b992fd0f7b95e7/src/index.js#L46))
```js
// show inspector
scene.debugLayer.show(); 
```

# 動作ページ

https://iwaken71.github.io/babylonjs_webpack_template/
