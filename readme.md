### 渲染
    // const react = "react";
function tick() {
  const element = (
    <div>
      <h1>hello, world</h1>
      <h2>it is {new Date().toLocaleTimeString()}</h2>
    </div>
  )
  ReactDOM.render(element, document.getElementById('root'));
}
setInterval(tick, 1000);


### 组件
import React from "react";
//用类的形式创建组件，hook形式

class App extends React.Component {
    //渲染函数
    render() {
        return <h1>hello react Component</h1>
    }
}
export default App

### props属性


### setState是同步还是异步
1.setState是对视图的重绘
2.在可控情况下，是异步，在非可控下是同步的

### 条件渲染
ifDemo.jsx

### 列表渲染
主要问题是：key

### 表单
1.受控组件
2.非受控组件

### 状态提升
组件之间的数据交互

### 组合&继承
关键点：this.props.children

### 使用PropsTypes进行类型检查
