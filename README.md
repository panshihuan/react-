<h1>react 源码学习</h1>
<ul>
  <li><a href="#1">目录结构</a></li>
  <li><a href="#2">Virtual DOM</a></li>
</ul>

<div id="1">目录结构</div>



<div id="2">
  <pre>
   type ReactNode = ReactElement | ReactFragment | ReactText;
  type ReactElement = ReactComponentElement | ReactDOMElement;
  type ReactDOMElement = {
  type : string,
  props : {
   children : ReactNodeList,
   className : string,
   etc.
  },
   key : string | boolean | number | null,
   ref : string | null
  };
  type ReactComponentElement<TProps> = {
   type : ReactClass<TProps>,
   props : TProps,
   key : string | boolean | number | null,
   ref : string | null
  };
  type ReactFragment = Array<ReactNode | ReactEmpty>;
  type ReactNodeList = ReactNode | ReactEmpty;
  type ReactText = string | number;
  type ReactEmpty = null | undefined | boolean;
  </pre>
</div>






























