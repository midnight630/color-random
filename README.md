### 颜色随机显示/指定范围

```


function bg3(){
    //随机颜色
    var r=Math.floor(Math.random()*256);
    var g=Math.floor(Math.random()*256);
    var b=Math.floor(Math.random()*256);
    return "rgb("+r+','+g+','+b+")";//所有方法的拼接都可以用ES6新特性`其他字符串{$变量名}`替换
    // //一定范围内随机颜色
    // var min = 80;
    // var max = 150;
    // var r=rn(min,max);
    // var g=rn(min,max);
    // var b=rn(min,max);
    // return "rgb("+r+','+g+','+b+")"
}
 
function rn(min,max) {
    return Math.floor(Math.random()*(max-min)+min);
};


```

参考:<https://www.cnblogs.com/li-han/p/5964463.html>

<https://blog.csdn.net/qq_32584661/article/details/82493389>