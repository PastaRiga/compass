# NioEndPoint组件

### 00. Java多路复用器
- 步骤1: 创建一个Selector，在它身上注册各种感兴趣的事件，然后调用select方法，等待感兴趣的事情发生
- 步骤2: 感兴趣的事情发生了，比如可以读取数据了，这时便创建一个新的线程从Channel中读数据

### 01. NioEndPoint总体实现