---
ms.openlocfilehash: 3f3f60f9752b9bd36d76387102c202d88b39c3ca
ms.sourcegitcommit: 8699383914c24a0df033393f55db3369db728a7b
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/15/2019
ms.locfileid: "65672225"
---
| .NET Standard              | [1.0]  | [1.1]  | [1.2] | [1.3] | [1.4] | [1.5]              | [1.6]              | [2.0]               |
|----------------------------|--------|--------|-------|-------|-------|--------------------|--------------------|---------------------|
| .NET Core                  | 1.0    | 1.0    | 1.0   | 1.0   | 1.0   | 1.0                | 1.0                | 2.0                 |
| .NET Framework <sup>1</sup>| 4.5    | 4.5    | 4.5.1 | 4.6   | 4.6.1 | 4.6.1 <sup>2</sup> | 4.6.1 <sup>2</sup> | 4.6.1 <sup>2</sup>  |
| Mono                       | 4.6    | 4.6    | 4.6   | 4.6   | 4.6   | 4.6                | 4.6                | 5.4                 |
| Xamarin.iOS                | 10.0   | 10.0   | 10.0  | 10.0  | 10.0  | 10.0               | 10.0               | 10.14               |
| Xamarin.Mac                | 3.0    | 3.0    | 3.0   | 3.0   | 3.0   | 3.0                | 3.0                | 3.8                 |
| Xamarin.Android            | 7.0    | 7.0    | 7.0   | 7.0   | 7.0   | 7.0                | 7.0                | 8.0                 |
| 通用 Windows 平台 | 10.0   | 10.0   | 10.0  | 10.0  | 10.0  | 10.0.16299         | 10.0.16299         | 10.0.16299          |
| Unity                      | 2018.1 | 2018.1 | 2018.1| 2018.1| 2018.1| 2018.1             |  2018.1            | 2018.1              |

<sup>1 针对 .NET framework 列出的版本适用于 .NET Core 2.0 SDK 和更高版本的工具。旧版本对 .NET Standard 1.5 及更高版本使用了不同映射。如果无法升级到 Visual Studio 2017，可[下载适用于 Visual Studio 2015 的 .NET Core 工具](https://github.com/dotnet/core/blob/master/release-notes/download-archive.md)。</sup>

<sup>2 此处所列的版本表示 NuGet 用于确定给定 .NET Standard 库是否适用的规则。虽然 NuGet 将 .NET Framework 4.6.1 视为支持 .NET Standard 1.5 到 2.0，但使用为从 .NET Framework 4.6.1 项目构建的 .NET Standard 库存在一系列问题。对于需要使用此类库的 .NET Framework 项目，建议将项目升级到面向 .NET Framework 4.7.2 或更高版本。</sup>

- 列表示 .NET Standard 版本。 每个标题单元格都是一个文档链接，其中介绍了相应版本的 .NET Standard 中新增了哪些 API。
- 行表示不同的 .NET 实现。
- 各单元格中的版本号指示要定向到此 .NET Standard 版本所需的最低实现版本。
- 有关交互式表的信息，请参阅 [.NET Standard 版本](https://dotnet.microsoft.com/platform/dotnet-standard#versions)。

[1.0]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.0.md
[1.1]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.1.md
[1.2]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.2.md
[1.3]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.3.md
[1.4]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.4.md
[1.5]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.5.md
[1.6]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard1.6.md
[2.0]: https://github.com/dotnet/standard/blob/master/docs/versions/netstandard2.0.md
