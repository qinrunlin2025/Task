//一、运算符

/*1.一元运算符：只有一个运算数的运算符如 ++，-- ， + (正号)
++ --: 自增(自减)
* ++(–) 在前，先自增(自减)，再运算
* ++(–) 在后，先运算，再自增(自减)*/
var num = 3;
//声明一个变量，名字叫 num，并给它赋初始值 3。
var a = ++num;
/*你先把牌子从 3翻到 4。
然后你告诉 a：“牌子现在是 4。” 所以 a记下了 4。*/
var b = num++;
/*你先告诉​ b：“牌子现在是 4。” 所以 b记下了 4。
然后你才把牌子从 4翻到 5。*/
document.write (num + "<br>"); //5
document.write (a + "<br>"); //4
document.write (b + "<br>"); //4
/*所以最后，牌子（num）是 5，
a记下的是第一次翻牌后的 4，
b记下的是第二次翻牌前的 4。*/
console.log(num); //5
console.log(a); //4
console.log(b); //4
/*想消除红线，可以暂时使用 console.log来替代，
结果会输出到浏览器的“控制台”中。*/

/*其他类型转number：
string转number：按照字面值转换。
如果字面值不是数字，则转为NaN（不是数字的数字）
boolean转number：true转为1，false转为0*/
var c =+"123";
var d =+"123abc";
document.write(typeof(c)+"<br>");//得到：number
document.write(c+1);//得到：124
document.write("<br>");//换行
document.write(typeof(d)+"<br>");//得到number
document.write(d+1);//得到：NaN(不是数字的数字)
document.write("<hr>");/*这行代码输出一个 HTML 水平线标签 <hr>，
在网页上显示为一条横贯页面的水平线，通常用于内容的分割。*/

var flag1 = + true;
/*第一行：var flag1 = + true;
这行代码是声明变量并赋值的一个语句。
var: 关键字，用于声明一个变量。意思是“我要创建一个变量了”。
flag1: 这是你为变量起的名称，可以理解为这个数据存储空间的标签。
=: 赋值操作符。它的作用是将右边的值计算出来，然后存入左边的变量里。
+ true: 这是这行代码的核心。
true是一个布尔值（Boolean），代表逻辑上的“真”。
它前面的 +是一元正号操作符。在这里，它的主要作用不是做数学加法，
而是类型转换：它会尝试将紧随其后的值转换为数字类型（Number）。
JavaScript 中规定，布尔值 true转换为数字是 1，
false转换为数字是 0。
;: 语句结束符，表示一个完整的代码语句到此结束。
整行意思：声明一个叫 flag1的变量，
然后将布尔值 true转换为数字 1，并把数字 1赋值给 flag1。*/
var flag2 = + false;
document.write(typeof(flag1)+"<br>");//得到：number
/*typeof(flag1)：检查 flag1是什么类型的数据。
因为 flag1是数字，所以这里得到的结果是 "number"。
2.+ "<br>"：+号把上面的结果 "number"和一个换行符 <br>拼接在一起，
变成 "number<br>"。这样写完“number”之后就会另起一行。
3.document.write(...)：执行“在网页上写字”这个动作。
所以，最终效果就是：网页上会显示“number”这个词，
并且光标会移到下一行，准备显示后续内容。*/
document.write(flag1+"<br>");//得到 1
document.write(flag2+"<br>");//得到 0

/*2.算数运算符 + - * / % ... */
var a = 2;
var a = 3;
document.write(a +b +"<br>");//5
document.write(b -a +"<br>");//1
document.write(a *b +"<br>");//6
document.write(a /b +"<br>");//0.66666666666666666666
document.write(a %b +"<br>");//2

/*3.赋值运算符 = += -= ....*/
var a = 2;
// 准备一个叫 a的钱包，往里放2块钱。
a+=2;
// 把钱包里的钱拿出来，加上2块钱，再把总和放回去。现在钱包里有：2 + 2 = 4块钱
document.write(a +"<br>");//4
// 在网页上写出钱包里现在的钱数（4），然后换一行。
a-=2;
// 从钱包里拿出2块钱。现在钱包里有：4 - 2 = 2块钱
document.write(a +"<br>");//2
a*=2;
// 让钱包里的钱变成原来的2倍。现在钱包里有：2 × 2 = 4块钱
document.write(a +"<br>");//4
a/=2;
// 把钱包里的钱平均分成2份，只留一份。
document.write(a +"<br>");//2
/*这段代码就是反复对钱包 a里的钱进行 加、减、乘、除​ 操作，
每操作一次，就把最新的金额显示在网页上。
所以网页上最终会显示：
4
2
4
2*/

/*4.比较运算符 > < >= <= == ===(全等于）*/
/*两种比较方式
1.类型相同的：直接比较
字符串：按照字典序进行比较。
（字典序：按位逐一进行比较，直到得出大小为止）
2.类型不同：先进行类型转换后进行比较
===全等于。在比较之前，会先判断类型，如果类型不同，则直接返回false。*/
var a="abc";
// 把一个叫 a的盒子清空，然后放进一个文字"abc"。
document.write((3>4) +"<br>");//false
/*判断“3大于4”这句话对不对。
运算：3显然不大于4，所以这句话是错的。
结果：在网页上输出 false（表示“错”），然后换行。*/
document.write("abc">"acb"+"<br>");//false
// 因为 b< c，所以整个单词 "abc"就比 "acb"小。
document.write(typeof(a) +"<br>");//string
/*用 typeof看看变量 a是什么类型。
结果：因为 a是文字 "abc"（看上一张图），
所以类型是 string（字符串）。
输出：string，然后换行。*/
document.write(("123"==123)+"<br>");//true
document.write(("123"===123) +"<hr>");//false
// ===（全等于）：很严格。必须数据类型和值都完全一样，才认为是相等的。

/*5.逻辑运算符 &&与 || 或 ！非*/
/*其他类型转boolean：
1.number类型：0或NaN为假，其他都为真
2.string类型：除了空字符(""),其他都为true
3.null和undefined类型：都为false
对象：所有对象都为true*/

//boolean
var falg = true;
// 创建一个叫 falg的盒子，直接往里面放入 true（真）。
document.write(flag+"<br>");
// 把盒子里的值拿出来看。现在是 true。
document.write(!flag+"<br>");
/*!是“非”运算符，意思是 取相反的值。
!作用在它上面：!true的结果就是 false。*/
document.write("<hr>");
// 在网页上画一条横线，用来分隔内容。

//number
var num = 3;
var num2 = 0;
var num3 = NaN;
 document.write(!num + "<br>"); 
  // false (!num 先进行类型转化 3->true ， ！ture = false ）
document.write(!num2 + "<br>");   // true
document.write(!num3 + "<br>");   // true

//string
var str = "abc";
var str2 = " ";
document.write(!str + "<br>");   // false
document.write(!str2+ "<br>");   // true

//null & undefined
var obj = null;
var obj2;
var obj3 = underfined;
document.write(!obj + "<br>");   // true
// null&undefined:都是false
document.write(!obj2 + "<br>");   // true
document.write(!obj3 + "<br>");   // true

//对象
var obj4 = new Object();
document.write(!obj4 + "<br>");   // 所有对象都为true

/*6.三元运算符 ？：表达式
*语法：表达式？值1：值2；
（判断表达式的值，如果是true则取值1，如果是false则取值2）*/
var a = 6;
var b = 5;
var c = a>b?"a>b":"a<b";
document.write(c);   //a>b

// 二、流程控制语句+特殊语法

// JavaScript中特殊的语法
// 1.语句以；结尾，如果一行只有一条语句则；可以省略
<script>
  var s = 2
  document.write(s)
</script>
/*2.变量的定义使用var关键字，也可以不使用
用：定义的变量为局部变量
不用：定义的变量为全局变量（容易报错一般不用）
<script>
  s = 2
  document.write(s)
</script>*/

// 流程控制语句
// 1.if...else...
var s=0;
if(s===0) document.write(true);//true
else document.write(false);
// 2.switch:在java JDK1.7后，switch语句可以接受的数据类型：
/*byte int short char，枚举
在JavaScript中，switch语句可以接受任意的原始数据类型*/
var s="abc";///可以接受任何原始数据类型s=abc、true、null underfined
switch(s){
  case 1:
    document.write("number");break;
  case true:
    document.write("boolean");break;
  case "abc":
    document.write("string");break;
  case null:
    document.write("null");break;
  case undefined:
    document.write("undefined");break;
}
// 3.while
var sum2=0;
// 准备一个叫 sum2的“总和盒子”，初始金额为0。
var i =0;
// 准备一个叫 i的“计数器”，从0开始数。
while(i<=100){//开始循环。
// 只要“计数器” i的值 小于等于100，就重复执行 {}里的所有步骤。
  sum+=i;//把当前“计数器” i的数值，加到“总和盒子” sum里。
  i++;//给“计数器” i加1（比如从0变成1，从1变成2……）。
}//循环体结束。执行完这行后，会跳回到第4行的 while处再次检查条件。
document.write(sum+"<hr>");//循环结束后，5050
// 4.do...while
var flag=0;
var sum3=0;
do{
  sum3+=flag;
  flag++;
}while(flag<=100)
document.write(sum3);//5050
/*（先干活，再检查）
这个人比较莽撞，他的规矩是：
不管对不对，先干一次再说！（先把当前的数加一次）
干完了再问自己：“我数到100了吗？”
如果没数到，就回去继续干。
风险：​ 即使一开始就让他从101开始数（已经超过100了），
他也会先把101加一次，然后才发现不对。它保证至少会数一次。*/
// 5.for
var sum = 0;
for(var i = 0;i <=100;i++){
  sum+=i;
}
document.write(sum);//5050
/*（先检查，再干活）
这个人非常严谨，他的规矩是：
先立规矩：​ 从几开始数 (i=0)，数到几结束 (i<=100)，怎么数 (i++)。
干活前先检查：“轮到这个数了吗？没超过100吧？”
如果符合规矩，就加一次，然后数下一个数。
如果不符合（比如数到101了），就立刻停止。
特点：​ 如果一开始就从101开始，他一次活都不会干。干活的次数可能为0。*/

