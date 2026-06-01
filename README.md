# FastInject 🚀

[![NuGet version](https://img.shields.io/nuget/v/FastInject.Core.svg)](https://www.nuget.org/packages/FastInject.Core/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**FastInject** is a zero-dependency, compile-time Dependency Injection source generator for .NET. It eliminates the need for reflection-based assembly scanning or messy `Program.cs` files by generating your DI container registrations at compile time.

## 🌟 Why FastInject?
- **Zero Startup Cost:** Uses C# Source Generators. No reflection means faster application startup.
- **Zero Dependencies:** Does not add any external DLLs to your project. Attributes are injected directly into your source code.
- **Clean Architecture:** Keep your `Program.cs` perfectly clean.

## 📦 Installation

Install the package via NuGet Package Manager:

```bash
dotnet add package FastInject.Core