# react学习---源码学习（看书第一遍）
## 目录
<ul>
 <li><a href="#1">项目目录结构</a></li>
 <li><a href="#2">VirtualDOM</a></li>
 <li><a href="#3">生命周期</a></li>
</ul>


## 项目目录结构
<h2 id="1">项目目录结构</h2>
    《深入react技术栈》这里有，reconciler 乃核心代码部分

For example:

##### `People function`

```js
 function(){}

```

<h2 id="2">VirtualDOM</h2>

    1,A-->B-->A : 不重新渲染
    
    2, 最初形状:
    
    ```js
      {
        tagName: 'div',   // 标签名
        properties: {  // 属性
         style: {}  // 样式
        },
        children: [], // 子节点
        key: 1   // 唯一标识
     }
     
    ```


<h2 id="3">生命周期</h2>
      <h3>流程图</h3>
      
      
