---
{"dg-publish":true,"title":null,"permalink":"//java/","dgPassFrontmatter":true}
---


## 网站文档资源： [[网页资源/Javaweb资源\|Javaweb资源]]


学习视频：[Java Tutorial for Beginners (youtube.com)](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s)

[05:00](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=300.741763)
function结构 的讲解 （组成Java的模块 ）

public classs main{
    void main(){   //类方法（在类外叫函数）
    ...
    }
}


[11:48](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=708.220522)
hello world 第一个Java程序

```
package   com.servlet;//包名
public  class Main{
     public startic void main(String[] args){
          System.out.println("hello world");
     }
}

```


[26:07](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=1567.500017)
java中的变量

 int age=34 ,  age1=23;这是错误的不能用逗号隔开。
  int （4），  byte（1），short（2），long（8），float（4），double（8），char（2），Boolean（1）

[33:33](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=2013.458265)
  关于无法识别变量的错误
  
  long views= 3_2323_232_232L;
  float price = 10.99F;

[35:17](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=2117.036129)
Date  （Java.util）日期类，在idea中选中后会出现import的包

Date now  = new  Date（）； //new运算符为这个变量分配内存 

基本类型和引用类型
基本类型用来储存简单值，使用类型来存储复杂对象。两者主要区别为 内存管理方面的存储方式。
1.
```
     public startic void main(String[] args){
          byle x= 1;
          byle y=x;
          x = 2;
          sout(y);//输出为1，x和y完全独立。
     }
```
2.
```
     import（Java.awt)
     public startic void main(String[] args){
          Point  point1 = new Point(x:1, y:1);
          Point  point2 = point1;
          point.x=2;
          sout(point2);//x发生改变
     }
```

indexof（）检查索引
replace（）替换字符
toLowerCase（）将大写改为小写；
trim（）在字符串开头或结尾去除空格；


[50:47](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=3047.984947)
转义字符\:可转   \"   \n   \t   \\

数组
```
public static void main(String[] args){
     int[] number = new int[5];
     int[] numbers = { 1,2};
     number[0]  = 1;
     number [1] = 2;
     //创建数组
}

```

二维数组

```
public static void main(String[] args){
     int[][] numbers = new int[2][3];
     int[][] number {{1,2,3},{4,5,6}}
     numbers[0][0]= 1;
     System.out.println(Arrays.deepToString(number));
     //打印二维数组
     

}
```

设置常量  ：final float  pi = 3.14；

转换变量类型：double result = （double）10 /（double）3；



[01:08:50](https://www.youtube.com/watch?v=eIrMbAQSU34&t=826s#t=4130.377939)
强制转换和类型转换


```
mian(){
short x = 1;
int y = x + 2;
/*y=3   bybe > short > int > long > float > double  强制转换(int)x:显示转换*/
}
```

转换：类型.parse类型（）；进行转换

