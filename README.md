# roundabout是一个3D旋转切换的插件
 1、首先插件使用HTML的格式如下   
 
```
<ul id="myRoundabout">
   <li>Box 1</li>
   <li>Box 2</li>
   <li>Box 3</li>
   <li>Box 4</li>
</ul>
 ```
 2、主要引入的css代码如下   
 
 ```
 .roundabout-holder { padding: 0; height: 5em; }  
 
   .roundabout-moveable-item { 
      height: 4em; 
      width: 4em; 
      cursor: pointer;
      background-color: #ffc;
      border: 1px solid #999;
   }
   .roundabout-in-focus { cursor: auto; }
   ```
 3、插件需要依赖jquery文件，还要引入3D旋转切换的效果，如下   
  
    <script src="js/jquery-1.4.2.min.js"></script>  
     
    <script src="js/jquery.roundabout.js"></script>  
    
    <script src="js/jquery.easing.js"></script>
  
 
