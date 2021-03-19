# .Net Core Koans

The .NET Core Koans walk you along the path to enlightenment in order to learn C# on .NET Core. The goal is to learn C# syntax, structure and some common functions and libraries available on the .NET Core platform. .NET Core is a cross platform environment that runs happily on Windows, OS X and Linux. It is super simple to get started learning.

### The Structure

The koans are broken out into areas by file, arrays are covered in AboutArrays.cs, lambdas are introduced in AboutLambdas.cs, etc. They are presented in order in the PathToEnlightenment.cs file.

Each koan builds up your knowledge of C# and builds upon itself. It will stop at the first place you need to correct.

Some koans simply need to have the correct answer substituted for an incorrect one. Some, however, require you to supply your own answer. If you see the object FILL_ME_IN listed, it is a hint to you to supply your own code in order to make it work correctly.

### Getting Started

1. Install [.NET Core SDK 2.1](https://www.microsoft.com/net/core).
2. Install [Visual Studio Code](https://code.visualstudio.com/), the [Insiders Edition](https://code.visualstudio.com/insiders) is highly recommended.
3. Clone the repository: `git clone https://github.com/NotMyself/DotNetCoreKoans.git`.
4. Change directory into the cloned repository `cd DotNetCoreKoans`.
5. Restore packages: `dotnet restore`.
6. Open the project in VSCode `code-insiders .` or `code .` depending on what version you chose to install.
7. Run the koans in watch mode: `dotnet watch --quiet run`.
   - **Note:** The `--quiet` flag is used here to suppress mesages from the watch framework.
8. Follow along with the instructions printed to your console. Each time you save a \*.cs file, the project will be built and run again for you automatically.

### About Koans

This project is based on the work of [Cory Foy](https://github.com/CoryFoy) and his original multi-language project [DotNetKoans](https://github.com/CoryFoy/DotNetKoans). If you are interested in learning VB.NET or the Full .NET Framework (windows only), please look at his fine work.
