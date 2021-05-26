# 安装

threejs官方提供了npm的安装方式

```shell
$ npm install three --save-dev
```

引入：

```js
import * as THREE from "three"
/**
 * 如控制器（control）、加载器（loader）以及后期处理效果（post-processing effect） 
 * 是 examples/jsm 目录的一部分, 这些模块的引入方式如下 
 */
import { TWEEN } from "three/examples/jsm/libs/tween.module.min.js";
import { TrackballControls } from "three/examples/jsm/controls/TrackballControls.js";
```

或 html 标签导入：

```html
<script type="module">

  // 通过访问 https://cdn.skypack.dev/three 来查找最新版本。
  import * as THREE from 'https://cdn.skypack.dev/three@<version>';
  const scene = new THREE.Scene();
</script>
```

或者到 github 下载对应 [three.js](https://github.com/mrdoob/three.js/tree/dev/build) 文件引入 ：

