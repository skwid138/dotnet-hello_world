## Getting Started
- From terminal run ```brew update```
- Next run ```brew install openssl```
- Then create the following directory ```mkdir -p /usr/local/lib```
- After that create this link ```ln -s /usr/local/openssl/lib/libcrypto.1.0.0.dylib /usr/local/lib/```
- Finally create this link ```ln -s /usr/local/openssl/lib/libssl.1.0.0.dylib /usr/local/lib/```
- Navigate to parent directory in terminal that you want your porject to live in and run <br/> ```dotnet new console -o [appName]```
- Move into the newly created direcotry ```cd [appName]```
- Running ```dotnet restore``` will install the projects dependencies
- Running ```dotnet run``` will run your application

### resources
- [Get started with .NET in 10 minutes](https://www.microsoft.com/net/learn/get-started/macos)
- [Great Video Tutorial](https://channel9.msdn.com/Blogs/dotnet/Get-started-VSCode-NET-Core-Mac)