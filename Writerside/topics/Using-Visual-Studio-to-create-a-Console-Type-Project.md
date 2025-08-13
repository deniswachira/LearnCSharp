# Using Visual Studio to create a Console-Type Project

Now, we are going to use Visual Studio to create a Console-Type Project. Then we are going to use the console application to display the message “Welcome to C#.NET”. 
Then, we will also see how to build and run the Console Application using Visual Studio GUI.
### Step 1
First, open Visual Studio 2022 (the latest version at this point in time) and then click on the Create a New Project option as shown in the below image.
![creating-the-console-application.png](creating-the-console-application.png)

### Step 2
The next step is to choose the project type as a Console Application. Type Console in the search bar and you will see different types of console applications 
using C#, VB, and F# Programming Languages and using both .NET Framework and .NET Core / .NET. Here, I am selecting Console App using C# Language 
and then clicking on the Next button as shown in the below image.
![2.png](creating-the-console-application-2.png)

### Step 3
The next step is to configure the new project. Here, you need to provide the project name and solution name. You can also give the same name to both project and 
solution but it is not mandatory. Here, I am providing the name MyFirstProject to both project and solution. You need to provide the location where you need to 
create the project. Here, you also need to provide the .NET Framework version that you want to use in this application. The latest version of the .NET Framework is 
4.8. So, I am selecting .NET Framework 9.0 and then clicking on the Create button as shown in the below image.
![3.png](creating-the-console-application-3.png)

Once you click on the Create button, visual studio will create the Console Application with the following structure.
![creating-the-console-application-4.png](creating-the-console-application-4.png)

A project called MyFirstProject will be created in Visual Studio. This project will contain all the necessary required files (Properties, References, App.Config files)
to run the Console application. The Main program called Program.cs is the default code file that is created when a new console application is created in Visual Studio
it contains the Main method by default and from that Main method our application is going to start its execution, but if you want you can also change this default 
behavior. So, if you look at the Program.cs class file, then you will see the following code.
![creating-the-console-applocation-5.png](creating-the-console-applocation-5.png)

### Step 4
Now let’s write our code which will be used to display the message “Welcome to C#, My First Console APP” in the console window. To do so, modify the Main method of the Program class as shown in the below code.
![creating-the-console-application-6.png](creating-the-console-application-6.png)

### Step 5
The next step is to run the .NET Application. To run any program in Visual Studio, you just need to click on the Start button or you can press **CTRL+F5** as shown in the below image.
![creating-the-console-application-7.png](creating-the-console-application-7.png)
Once you click on the Start button, you should get the following console window showing the message.
![output.png](output.png)

_🥳🥳🥳Congratulation you have written your first C# Console Application_