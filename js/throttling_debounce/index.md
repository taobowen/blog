**应用场景**

实际工作中，我们经常性的会通过监听某些事件完成对应的需求，比如：

- 通过监听 scroll 事件，检测滚动位置，根据滚动位置显示返回顶部按钮
- 通过监听 resize 事件，对某些自适应页面调整DOM的渲染（通过CSS实现的自适应不再此范围内）
- 通过监听 keyup 事件，监听文字输入并调用接口进行模糊匹配

**函数防抖**

定义：多次触发事件后，事件处理函数只执行一次，并且是在触发操作结束时执行。
原理：闭包

**防抖函数的封装使用**

[防抖](./debounce.js)

**函数节流**

定义：每隔一段时间，只执行一次函数。
原理：闭包

**节流函数的封装使用**

[节流](./throttling.js)