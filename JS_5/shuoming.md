#完成一个简易的轮播图


    现在不需要自动轮播
    有两种轮播方式
        轮播到最后或第一张图片时停止
            此时会弹出一个提示框
        轮播到最后时，再次向后轮播时，切换为第一张图片
    显示总页数和当前在第几页


不过这个若是到实际应用中会出现bug，因为第6张图片一直是在最上面的只不过是因为透明度的原因看不见罢了
若是每张图片都有链接用于点击跳转的话，很明显点击跳转的会一直是位于最顶层的第6张图片的链接。
解决方法:事件里面顺带改一下z-index就可以了

也可以改变display属性来实现。