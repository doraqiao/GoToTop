# GoToTop
# Jquery返回顶部的插件

 **源码里面有详细的注释，可直接引入调用，压缩后仅0.7k**
 
 实例代码：
 
```
 $('#js-go_top').gotoTop({
        offset : 500, //距离顶部的位置
        speed : 300, //移动到顶部的速度
        /*     iconSpeed : 300, //icon动画样式的速度*/
        animationShow : {
            'transform' : 'translate(0,0)',
            'transition': 'transform .5s ease-in-out'
        }, //icon动画样式显示时
        animationHide : {
            'transform' : 'translate(80px,0)',
            'transition': 'transform .5s ease-in-out'
        } //icon动画样式隐藏时
    });
```


ps：如果想在加载一开始时就隐藏icon，可以在css中设置，本示例中没有设置
