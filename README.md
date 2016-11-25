# WebIcons

[Link to NuGet package](https://www.nuget.org/packages/WebIcons)

## What?

Intellisense in Visual Studio for the latest web fonts:

+ Font Awesome
+ Glyphicons
+ Material Design

## Why?

So you can do this:

![why](http://i.imgur.com/dwGOMZ0.png)

## How?
Package Manager Console:

```
Install-Package WebIcons
```

In .cshtml file:

```cshtml
<i class="@WebIcons.FontAwesome.Hotel"></i>
```

In .cs file:

```csharp
using WebIcons;

var iconTag = $"<i class=\"{ WebIcons.FontAwesome.Hotel }\"></i>";
```
