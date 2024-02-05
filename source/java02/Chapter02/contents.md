#### 数据类型

Java是强类型语言，强类型就是一个变量声明的时候，必须先指定类型，而且声明后这个变量只能存这种类型的数据。

Java有两种数据类型，一种是基础数据类型，一种是引用数据类型。

##### 基础数据类型

Java的基础数据类型有八种四类
- 整型: `byte`、`short`、`int`、`long`
- 浮点型: `float`、`double`
- 字符型: `char`
- 布尔型: `boolean`

```java
// byte类型范围 -128~127
byte b = 1;
// short类型范围 -65536~65535
short s = 2; 
// int类型范围 正负21亿
int i = 3;   
// long类型范围 能表示长度是19位的数
long l = 4L; 
float f = 1.1F;
double d = 1.2;
char c = 'A';
boolean bo = false;
```