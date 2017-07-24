# numKeyBoard.js

## 1、效果
 ![](https://github.com/xingxiaoyiyio/numPad-es/raw/master/1.jpeg)
 
## 2、调用方法
```
 var numPad= new NumKeyBoard({
          precision: 2,        //精确度
          minVal:10,           //允许输入的最小值
          maxVal:1000          //允许输入的最大值
      });
      
//打开数字键盘弹框,参数为弹框确定按钮的回调函数，回调函数的参数是输入的值
 numPad.open(function(val){
　　alert(val)
})
 ```

