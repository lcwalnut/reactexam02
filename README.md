# React Exam 02
请写一个满足以下要求的confirm方法组件：

（1）能在任意组件(示例如下)的componentDidMount生命周期中挂载，并返回一个promise；

（2）能通过该promise返回的结果判断confirm组件是否成功挂载。

```JS

async componentDidMount(){
    let res = await confirm("确定删除吗")
    if(res) {
        console.log("是")
    } else {
        console.log("否")
    }
}

```
