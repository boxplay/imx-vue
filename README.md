## imgx-vue

#### 运行

根目录下

```js
npm i
npm run dev
npm run build
npm run build:es
npm run build:browser
npm run build:umd
```

> dev 运行的是 rollup watch，监听 src 文件夹的变化，实时打包插件

#### 开发

只需要关注 src 目录，.babelrc 文件设置了 src 目录为 root

src 目录下的模块引入，不需要'../../' 比如:

```js
import util from 'utils/util';
```

#### 打包

dist 输出文件

- imgx-vue.css
- imgx-vue.esm.js
- imgx-vue.min.js
- imgx-vue.umd.js

### 使用

##### 安装

```

```

##### 引用

```
import Imgx from 'imgx-vue'

...
components: [
  ...
  Imgx,
  ...
]
```

模版中直接使用

<Imgx :src="'https://img.xxxx.com/91326120210202eutg.png'" :delayTime="0.6"/>

#### 参数说明

dalayTime 动画完成时间

## example 查看示例

> 进入 example 目录下

```
npm i
npm run dev
npm run build
```

浏览器中打开 localhost:8080
