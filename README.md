# miniprogram-lodash-polyfill

小程序版 lodash-polyfill

### 安装

首先，你需要先安装

```bash

npm install @comall/miniprogram-lodash-polyfil --save

```

### 说明

使用场景是解决 `taro` 项目中使用 `lodash`/`lodash-es` 报错问题。

在使用 `lodash`/`lodash-es` 之前引用，

```js
import "@comall/miniprogram-lodash";
import {isFunction} from "lodash-es";
```
