[TOC]

# 面向对象概述

## 面向对象的内涵

一个类比：将C#比作画笔，VS开发环境比作画板，学会C#和VS开发环境的使用，也只是学会了使用画笔和画板这两种工具罢了，但是，使用相同的工具，在相同的经验水平下，若是带有一定的思想高度去画画，画出来的东西却有很大的分别，因此技术很重要，思想更重要！从思想的高度来看待编程时，语言和平台变为一个人抒写想法的载体。因此学习程序设计的思想非常重要。

### 世间万物皆对象

1. 每个对象都有各自的内部状态和运动规律
2. 按照对象的属性和运动规律的相似性，可以将相近的对象划分为一类
3. 复杂的对象由相对简单的对象通过一定的方式组成
4. 不同对象的组合及其间的相互作用和联系构成了各种不同的系统，构成了我们所面对的客观世界

### 人类思维及认知的一般过程

![](https://upload-images.jianshu.io/upload_images/25288552-538bc0f2370f4405.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-b96a3c994a58d77b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 面向对象程序设计

面向对象的出发点和基本原则是尽可能模拟人类习惯的思维方式，使开发软件的方法与过程尽可能接近人类认识世界、解决问题的方法与过程。面向对象程序设计（Object Oriented Programing，OOP）是面向对象的思想在程序设计中的具体应用

1. 软件是由各种各样的对象构成
2. 每个对象都有各自的属性和行为
3. 具有相似属性和行为的对象可以归纳为一类
4. 复杂的对象由相对简单的对象构成
5. 不同对象的组合及其间的相互作用和联系构成了系统
6. 对象的相互作用通过消息传递，对象根据接受到的消息做成自身的反应
7. 程序 = 对象 + 消息

## 面向对象的基本特征

#### 封装

1. 封装是将对象的属性和行为封装起来的机制

2. 将对象的属性和行为封装起来的载体就是类，类通常对用户隐藏其实现细节

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-25114f0849b11f5e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 封装的副作用：如果强调严格的封装，则对象的任何属性都不允许外部直接存取，因此就要增加许多没有其他意义、只负责读或写的服务，从而为编程工作增加了负担，增加了运行开销。为了避免这一点，语言往往采取一种比较灵活的做法，即允许对象由不同程度的可见性

#### 继承

1. 概述

   * 继承机制允许创建分等级层次的类，是实现父类和子类之间共享数据和方法的机制

   * 继承就是子类继承父类的特征和行为，使得子类对象（实例）具有父类的属性和方法

     ![image.png](https://upload-images.jianshu.io/upload_images/25288552-3fd15ea4a2412e5a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

   * 继承意味着“自动地拥有”，即在子类中不必重新对已经在父类中所定义过的属性和行为进行定义，而是子类自动地、隐含地拥有其父类的属性和行为
   * 继承提高了程序代码的复用性、可扩展性，即一个子类既有自己定义的属性和行为，又有继承下来的属性和行为

2. 继承的关系

   一个父类可以拥有多个子类，一个派生类也可以成为其他类的基类![image.png](https://upload-images.jianshu.io/upload_images/25288552-ad410d4787f24ded.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 单继承和多继承

   * 单继承：指任何一个类都只有一个单一的分类，即派生类是由一个且只能是一个基类创建

   * 多继承：指一个类可以有一个以上的父类。它的静态的数据属性和操作从所有这些父类中继承

     ![image.png](https://upload-images.jianshu.io/upload_images/25288552-d691433ef1843b7c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 多态性（Ploymorphism）

* 多态性主要是指在一般类中定义的属性或行为，在被特殊类继承之后可以具有不同的数据类型或表现出不同的行为

* 多态性使得同一个属性或行为在一般类和各个特殊类中具有不同的意义

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-3e552f00910be5fa.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 面向对象的优点

* 面向过程与面向对象
  * 两者都是程序设计的基本思想与方法
  * 两者的出发点不同：功能分解与对象分解
  * 两者的思维方法不同，对世界的理解不同

![image.png](https://upload-images.jianshu.io/upload_images/25288552-46a088d56d8b27cf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-1fe9dfbfee96bbb0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-abf8a7fb6a2add3d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-2dd273b340e70e57.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-61537bad548f74ca.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-1a2e57750717311e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 两者之间相辅相成

  * 面向对象的技术是在面向过程的基础之上发展而来，又提供了抽象、封装、继承、多态技术手段
  * 面向对象的设计包含了面向过程，面向对象比面向过程站到了一个更高的层次上，主要进行总体结构模型设计（构建类），对数据和方法进行封装，面向过程主要是写函数或过程也就是确定类中的方法的实现

* 面向对象的主要优点

  * 与人类习惯的思维方法一致

    * 以对象为核心，强调对现实概念的模拟
    * 面向对象尽可能地按照人类认识世界的方法和思维方式来分析和解决问题，使人们分析、设计一个系统的方法尽可能接近认识一个系统的方法
    * 数据和操作封装成统一体

    ![image.png](https://upload-images.jianshu.io/upload_images/25288552-db61000655d073c1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  * 稳定性好

    * 软件系统结构根据问题域模型建立
    * 以对象模拟实体，实体相对稳定，故系统也相应稳定
    * 需求变化不会引起结构的整体变化，只需局部性修改

  * 可重用性好

    * 对象具有较强的自含性和独立性
    * 对象和类提供了理想的模块化机制和可重用的软件成分
    * 继承性为面向对象方法提供了比传统方法更广泛、更规范、更简单的重用机制

  * 可维护性好

    * 稳定性好
    * 容易修改
      * 类独立性强，修改完全不影响软件的其他成分
      * 继承性和多态性，使修改和扩充容易实现
    * 容易理解
    * 容易测试、调试

  * 较易开发大型软件产品

    * 把一个大型产品看作是一系列本质上相互独立的小产品来处理
    * 降低了开发的技术难度，而且也使得对开发工作的管理变得容易
    * 自底向上分析和设计，自顶向下实现（继承），可重用性好

## 定义类

### 类的声明与实例化

#### 类的声明

类是一种数据结构，包含静态的属性和动态的方法

![image.png](https://upload-images.jianshu.io/upload_images/25288552-bcdbbadb2c8b85e7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 添加类文件

  在声明一个类之前，需要向工程中新添加一个类文件。方法如下，示例（见书）

* 在类文件中声明类

  C#中类的声明需要使用class关键字，并把类的主体放在花括号中。格式如下：

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-e80a4db9ce5fd373.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 类的访问级别由类的修饰符进行限定

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-fded11522f8a85bc.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

<img src="https://upload-images.jianshu.io/upload_images/25288552-e4b8178b0a819a35.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="image.png" style="zoom: 67%;" />

![image.png](https://upload-images.jianshu.io/upload_images/25288552-f0bf37e3369b74d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

``` C#
//类的声明示例:
using System;

namespace C_Program
{
    class student
    {
        public class Student //类的声明
        {
            //属性
            public string strName; //公有属性
            public int nAge; //私有属性

            //方法，这里没有
        }

        //Main函数类
        class Test
        {
            //应用程序的主入口点
            static void Main()
            {
                Student s = new Student();
                s.strName = "张三";
                s.nAge = 19;
            }
        }
    }
}
```

#### 类的实例化

C#使用关键字来实现类的实例化，其格式如下：

![image.png](https://upload-images.jianshu.io/upload_images/25288552-ba1843068b66ead2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 类的静态特性与动态行为

* 对象的两个特征

  对象具有的这两项特征通常被封装在一起，共同体现事物的特性，两者相辅相成，不能分隔

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-03f761af83c741af.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  * 静态特性：双层，红色，限载36人……
  * 动态行为：启动，加速，减速，刹车……

* 类的静态特性

  属性（或字段）可以看作是类的静态描述。字段的定义格式如下：

  [访问修饰符]  数据类型  字段名

  例如：public string strName;    private int nScore;

  实例：public和private修饰符的作用

  ``` C#
  using System;
  
  namespace C_Program
  {
      class student
      {
          public class Student
          {
              //属性
              public string strName; //公有属性
              private int nAge; //私有属性
  
              //方法，这里没有
          }
  
          //Main函数类
          class Test
          {
              //应用程序的主入口点
              static void Main()
              {
                  Student s = new Student();
                  s.strName = "张三";
                  s.nAge = 19;
              }
          }
      }
  }
  
  报错信息：
      CS0122	“student.Student.nAge”不可访问，因为它具有一定的保护级别	Test4	
  ```

* 类的动态行为

  类的属性是客观世界实体性质的抽象，而方法是实体所能执行的操作，体现了类的动态行为。其定义格式如下：

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-1b06534c0f58d29e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  ``` C#
  //实例：类的公有方法的实例
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  namespace C_Program
  {
  	public class Student
  	{
  		private int nAge; //私有属性
  		public void SetAge(int _nAge)
  		{
  			this.nAge = _nAge;
  		}
  		public int GetAge()
  		{
  			return this.nAge;
  		}
  	}
  	class Test
  	{
  		static void Main()
  		{
  			Student s = new Student();
  			s.SetAge(20); //赋值年龄
  			Console.WriteLine(s.GetAge());
  			// 获取年龄
  		}
  	}
  }
  ```

### 继承

继承是指一个类可以建立在另一个类的基础上，可以继承另一个类的属性和方法。被继承的类被称为基类（父类），通过继承产生的类叫做派生类（子类）

![image.png](https://upload-images.jianshu.io/upload_images/25288552-d4b21b9e77f8f263.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 继承的本质

  继承的本质是代码重用。当要构造一个新的类时，通常无需从头开始

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-93ef740e6258b32a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 继承的实现

  实现继承的语法格式：

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-575668ad87c1391c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  ``` C#
  //类的继承
  using System;
  
  namespace C_Program
  {
  	public class Student // 学生类
  	{
  		public string strName; // 姓名
  		public int nAge; // 年龄
  	}
  	public class CollegeStudent : Student //大学生类继承学生类
  	{
  		public string strDepartment; // 所在系
  	}
  	class Program
  	{
  		static void Main(string[] args)
  		{
  			Student s = new Student(); // 创建Student类的对象s
  			s.strName = "xiaobao";
  			s.nAge = 18;
  			Console.WriteLine("姓名：{0}，年龄：{1}", s.strName, s.nAge);
  
  			Console.WriteLine("---------使用子类---------"); // 以下演示子类使用
  
  			CollegeStudent c = new CollegeStudent(); // 创建CollegeStudent类的对象c
  			c.strName = "小宝";
  			c.nAge = 23;
  			c.strDepartment = "管理科学系";
  			Console.WriteLine("姓名：{0}，年龄：{1}岁，所属系：{2}", c.strName,
  			c.nAge, c.strDepartment);
  			Console.ReadKey();
  		}
  	}
  }
  ```

  ``` C#
  //练习：参考上例基于类继承自行编程实现“大学”、“院系”和“班级”三者的继承关系
  using System;
  
  namespace C_Program
  {
  	public class College
  	{
  		public string CollegeName;
  	}
  
  	public class School : College
  	{
  		public string SchoolName;
  	}
  
  	public class Class : School
  	{
  		public string ClassName;
  	}
  
  	class Test3
  	{
  		static void Main()
  		{
  			College c = new College();
  			School s = new School();
  			Class cl = new Class();
  
  			c.CollegeName = "海南大学";
  
  			s.CollegeName = "海南大学";
  			s.SchoolName = "管理学院";
  
  			cl.CollegeName = "海南大学";
  			cl.SchoolName = "管理学院";
  			cl.ClassName = "2019级信息管理与信息系统班";
  
  			Console.WriteLine("{0}\n{1}\t{2}\n{3}\t{4}\t{5}", c.CollegeName,
  				s.CollegeName, s.SchoolName,
  				cl.CollegeName, cl.SchoolName, cl.ClassName);
  		}
  	}
  }
  ```

* 不能被继承的类

  这里需要注意的是，如果Person类时以sealed关键字进行修饰的类，那么Person类就不能被继承，Student类中的代码需要全部重写

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-fe984de97fe4449e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 构造函数和析构函数

### 构造函数

当定义了一个类之后，就可以通过new运算符将其实例化，产生一个对象。为了能规范、安全地使用这个对象，C#提供了对对象进行初始化的方法，这就是构造函数。在C#中，构造函数是当类实例化时首先执行的函数。只要定义一个对象，系统就会自动在创建对象时调用构造函数，构造函数的执行是无条件的，并且不需要程序手工干预。也就是说，不需要人为地去显示地调用

* 构造函数的声明及其特殊性

  <img src="https://upload-images.jianshu.io/upload_images/25288552-b22f353bc486e78c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="image.png" style="zoom:50%;" />
  * 构造函数的函数名和类的名称一样
  * 构造函数可以带参数，但没有返回值
  * 构造函数在对象定义时被自动调用
  * 如果没有给类定义构造函数，则编译系统会自动生成一个默认的构造函数
  * 构造函数可以被重载，但不可以被继承
  * 一般地，构造函数的类型修饰符总是public。如果是private，则表示这个类不能被实例化，这通常用于只含有静态成员的类中

* 无参构造函数

  ``` C#
  //例：通过无参构造函数，实现在产生一个学生对象时为其年龄赋值
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	public class Student // 学习类
  	{
  		public int age;
  		public Student() // 构造函数，为年龄赋值
  		{
  			age = 18;
  		}
  	}
  	class Test
  	{
  		static void Main(string[] args)
  		{
  			Student s = new Student();
  			Console.WriteLine(s.age);
  			Console.ReadKey();
  		}
  	}
  }
  ```

  Console.ReadLine() 会等待直到用户按下回车，一次读入一行。

  Console.ReadKey() 则是等待用户按下任意键，一次读入一个字符

* 带参构造函数

  ``` C#
  //例：通过带参构造函数，实现在产生一个学生对象时为其年龄赋值
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	public class Student // 学生类
  	{
  		public int age;
  		public Student(int i) // 构造函数
  		{
  			age = i;
  		}
  	}
  	class Test
  	{
  		static void Main(string[] args)
  		{
  			Student s = new Student(18);
  			Console.WriteLine(s.age);
  			Console.ReadKey();
  		}
  	}
  }
  ```

* 默认的构造函数

  ``` C#
  //例：如果不定义构造函数，编译系统自动生成一个默认构造函数
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	public class Student
  	{
  		public int age;
  	}
  	class Test
  	{
  		static void Main(string[] args)
  		{
  			Student s = new Student();
  			Console.WriteLine("His age is:" + s.age);
  			Console.ReadKey();
  		}
  	}
  }
  ```

* 构造函数的重载

  * 构造函数可以没有参数，也可以有一个或多个参数
  * 在类的声明中，存在多个参数列表不相同（参数个数不同，或参数类型不同，或两者都不同）的构造函数的情形，称为构造函数的重载
  * 构造函数的重载，可以使类实例化对象更灵活

  ``` C#
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	class Time
  	{
  		public int nHour, nMinute, nSecond;
  		public Time() // 无参构造函数
  		{ nHour = nMinute = nSecond = 0; }
  		public Time(int Hour) // 带一个参数的构造函数
  		{ nHour = Hour; nMinute = nSecond = 0; }
  		public Time(int Hour, int Minute) // 带两个参数的构造函数
  		{ nHour = Hour; nMinute = Minute; nSecond = 0; }
  		public Time(int Hour, int Minute, int Second) // 带三个参数的构造函数
  		{ nHour = Hour; nMinute = Minute; nSecond = Second; }
  		static void Main()
  		{
  			Time t1, t2, t3, t4;
  			// 对t1, t2, t3, t4分别调用不同的构造函数
  			t1 = new Time();
  			t2 = new Time(10);
  			t3 = new Time(10, 30);
  			t4 = new Time(10, 30, 30);
  			Console.WriteLine("t1的时间为：{0}时{1}分钟{2}秒",
  			t1.nHour, t1.nMinute, t1.nSecond);
  			Console.WriteLine("t2的时间为：{0}时{1}分钟{2}秒",
  			t2.nHour, t2.nMinute, t2.nSecond);
  			Console.WriteLine("t3的时间为：{0}时{1}分钟{2}秒",
  			t3.nHour, t3.nMinute, t3.nSecond);
  			Console.WriteLine("t4的时间为：{0}时{1}分钟{2}秒",
  			t4.nHour, t4.nMinute, t4.nSecond);
  		}
  	}
  }
  
  (base) PS D:\Porgram\C#Program> dotnet run
  t1的时间为：0时0分钟0秒
  t2的时间为：10时0分钟0秒
  t3的时间为：10时30分钟0秒
  t4的时间为：10时30分钟30秒
  ```

  ``` C#
  //参考上例实现 学生类的构造函数及其重载，学生类通常包括姓名、班级、学号、专业等
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	public class Student
  	{
  		// 属性
  		public string nName, nStudentclass, nId, nProfession;
  
  		public Student(string Name)
  		{
  			nName = Name;
  		}
  
  		/*public Student(string Studentclass, string Name)
  		{
  			nStudentclass = Studentclass;
  			nName = Name;
  			nId = nProfession = "";
  		}*/
  
  		public Student(string Name, string Studentclass)
  		{
  			nName = Name;
  			nStudentclass = Studentclass;
  			nId = nProfession = "";
  		}
  
  		public Student(string Name, string Studentclass, string Id)
  		{
  
  			nName = Name;
  			nStudentclass = Studentclass;
  			nId = Id;
  			nProfession = "";
  		}
  
  		public Student(string Name, string Studentclass, string Id, string Profession)
  		{
  			nName = Name;
  			nStudentclass = Studentclass;
  			nId = Id;
  			nProfession = Profession;
  		}
  	}
  
  	class Test
  	{
  		static void Main()
  		{
  			Student s1 = new Student("彭泽华");
  			Student s2 = new Student("彭泽华", "2019级信息管理与信息系统班");
  			Student s3 = new Student("彭泽华", "2019级信息管理与信息系统班",
  				"20190608310007");
  			Student s4 = new Student("彭泽华", "2019级信息管理与信息系统班",
  				"20190608310007", "信息管理与信息系统");
  
  			Console.WriteLine("姓名：{0}\t班级：{1}\t学号：{2}\t专业：{3}", s1.nName,
  				s1.nStudentclass, s1.nId, s1.nProfession);
  			Console.WriteLine("姓名：{0}\t班级：{1}\t学号：{2}\t专业：{3}", s2.nName,
  				s2.nStudentclass, s2.nId, s2.nProfession);
  			Console.WriteLine("姓名：{0}\t班级：{1}\t学号：{2}\t专业：{3}", s3.nName,
  				s3.nStudentclass, s3.nId, s3.nProfession);
  			Console.WriteLine("姓名：{0}\t班级：{1}\t学号：{2}\t专业：{3}", s4.nName,
  				s4.nStudentclass, s4.nId, s4.nProfession);
  		}
  	}
  }
  
  运行结果：
  姓名：彭泽华 班级：  学号：  专业：
  姓名：彭泽华    班级：2019级信息管理与信息系统班        学号：  专业：
  姓名：彭泽华    班级：2019级信息管理与信息系统班        学号：20190608310007    专业：
  姓名：彭泽华    班级：2019级信息管理与信息系统班        学号：20190608310007    专业：信息管理与信息系统
  			 
  D:\Program\C#\Test3\bin\Debug\netcoreapp3.1\Test3.exe (进程 21600)已退出，代码为 0。
  按任意键关闭此窗口. . .
  ```

### 析构函数

创建实例时，系统会为实例分配空间，当实例用完以后，就要回收这些分配出去的空间，这时要用析构函数。析构函数是当实例（也就是对象）从内存中销毁前最后执行的函数。这个函数的执行和构造函数一样也是无条件的。即，只要销毁一个对象，不用显式地调用析构函数，系统都会自动在销毁对象时调用析构函数。

![image.png](https://upload-images.jianshu.io/upload_images/25288552-11376829a57f05ea.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

* 析构函数的名字也与类名相同，只是需要在其前面加一个符号“~”
* 析构函数不能带任何参数，没有任何返回值，也没有任何访问修饰符
* 当撤销对象时，自动调用析构函数
* 析构函数不能被继承，也不能被重载

``` C#
//为Student类建立析构函数（Visual Studio中的析构函数为什么没有执行？）
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	public class Student
    {
        public int age;
        ~Student()
        {
            Console.WriteLine("Call Destruct Method.");
        }
    }

    class Test
    {
        static void Main()
        {
            Student s = new Student();
            s.age = 19;
            Console.WriteLine(s.age);
        }
    }
}
```

``` C#
//构造函数和析构函数的使用（Visual Studio中的析构函数为什么没有执行？）
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
    class Point
    {
        int x, y, z;
        public Point()
        {
            this.z = 0;
        }
        
        public Point(int x, int y)
        {
            this.x = x;
            this.y = y;
            this.z = x + y;
        }
        
        public int _Z
        {
            get { return this.z; }
            set { this.z = value; }
        }

        ~Point()
        {
            Console.WriteLine("~Point() is being called.");
        }
        
        class Test
        {
            static void Main()
            {
                Point p1 = new Point(1, 5);
                Point p2 = new Point();
                Console.WriteLine("p1.z = " + p1._Z);
                Console.WriteLine("p2.z = " + p2._Z);
            }
        }
    }
}
```

``` C#
//构造函数和析构函数的使用（Visual Studio中的析构函数为什么没有执行？）
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
    class Hero
    {
        public int x;
        public Hero(int i) //构造函数
        {
            x = i;
        }

        ~Hero() //析构函数
        {
            Console.WriteLine("This program is end");
        }
    }

    class Test
    {
        static void Main()
        {
            Hero aa = new Hero(3);
            Console.WriteLine(aa.x);
        }
    }
}
```

事实上，用户一般并不需要自定义析构函数，.NET Framework提供了默认的析构函数执行内存清理等工作；如果需要在销毁对象之前完成一些特殊的任务才需要使用自定义的析构函数。

## 方法

方法是类中用于执行计算或进行其他操作的函数成员，表示类的行为，告诉我们类能够做什么，隐藏细节，封装、重用。

### 方法的分类、定义、调用和返回

* 方法的分类

  * 静态方法：使用static修饰的方法

    静态方法表示类所具有的行为，而非其某个具体对象所具有的行为。在调用静态方法时不需要实例化类的对象，直接使用类引用即可

  * 非静态方法：没有使用static修饰的方法

* 方法的定义

  方法由方法头和方法体组成，其一般定义的格式为：

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-b42a6098a3af1f1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-52fa94b9777dfa6d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  ``` C#
  //示例
  class Motorcycle
  {
      public static void StarEngine(){} //静态方法
      public void AddGas(int gallons){}
      public int Drive(int miles, int speed){return 0;}
  }
  ```

  Motorcycle类中定义了三个方法：

  * 第一个是无参数、无返回值、名为StartEngine的静态方法

  * 第二个方法名为AddGas，也同样没有返回值，但有一个参数
  * 第三个方法是带有两个形式参数、有int类型返回值的Drive方法，该方法通过return语句返回0值

* 方法的调用

  方法的调用类似于访问字段，格式如下：在类名/对象名之后用“.”运算符来调用类中的方法名，参数在方法名后的括号中列出，多个参数之间用逗号隔开。

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-b944bf5a822dd5e0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  静态方法用类名调用，非静态方法用对象名调用

  ``` C#
  //示例：方法的调用
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	class Motorcycle
  	{
  		public static void StartEngine() { } // 静态方法
  		public void AddGas(int gallons) { } // 非静态方法
  		public int Drive(int miles, int speed) { return 0; } // 静态方法
  
  		static void Main(string[] args)
  		{
  			Motorcycle moto = new Motorcycle();
  			Motorcycle.StartEngine(); // 由类名调用静态方法
  			moto.AddGas(15);
  			moto.Drive(5, 20);
  		}
  	}
  }
  ```

  ``` C#
  //示例：使用静态方法和非静态方法
  class Test
  {
      static void Main()
      {
          MyClass clsA = new MyClass();
          clsA.a = 10; //正确，访问类MyClass的非静态公有成员
          clsA.b = 20; //错误，不能直接访问类中静态公有成员
          MyClass.a = 30; //错误，不能通过类名访问类中非静态公有成员
          MyClass.b = 40; //正确，访问MyClass中静态公有成员
      }
  }
  ```

* 从方法返回

  一般来说，以下两种情况将导致方法返回

  * 当遇到方法的结束花括号时

  * 当执行到return语句时

    return语句的两种使用形式

    * return; // 用在void方法中，无返回值
    * return 表达式; // 用在有返回值的方法中农，表达式的类型应和方法要返回的类型一致

  ``` C#
  \\示例：通过方法的结束花括号返回
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	class MyClass
  	{
  		public void myMethod()
  		{
  			int i;
  			for (i = 0; i < 10; i++)
  			{
  				if (i % 3 == 0)
  					continue;
  				Console.WriteLine("{0}", i);
  			}
  		}
  		static void Main()
  		{
  			MyClass mycls = new MyClass();
  			// 调用myMethod()方法
  			mycls.myMethod();
  		}
  	}
  }
  
  输出：
  (base) PS D:\Porgram\C#Program> dotnet run
  1
  2
  4
  5
  7
  8
  ```

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-da2e7d09ec9d889f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  ``` C#
  //示例：通过方法的return语句返回到调用者
  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text;
  using System.Threading.Tasks;
  
  namespace C_Program
  {
  	class MyClass
  	{
  		public void myMethod()
  		{
  			int i = 8;
  			if (i >= 5)
  			{
  				i = i * 2;
  				Console.WriteLine(i);
  				return;
  			}
  			else
  			{
  				i = i * 3;
  				Console.WriteLine(i);
  				return;
  			}
  		}
  		static void Main(string[] args)
  		{
  			MyClass mycls = new MyClass();
  			// 调用myMethod()方法
  			mycls.myMethod();
  		}
  	}
  }
  
  输出：
  (base) PS D:\Porgram\C#Program> dotnet run
  16
  ```

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-67c7254ad7480378.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  两种方法的对比：

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-0eb04a46e6f6bda3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)![image.png](https://upload-images.jianshu.io/upload_images/25288552-2aee88758299f72b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 方法的参数

调用方法时，可以给方法传递一个或多个值。传给方法的值称为实参（argument），在方法内部，接受实参值的变量称为形参（parameter），形参在紧跟着方法名的括号中声明。形成的声明语法与变量的声明语法一样

![image.png](https://upload-images.jianshu.io/upload_images/25288552-5f7b2a8f92d89dd0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

形参只在方法内部有效，除了将接受实参的值外，它与一般的变量没什么区别

1. 值参数

   没有用任何修饰符声明的参数为值参数，它表明实参与形参之间按值传递

   * 当这个方法被调用时，编译器为值参数分配存储单元，然后将对应的实参的值拷贝的形参中
   * 实参可以是变量、常量、表达式、但要求其值的类型必须与形参声明的类型相同或者能够被隐式地转换为这种类型

   * 在方法中对形参的修改不会影响外部的实参，也就是说数据只能传入方法，而不能从方法传出

   ``` C#
   using System;
   using System.Collections.Generic;
   using System.Linq;
   using System.Text;
   using System.Threading.Tasks;
   
   namespace C_Program
   {
   	class MyClass
   	{
   		// 实现两个数的交换
   		public void Swap(int x, int y)
   		{
   			int k;
   			k = x; x = y; y = k;
   		}
   	}
   	class Test
   	{
   		static void Main()
   		{
   			int a = 10, b = 20;
   			Console.WriteLine("a = {0}, b = {1}", a, b);
   			MyClass mycls = new MyClass();
   			mycls.Swap(a, b); // 调用Swap()方法
   			Console.WriteLine("a = {0}, b = {1}", a, b);
   			Console.Read();
   		}
   	}
   }
   
   输出：
   (base) PS D:\Porgram\C#Program> dotnet run
   a = 10, b = 20
   a = 10, b = 20
   ```

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-e8d71ef46674d94a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

   思考：如何传值回去给调用者？ 使用return语句？

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-b994838cee127d38.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 引用参数

   用ref修饰符声明的参数为引用参数

   * 引用参数与值参数不同，引用参数并不创建新存储单元，它与方法调用中的实参变量同处一个存储单元。因此在方法内对形参的修改就是对外部实参变量的修改

   * 在函数调用中，引用参数必须被赋初值。在调用时，传递给ref参数的必须是变量，类型必须相同，并且必须使用ref修饰

   ``` C#
   \\示例：使用引用参数
   using System;
   using System.Collections.Generic;
   using System.Linq;
   using System.Text;
   using System.Threading.Tasks;
   
   namespace C_Program
   {
   	class MyClass
   	{
   		public void Swap(ref int x, ref int y)
   		{
   			int k;
   			k = x; x = y; y = k;
   		}
   	}
   	class Test
   	{
   		static void Main()
   		{
   			int a = 10, b = 20;
   			Console.WriteLine("a={0}, b={1}", a, b);
   			MyClass mycls = new MyClass();
   			mycls.Swap(ref a, ref b); // 调用Swap()方法
   			Console.WriteLine("a={0}, b={1}", a, b);
   			Console.Read();
   		}
   	}
   }
   
   输出：
   (base) PS D:\Porgram\C#Program> dotnet run
   a = 10, b = 20
   a=20, b = 10
   ```

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-6059ecb16ce0d2b3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 输出参数

   * 用out修饰符定义的参数称为输出参数。如果希望方法返回多个值，可使用输出参数
   * 两者的区别在于：out参数只能用于从方法中传出值，而不能从调用处接受实参数值；在方法体内out参数被认为是未赋过值的，所以在方法结束前应该对out参数赋值

   ``` C#
   //示例：使用输出参数
   using System;
   using System.Collections.Generic;
   using System.Linq;
   using System.Text;
   using System.Threading.Tasks;
   
   namespace C_Program
   {
   	class MyClass
   	{
   		public void Sum(out int y, out int z)
   		{
   			y = 10 + 10;
   			z = 20 + 20;
   
   		}
   
   		static void Main(string[] args)
   		{
   			int a, b;
   			MyClass mycls = new MyClass();
   			mycls.Sum(out a, out b); // 调用Sum()方法
   			Console.WriteLine("a={0}\nb={1}", a, b);
   		}
   	}
   }
   
   输出：
   (base) PS D:\Porgram\C#Program> dotnet run
   a = 20
   b=40
   ```

4. 参数数组

   用params修饰声明的参数为参数数组

   * 有时候，在调用一个方法时，预先不能确定参数的数量、数据类型等，怎么办呢？一个解决方案是使用params关键字
   * params关键字指明一个输入参数，此输入参数将被看作为一个参数数组，这种类型的输入参数只能作为方法的最后一个参数

   ``` C#
   using System;
   using System.Collections.Generic;
   using System.Linq;
   using System.Text;
   using System.Threading.Tasks;
   
   namespace C_Program
   {
   	class MyClass
   	{
   		public int Sum(params int[] x)
   		{
   			int s = 0;
   			for (int i = 0; i < x.Length; i++)
   				s += x[i];
   			return s;
   		}
   		static void Main(string[] args)
   		{
   			int[] a = { 2, 4, 6, 8, 10 };
   			MyClass mycls = new MyClass();
   			int sum1 = mycls.Sum(1, 3, 5, 7, 9); // 调用Sum()方法
   			int sum2 = mycls.Sum(a); // 调用Sum()方法
   			Console.WriteLine("sum1={0}\nsum2={1}", sum1, sum2);
   		}
   	}
   }
   
   输出：
   (base) PS D:\Porgram\C#Program> dotnet run
   sum1 = 25
   sum2=30
   ```

### 方法的重载

* 在C#中，方法重载是指具有相同的方法名、但参数类型或参数个数不完全相同的两个或两个以上的方法出现在同一个类中

* 当一个重载方法被调用时，C#会根据调用该方法的参数自动调用适当的方法来执行

* 方法重载是让类以统一的方式处理不同类型数据的一种手段

![image.png](https://upload-images.jianshu.io/upload_images/25288552-c80b4ad42970c72a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-dc108891b837dc30.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/25288552-bfd38839ff6fb993.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```C#
//示例1：方法的重载_参数类型相同、参数数目不同
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class MyClass
	{
		public int Add(int x)
		{
			return x + x;
		}
		public int Add(int x, int y)
		{
			return x + y;
		}
		public int Add(int x, int y, int z)
		{
			return x + y + z;
		}
	}
	class Test
	{
		static void Main(string[] args)
		{
			MyClass mc = new MyClass();
			Console.WriteLine(mc.Add(10));
			Console.WriteLine(mc.Add(10, 20));
			Console.WriteLine(mc.Add(10, 20, 30));
		}
	}
}

输出：
(base) PS D:\Porgram\C#Program> dotnet run
20
30
60
```

``` C#
//示例2：方法的重载_参数个数相同，参数类型不同
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class MyClass
	{
		public void Add(double x, double y)
		{
			double s = x + y;
			Console.WriteLine("x+y={0}", x);
		}
		public void Add(string x, string y)
		{
			string s = x + y;
			Console.WriteLine("x+y={0}", s);
		}
	}
	class Test
	{
		static void Main(string[] args)
		{
			MyClass mc = new MyClass();
			mc.Add(10, 20);
			mc.Add("10", "20");
		}
	}
}

输出：
(base) PS D:\Porgram\C#Program> dotnet run
x+y=10
x+y=1020
```

```C#
//示例3：方法的重载_参数个数不同，参数类型不同
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class MyClass
	{
		public void Hello()
		{
			Console.WriteLine("你好！");
		}
		public void Hello(String name)
		{
			Console.WriteLine(name + "，你好！");
		}
		public void Hello(String name, int seatNumber)
		{
			Console.WriteLine(name + "，你好！你的座位号是{0}", seatNumber);
		}
	}
	class Test
	{
		static void Main(string[] args)
		{
			MyClass mc = new MyClass();
			mc.Hello();
			mc.Hello("彭泽华");
			mc.Hello("彭泽华", 10);
		}
	}
}

输出：
(base) PS D:\Porgram\C#Program> dotnet run
你好！
彭泽华，你好！
彭泽华，你好！你的座位号是10
```

```C#
\\示例4：方法的重载_参数个数与类型相同，顺序不同
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class MyClass
	{
		public void Add(string x, int y)
		{
			Console.WriteLine(x + y);
		}
		public void Add(int x, string y)
		{
			Console.WriteLine(x + y);
		}
	}
	class Test
	{
		static void Main(string[] args)
		{
			MyClass mc = new MyClass();
			mc.Add("你好！", 2019);
			mc.Add(2019, "你好！");
			Console.ReadKey();
		}
	}
}

输出：
(base) PS D:\Porgram\C#Program> dotnet run
你好！2019
2019你好！
```

返回值类型不同是不能区分重载的：

![image.png](https://upload-images.jianshu.io/upload_images/25288552-cdb62d47d4815cff.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 属性

### 字段与属性

* 字段

  字段（Field）又称为域，表示与对象或类相关联的变量。即，在定义类时声明的变量，也是对象所要维护的数据。一般格式：[访问修饰符|其他修饰符]<类型><字段名>; 

  * 访问修饰符：public, protected, private(默认值), internal, internal protected
  * 其他修饰符：new, static, readonly, const …
  * 类型：可以是任何有效的类型
  * 字段名：按变量名取名规则
  * 例如：public string strName;         private int score; 

  私有字段的访问：设计一个类时，如果要隐藏一些私有成员，可将这些成员设置成private，禁止类外面的方法直接访问这些成员

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-f6e8ae09e6103599.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  若要访问私有字段？

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-d02097ab2ca31209.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  定义成公有的？这将导致什么问题？      数据安全问题

  ![image.png](https://upload-images.jianshu.io/upload_images/25288552-9e73a89ebbac9542.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  一种可行的办法：使用公用方法对私有字段进行访问

  <img src="https://upload-images.jianshu.io/upload_images/25288552-0d78033e7b727cb4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="image.png" style="zoom: 50%;" />

  该办法有如下好处：

  * 使用者不可直接操作_age
  * 用方法返回_age值供读取
  * 用方法限制使用者的非法赋值

  有没有更好的办法？     C#给我们提供了一种更理想的方法，就是属性

* 属性

  通过属性让用户像访问公有成员字段一样来访问类的私有成员字段。属性机制有两个属性访问函数get和set：取值函数get()，用于获取字段的值；赋值函数set()，用于为字段赋值，使用value关键字获取用户输入。在面向对象设计中，主要使用属性描述对象的静态特征

  * 属性的声明

    属性将字段和访问字段的方法组合在一起。它提供灵活的机制来读取、编写或计算私有字段的值

    它的声明格式如下所示

    <img src="https://upload-images.jianshu.io/upload_images/25288552-02761837e9b936f2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240" alt="image.png" style="zoom:50%;" />

    定义属性的目的是便于一些私有字段的访问，因此属性的命名建议与字段相关联

    ![image.png](https://upload-images.jianshu.io/upload_images/25288552-edac437ec0129a9b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

    * 属性不表示存储位置，而是一个特殊的接口，用于对外交互类的静态信息

    * 对于字段的访问级别，属性提供了3种接口：

      * 只读（get）：只能读取字段的值
      * 只写（set）：只能为字段赋值
      * 读写（get和set）：能同时读取和赋值

      ![image.png](https://upload-images.jianshu.io/upload_images/25288552-6875f94f9571adbf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

  * 属性的作用

    ![image.png](https://upload-images.jianshu.io/upload_images/25288552-b1f8d8f9389a365b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 属性的使用

``` C#
//示例：字段与属性的使用示例
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class Student
	{
		private int nAge; // 私有域
		public int Age // 属性
		{
			get
			{
				return this.nAge;
			}
			set
			{
				if (value != this.nAge)
					this.nAge = value;
			}
		}
	}
	class Test
	{
		static void Main(string[] args)
		{
			Student s = new Student();
			s.Age = 20;
			Console.WriteLine(s.Age);
		}
	}
}

输出：
(base) PS D:\Porgram\C#Program> dotnet run
20
```

* 快速创建属性

  在VS中指针指向字段并点击鼠标右键，选择【快速操作和重构】

* 自动属性

  系统提供了自动生成属性set和get访问器代码块的机制。自动实现属性的一般形式：

  访问修饰符 类型 属性名 {get; set;}

  ``` C#
  public class Student
  {
  	public string Name { get; set; }
  }
  ```

  自动实现的属性必须同时声明get和set访问器。如果要创建只读的自动实现属性，则可声明private的set访问器

  ``` C#
  public class Student
  {
  	public string Name { get; private set; }
  }
  ```

  没有特定业务逻辑的属性都可以简写成自动属性

* 使用属性的好处

  * 封装类的内部数据，保护类中的字段
  * 属性可以设置为只读或只写，而字段却没有这样的功能（只可设置只读）
  * 可在访问器中对字段访问进行一些规则约束

* 属性的使用局限

  * 除了get、set访问器之外，属性不能包含其他并列的代码块
  * 除了set访问器内建的value参数，get、set访问器不能获取别的参数
  * 不能声明const属性
  * 不能将属性作为一个ref或out参数

## 常用的基础类

### .NET框架类库

.NET框架类库（FCL）提供了丰富的类和方法的集合，这些类被组织为命名空间，为从文件输入和输出、字符串操作、XML分析到Windows窗体空间的所有内容提供了各种有用的功能

![image.png](https://upload-images.jianshu.io/upload_images/25288552-23daccc56c221592.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

System命名空间包含了用于定义常用值和引用数据类型、事件和事件处理程序、接口、特性以及处理异常的基础类和基类，常用的类和结构如图所示

![image.png](https://upload-images.jianshu.io/upload_images/25288552-56549f9ac3d45739.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Math类

* Math类方法可以使程序完成某些常见的数据计算

* Math类方法中的参数可以是常量、变量或者表达式。例如，下面这个语句调用Math类中的Sqrt方法求表达式12 + 4 × 6的平方根：Math.Sqrt(12 + 4 *     6); 

* 下表总结了一些Math类的常用方法，Math类中也定义了两个常被使用的数学常量：Math.Pl和Math.E，它们分别代表了圆周率和自然对数底

  | **功能** |   **函数**   |      **C#**示例      |
  | :------: | :----------: | :------------------: |
  |   乘方   |  Math.Pow()  |   Math.Pow(2,  3);   |
  |   开方   | Math.Sqrt()  |    Math.Sqrt(16);    |
  | e的次方  |  Math.Exp()  |     Math.Exp(8);     |
  |  绝对值  |  Math.Abs()  |    Math.Abs(-3);     |
  |   对数   |  Math.Log()  |   Math.Log(8,  2);   |
  | 常用对数 | Math.log10() |   Math.Log10(100);   |
  | 正弦函数 |  Math.Sin()  | Math.Sin(Math.PI/3); |
  | 余弦函数 |  Math.Cos()  | Math.Cos(Math.PI/3); |
  | 正切函数 |  Math.Tan()  | Math.Tan(Math.PI/3); |

  圆周率与自然对数底的表示：

  | 数字含义 | 代码表示 |      近似值      |
  | :------: | :------: | :--------------: |
  |    π     | Math.PI  | 3.14159265358997 |
  |    e     |  Math.E  | 2.71828182845905 |

``` C#
//Math类应用示例
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class Circle
	{
		double r = 2; // 设置半径值为2
		public double getArea()
		{
			double s = Math.PI * r * r;
			return s;
		}
		static void Main(string[] args)
		{
			Circle c = new Circle();
			Console.WriteLine(c.getArea());
		}
	}
}

输出：
(base) PS D:\Porgram\C#Program> dotnet run
12.566370614359172
```

### Random类

在C#中，System.Random类用于产生随机数

* Random.Next()方法用于返回非负随机数
* Random.Next(int)方法用于返回一个小于所指定最大值的非负随机数
* Random.Next(int, int)方法用于返回一个指定范围内的随机数
* Random.NextDouble()方法用于返回一个介于0.0和1.0之间的随机数

示例1：使用Random生成四位数字的验证码

![image.png](https://upload-images.jianshu.io/upload_images/25288552-3e92a7baa1a854e3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

示例2：使用Random生成四个字母的验证码

![image.png](https://upload-images.jianshu.io/upload_images/25288552-b25e37b54e133813.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### DataTime类和TimeSpan类

* DataTime类可以表示范围在0001年1月1日午夜12:00:00到9999年12月31日晚上11:59:59之间的日期和时间，最小时间单位等于100ns
* TimeSpan类可以表示一个时间间隔。其范围可以在Int64.MinValue和Int64.MaxValue之间

示例：今天距离四六级考试还有多少天？

![image.png](https://upload-images.jianshu.io/upload_images/25288552-5522cb7bd69310f3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### Convert类

Convert（转换）类提供了一个基本数据类型转换为另一个基本数据类型的一系列静态方法。其中最常用是由字符串类型转换为相应其他基本数据类型的静态方法

* 类型如果相兼容的两个变量，可以使用自动类型转换或者强制类型转换
* 如果两个变量不兼容，比如说String和int或者String和Double类型，则使用Convert类进行转换

1. 使用Parse()转换

   字符串向数值型转换

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-6930480d6b284e2c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2. 使用Convert类转换

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-81bcb7df08d74c10.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. Parse()与Convert类

   ![image.png](https://upload-images.jianshu.io/upload_images/25288552-4fe93a31f0696694.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4. Convert类的常用方法

   |         方法         |            说明            |
   | :------------------: | :------------------------: |
   |  Convert.ToInt32()   |      转换为整型(int)       |
   |   Convert.ToChar()   |     转换为字符型(char)     |
   |  Convert.ToString()  |   转换为字符串型(string)   |
   | Convert.ToDateTime() |   转换为日期型(datetime)   |
   |  Convert.ToDouble()  | 转换为双精度浮点型(double) |
   |  Convert.ToSingle()  | 转换为单精度浮点型(float)  |

```C#
// 示例1：使用Convert类转换数据类型
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace C_Program
{
	class Circle
	{
		double s; // 圆面积
		public double getArea(double r)
		{
			s = Math.PI * r * r;
			return s;
		}
	}
	class Program
	{
		static void Main(string[] args)
		{
			Circle c = new Circle();
			Console.WriteLine("请输入半径的值：");
			double radius = Convert.ToDouble(Console.ReadLine());
			Console.WriteLine("圆的面积是：{0}", c.getArea(radius));
		}
	}
}

输出：
请输入半径的值：
2
圆的面积是：12.566370614359172
```

示例2：在窗体程序中使用Convert类转换数据类型

![image.png](https://upload-images.jianshu.io/upload_images/25288552-3c6b7c1d756b035d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 委托

