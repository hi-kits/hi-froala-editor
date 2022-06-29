<!--
 * @Descripttion: 
 * @version: 
 * @Author: liulina
 * @Date: 2022-05-18 15:50:12
 * @LastEditors: liulina
 * @LastEditTime: 2022-06-29 19:02:19
-->
#hi-froala-editor
基于hi-froala-editor组件在修改了样式及在生产上会展示红色需破解的div
2。0.0
针对三翼鸟商家平台的跨域问题，出的版本
修改点如下：
从：
var e = N(p(n)),
        t = N(p("tzgatD-13eD1dtdrvmF3c1nrC-7saQcdav==")).split(".");
      return window.parent.document.querySelector(e) && window[t[1]][t[2]]
到
var e = N(p(n)),
        t = N(p("tzgatD-13eD1dtdrvmF3c1nrC-7saQcdav==")).split(".");
      return window.document.querySelector(e) && window[t[1]][t[2]]