# color-random
js -- Random color display/specified range display

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
    // return "rgb("+r+','+g+','+b+")";
 }
 /*** random number : 生成指定范围内的随机整数 ****/
function rn(min,max) {
    return Math.floor(Math.random()*(max-min)+min);
};
