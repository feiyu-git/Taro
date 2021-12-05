React基础知识点



##### 1、Fragment 

 React.Fragment 组件能够在不额外创建 DOM 元素的情况下，让 render() 方法中返回多个元素。一个常见模式是一个组件返回多个元素。Fragments 允许你将子列表分组，而无需向 DOM 添加额外节点。 

```js
import React,{Fragment} from 'react'

render() {
    return (
      <React.Fragment>
        <ChildA />
        ...
      </React.Fragment>
    );
}

// 或者 
render() {
    return (
      <Fragment>
        <ChildA />
        ...
      </Fragment>
    );
}
```



