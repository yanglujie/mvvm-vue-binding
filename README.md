# vue mvvm简易实现
### 实现的功能
#vue-binding1:
##1.用户在表单中输入的数据实时绑定在person对象的同名属性中；
##2.在person对象中进行属性的修改会实时反映在表单中；
##实现效果：
![Image text](https://github.com/yanglujie/bigDatamap/raw/master/static/img/ditu1.jpg)
#vue-binding2:
##Vue的数据响应系统包含三个部分：Observer、Dep、Watcher
![Image text](https://github.com/yanglujie/bigDatamap/raw/master/static/img/ditu1.jpg)

### 两种方法

1、`index.js`文件中是用`getBoundingClientRect()`方法的

2、`index2.js`文件中是用`IntersectionObserver()`方法的