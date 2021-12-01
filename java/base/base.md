Java定义的数据类型
1.变量按照数据类型来分:
数据类型:
  基本数据类型 8种
     数值型
        整数类型（byte,short,int,long）
        浮点类型（float,double）
    字符型（char）
    布尔型（boolean）

  引用数据类型（reference type）
    类（class）<-字符串这里
    接口(interface)
    数组（array）

2.变量在类中声明的位置
   成员变量 vs 局部变量

1byte=8bit
1字符 = 2字节 


基本数据类型之间的运算规则：
1.自动类型提升:
  结论：当容量小的数据类型的变量与容量大的数据类型的变量做运算时，结果自动提升为容量大的数据类型。  
      byte,char,short ->int ->long -> float -> double 

   特别的：当byte char short三种类型的变量做运算时，结果为int型

2.强制类型转换:
   2.1 需要使用强转符:()
   2.2 注意点: 强制类型转换,可能导致精度损失。 
  double d1 = 12.9;
  int i1 = (int)d1;

String属于引用数据类型，声明String变量类型使用""
