

## 1. 什么是 GitHub Package Registry ？

GitHub 2019年5月10日正式推出一项名为 GitHub Package Registry (以下简称GPR) 的新产品，它提供了软件包管理服务，开发者通过它可发布公共或私有软件包。支持大众熟知的包管理工具，目前支持 JavaScript (npm)、Java (Maven)、Ruby(RubyGems)、.net (NuGet) 和 Docker images。

## 2. 为什么使用 GPR ？
* 开源项目完全免费使用，私有项目可参见：[私有项目收费标准]()
* 目前体验来看，相比较 jCenter ，包的发布和管理更加稳定和方便
* Github 出品，社区资源好，交互体验好

当然目前 GPR 在部分功能上还有待完善，但是拥有更好的体验只是时间问题。

## 3. 支持的客户端和格式

|<center>包客户端</center>|<center>语言</center>|<center>包格式</center>|<center>描述</center>|
|:-|:-|:-|:-|
|npm|JavaScript|package.json|Node package manager|
|gem|Ruby|Gemfile|RubyGems package manager|
|mvn|Java|pom.xml|Apache Maven project management and comprehension tool|
|gradle|Java|build.gradle 或 build.gradle.kts|Gradle build automation tool for Java|
|docker|N/A|Dockerfile|Docker container management platform|
|nuget|.NET|nupkg|NuGet package management for .NET|
