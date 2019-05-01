.Net

C# code can'st be given to the computer itself, it need's additonal software that know how to translate the c# code to the cpu/device intructions. This is true for any high level language. This software is .NET.


.NET separates in two pieces.

## CLR (Common Language Runtime)

.NET it's a **Runtime**.
    * It's provide space for our program to run in C#    
    * Manage memory for that program
    * Send intructions for the procesor of the device
    * It provides support not only for C# language (Visal Basic, F#, etc)

## FCL (Framework Class Library)

.NET Provides a **Library** of code that have been tested by Microsoft developers and non M-developers. You can use the code of this library to perform common activities (Read files, Network, etc)

The .NET SDK includes the CLR and the FCL.

## The CLI (Command Line Interface)

After installed .NET, there should be a program called **dotnet** added to the system variable path, it must be available from anywhere in the command prompt.

When executed `dotnet` , it tell us that parameters must be added.

`dotnet --info` Give us information about the SDK installed in the device. Plus info about the enviroment (OS) running. Also give us the version and path of all Runtimes and SDK Installed, and the one is running the command.

`dotnet -h` Give us info about all parameters available, included the ones from the SDK.

**Project**: It a collection of source code files that you need to put toguether into an Application or Library.

`dotnet new` Creates a new .NET project. It needs a parameter that specify a template.

**Template**: Give us the basic structure of a .NET project for an Application.

