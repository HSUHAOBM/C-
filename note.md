https://learn.microsoft.com/zh-tw/aspnet/core/?view=aspnetcore-7.0

dotnet --help
dotnet -h

# 快速鍵立範本
dotnet new mvc --output name
# 取得範本名稱
dotnet new --list
dotnet new -l
Console Application	console	[C#], F#, VB	Common/Console
Class Library	classlib	[C#], F#, VB	Common/Library
Unit Test Project	mstest	[C#], F#, VB	Test/MSTest
ASP.NET Core Web App (Model-View-Controller)	mvc	[C#], F#	Web/MVC
ASP.NET Core Web API	webapi	[C#], F#	Web/WebAPI
Solution File	sln	Solution

# 建置
dotnet build
dotnet build ./file/xxxx.csproj