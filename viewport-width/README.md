# Viewport Width
```
<meta name="viewport" content="width=750, user-scalable=no">
```
注意这行代码，并没有提供 `initial-scale`，而是由浏览器自行缩放。  
比如 iPhoneX 的设备宽度 375，不设置和在这里手动设置`initial-scale=0.5`效果是一样的。

这种方案是最简单的一种，不需要任何多余操作，并且 `border 1px` 问题都直接解决了 ，网上只能检索到只言片语说有问题，但又没人说真的有什么问题。  