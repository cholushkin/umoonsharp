http://www.moonsharp.org   

A complete Lua solution written entirely in C# for Unity. 

Features (MoonSharp original):
* 99% compatible with Lua 5.2 (with the only unsupported feature being weak tables support) 
* Support for metalua style anonymous functions (lambda-style)
* Easy to use API
* **Debugger** support for Visual Studio Code (PCL targets not supported)
* Remote debugger accessible with a web browser and Flash (PCL targets not supported)
* Runs on .NET 3.5, .NET 4.x, .NET Core, Mono, Xamarin and Unity3D
* Runs on Ahead-of-time platforms like iOS
* Runs on IL2CPP converted code
* Runs on platforms requiring a .NET 4.x portable class library (e.g. Windows Phone)
* No external dependencies, implemented in as few targets as possible
* Easy and performant interop with CLR objects, with runtime code generation where supported
* Interop with methods, extension methods, overloads, fields, properties and indexers supported
* Support for the complete Lua standard library with very few exceptions (mostly located on the 'debug' module) and a few extensions (in the string library, mostly)
* Async methods for .NET 4.x targets
* Supports dumping/loading bytecode for obfuscation and quicker parsing at runtime
* An embedded JSON parser (with no dependencies) to convert between JSON and Lua tables
* Easy opt-out of Lua standard library modules to sandbox what scripts can access
* Easy to use error handling (script errors are exceptions)
* Support for coroutines, including invocation of coroutines as C# iterators 
* REPL interpreter, plus facilities to easily implement your own REPL in few lines of code
* Complete XML help, and walkthroughs on http://www.moonsharp.org

Features for Unity and Qonsole support:
