Note that non-web projects (Console, Wpf, Winform) don't have ASP.NET Core as a default installed package, so they don't use Middleware.  .NET's Middleware is specifically for handling the HTTP request/response pipeline.  Different file structures are mapped automagically by ASP.NET Core using [MVC or RazorPages Filter Pipeline](https://learn.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-8.0#middleware-order).

This article has a few nice graphics:
https://www.tutorialsteacher.com/core/aspnet-core-middleware

Microsoft docs:
https://learn.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-8.0

JwtBearerEvents class:
https://learn.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.authentication.jwtbearer.jwtbearerevents?view=aspnetcore-8.0
