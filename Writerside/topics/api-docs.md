# C# Fundamentals


## Hello world

```C#
// This line prints "Hello, World"
Console.WriteLine("Hello, World");
```

## _Explanation_ {id="explanation_1"}
The line starting with // is a single line comment. C# single line comments start with // and continue to 
the end of the current line. C# also supports multi-line comments. Multi-line comments start with /* and end with */. 
The WriteLine method of the Console class, which is in the System namespace, produces the output of the program.

This alternative format is still valid and contains many of the basic concepts in all C# programs. Many existing C# samples use the following equivalent format:
```C#
using System;
namespace TourOfCsharp;

class Program
{
    static void Main()
    {
        // This line prints "Hello, World" 
        Console.WriteLine("Hello, World");
    }
}
```
## _Explanation_
The preceding "Hello, World" program starts with a using directive that references the System namespace. Namespaces provide 
a hierarchical means of organizing C# programs and libraries. Namespaces contain types and other namespaces—for example, the 
System namespace contains many types, such as the Console class referenced in the program, and many other namespaces, such as 
IO and Collections. A using directive that references a given namespace enables unqualified use of the types that are members 
of that namespace. Because of the using directive, the program can use Console.WriteLine as shorthand for System.Console.WriteLine. In the 
earlier example, that namespace was implicitly included.

### File based programs
C# is a compiled language. In most C# programs, you use the `dotnet build` command to compile a group of source files into a binary package. Then, you
use the `dotnet run` command to run the program. (You can simplify this process because dotnet run compiles the program before running it if necessary.) These
tools support a rich language of configuration options and command-line switches. The dotnet command line interface (CLI), which is included in the .NET SDK, provides many 
tools to generate and modify C# files.

### Summary: Key Features of C#
C# is **beginner-friendly** yet powerful enough for advanced development. It allows developers to be productive quickly while offering deeper, specialized capabilities as needed.
C# applications benefit from the .NET runtime's automatic memory management and a rich set of runtime libraries. These include cross-platform utilities (e.g. file system, collections, math) and workload-specific tools (e.g. ASP.NET Core for web, .NET MAUI for UI). Additionally, the NuGet ecosystem provides a vast collection of open-source packages to extend functionality.

C# is a strongly typed language, meaning every variable has a type known at compile-time. This helps catch errors early during development. It includes built-in value types (int, double, char) and reference types (string, arrays), and also allows you to create custom struct, class, record, interface, and generic types.

Behavior is defined through methods, which can be overloaded and may return values. Properties, events, and object-oriented features like inheritance and polymorphism are supported.
