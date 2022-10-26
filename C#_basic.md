<img src="Photos/Csharp1.png" width = "750" align=center />  <br>

对象（Object）类型  
对象（Object）类型 是 C# 通用类型系统（Common Type System - CTS）中所有数据类型的终极基类。  
Object 是 System.Object 类的别名。所以对象（Object）类型可以被分配任何其他类型（值类型、引用类型、预定义类型或用户自定义类型）的值。但是，在分配值之前，需要先进行类型转换。

当一个值类型转换为对象类型时，则被称为 装箱；另一方面，当一个对象类型转换为值类型时，则被称为 拆箱。
```
object obj;
obj = 100; // 这是装箱
```
### integer type
```
int max = int.MaxValue;
int min = int.MinValue;
Console.WriteLine($"The range of integers is {min} to {max}");
```

### decimal type
```
decimal min = decimal.MinValue;
decimal max = decimal.MaxValue;
Console.WriteLine($"The range of the decimal type is {min} to {max}");
```
```
decimal c = 1.0M;
decimal d = 3.0M;
Console.WriteLine(c / d);
```


### double type
```
double max = double.MaxValue;
double min = double.MinValue;
Console.WriteLine($"The range of double is {min} to {max}");
```
```
double a = 1.0;
double b = 3.0;
Console.WriteLine(a / b);
```
