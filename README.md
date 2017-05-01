## 2016研发暑假博客开发

#### 预览地址
https://devinnan.github.io/RDC-Login/

#### 说明

- 该页面模仿知乎登录页做canvas开发  
    - 减少了圆圈线的连接，可以独立使用
    - 源码在```./js/mycanvas.js```中  
    - 使用方法  
    首先引入文件，```<script src="js/mycanvas.js"></script>```
    在HTML中，添加```<div class="mycanvas"><canvas id="mycanvas"></canvas></div>```
    在CSS中指定样式 ```.mycanvas {position: absolute;top: 0;z-index: -1;}```
- 参考了知乎垂直居中的做法
- 整体兼容到ie7


