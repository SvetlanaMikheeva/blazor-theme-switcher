<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/227836631/22.1.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T845557)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# How to implement a Theme Switcher in Blazor applications

This example demonstrates how to create a Theme Switcher as in [DevExpress Blazor Demos](https://demos.devexpress.com/blazor/) and apply the selected theme to an application at runtime. The example contains solutions both for Blazor Server and Blazor WebAssembly. Note that these solutions target .NET 6.0.

![Blazor - Theme Switcher](images/blazor-theme-switcher.png)

This Theme Switcher includes the standard Bootstrap theme, [4 DevExpress Bootstrap themes](https://github.com/DevExpress/bootstrap-themes), and [21 Bootstwatch themes](https://bootswatch.com/). 

Refer to the [Themes](https://docs.devexpress.com/Blazor/401523/common-concepts/themes#implement-a-theme-switcher) documentation topic for more information.

<!-- default file list -->
## Files to look at

**Blazor Server**
* [ThemeSwitcherSideView.razor](./CS/BlazorServer/switcher/switcher/Shared/ThemeSwitcherSideView.razor)
* [ThemeItem.cs](./CS/BlazorServer/switcher/switcher/Shared/ThemeItem.cs)
* [MainLayout.razor](./CS/BlazorServer/switcher/switcher/Shared/MainLayout.razor)
* [Index.razor](./CS/BlazorServer/switcher/switcher/Pages/Index.razor)
* [switcher-resources](./CS/BlazorServer/switcher/switcher/wwwroot/css/switcher-resources) (folder)

**Blazor WebAssembly**
* [ThemeSwitcherSideView.razor](./CS/BlazorWebAssembly/switcher/switcher/Shared/ThemeSwitcherSideView.razor)
* [ThemeItem.cs](./CS/BlazorWebAssembly/switcher/switcher/Shared/ThemeItem.cs)
* [MainLayout.razor](./CS/BlazorWebAssembly/switcher/switcher/Shared/MainLayout.razor) 
* [Index.razor](./CS/BlazorWebAssembly/switcher/switcher/Pages/Index.razor)  
* [switcher-resources](./CS/BlazorWebAssembly/switcher/switcher/wwwroot/css/switcher-resources) (folder)
<!-- default file list -->

## Documentation

[Themes](https://docs.devexpress.com/Blazor/401523/common-concepts/themes)
