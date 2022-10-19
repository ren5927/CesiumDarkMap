# CesiumDarkMap
cesium暗色地图滤镜代码(不需要修改源码)

个人用的高德

描述:

```
google找了半天的方法,发出来让大家少走弯路,用于实现暗色地图,国内的地图用不了暗色,超图地图不太全,所以就有了这种需求
```

使用方法
引入:

```
 import modifyMap from './filterColor'
 //根据实际情况修改,你想放哪里就放哪里,不过记得填正确的路径
```

调用:

```
modifyMap(viewer, {
    //反色?
    invertColor: true,
    //滤色值
    filterRGB: [60, 145, 172],
});
//viewer是什么不用我说了吧
```

(注:filterColor.js中我是`import * as Cesium from 'cesium'` 这样引入cesium的,请根据实际情况修改)

效果如图:

![demo](.\demo.png)
