# Understanding the Code:

Using Visual Studio, if we are creating a console application and checking the checkbox stating "_Do not use the top-level Statement_, then automatically we are getting four sections which are shown in the below image.
![understading-csharp-code.png](understading-csharp-code.png)

## Let’s understand each of these sections in detail.

#### Importing Namespace Section:
This section contains importing statements that are used to import the **BCL (Base Class Libraries)** as well as user-defined namespaces if required. This is similar to the included statements in the C programming language. Suppose you want to use some classes and interfaces in your code, then you have to include the namespace(s) from where these classes and interfaces are defined. For example, if you are going to use the Console class in your code, then you have to include the System namespace as the Console class belongs to the System namespace.
_Syntax: using NamespaceName;_
```C#
using System;
```

If the required namespace is a member of another namespace, we have to specify the parent and child namespaces separated by a dot as follows:
``` C#
using System.Data;
using System.IO;
```

_Note: A namespace is a container that contains a group of related classes and interfaces, as well as, a namespace can also contain other namespaces._

#### Namespace Declaration Section:
Here a user-defined namespace is declared. In .NET applications, all classes and interfaces or any type related to the project should be declared inside some namespace. Generally, we put all the related classes under one namespace and in a project, we can create multiple namespaces.
Syntax: namespace NamespaceName {}
``` C#
namespace MyFirstProject {}
```

Generally, the _namespace_ name will be the same as the project name but it is not mandatory, you can give any user-defined name to the namespace.

### Class Declaration Section:
For every Desktop Application in .NET, we need a start-up class file. For example, for every .NET Desktop Application like Console and Windows, there should be a Start-Up class that should have the Main method from where the program execution is going to start. When we create a Console Application using Visual Studio, by default, Visual Studio will Create the Start-Up class file with the name Program.cs which will have a class with the name Program that contains the Main method. A start-up class is nothing but a class that contains a Main() method from which the program execution is going to start.

Syntax:
class ClassName
{
}
```C#
class Program
{
}
```


_Note: You can change this default behavior. You can create your own class and you can also make that class as the Start-Up Class by including the Main method. In our upcoming articles, we will discuss this in detail._
Main() Method Section:
The main() method is the entry point or starting point of the application to start its execution. When the application starts executing, the main method will be the first block of the application to be executed. The Main method contains the main logic of the application.

#### What is using?
Using is a keyword. Using this keyword, we can refer to **.NET BCL in** C# Applications i.e. including the BCL namespaces as well as we can also include user-defined namespaces that we will discuss as we progress in this course. 
Apart from importing the namespace, other uses of using statements are there, which we will also discuss as progress in this course. For now, it is enough.

_Note: In .NET the base class libraries are divided into a collection of namespaces. Each namespace contains a set of predefined classes and sub-namespaces. The namespace contains another namespace called sub-namespaces._

#### Advantages of using the .NET framework from the C# point of view.
1. It provides GUI features. Earlier programming languages like C and C++ do not support GUI features but C#.NET will provide complete GUI features. All GUI features are getting from the framework.
2. We can connect with any database and perform the operations. Using ADO.NET and Entity Framework technologies, we can perform the DB operations with any Database. ADO.NET and Entity Framework are also a part of the .NET Framework.
3. The Framework also helps us to develop WEB Based applications. Using ASP.NET technology we can develop WEB Based Applications. ASP.NET itself alone cannot develop Web Applications; it requires language support. So, here we can use C# as the programming language. ASP.NET is also a part of the framework.

_In the next article, I am going to discuss the Console Class Methods and Properties in detail. Here, in this article, I try to explain the Basic Structure of the C# Program step by step with one example. I hope you enjoy this article._ 