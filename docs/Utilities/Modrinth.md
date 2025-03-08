---
title: "Modrinth 支持"
---

# Modrinth 支持

Modrinth 支持

命名空间 `StarLight_Core.Utilities`

## 方法参考

### `Modrinth.example` 示例

```csharp
public static async Task<IEnumerable<ModrinthInfo>?> GetRandomMod(int count)
```

|             返回值              |        描述         |
|:----------------------------:|:-----------------:|
|  IEnumerable<ModrinthInfo>?  |  [参数详解](./#参数详解)  |



## 参数详解

### 详细 `ModrinthInfo` 定义

|     参数      |         类型          |   描述   |
|:-----------:|:-------------------:|:------:|
|     Id      |       string        |  项目Id  |
|    Slug     |       string        | 项目Slug |
|    Title    |       string        |  项目标题  |
| description |       string        |  项目描述  |
| client_side |   ClientSideType    | 客户端可用性 |
| ServerSide  |   ServerSideType    | 服务端可用性 |
|   license   |       License       |  许可证   |
|   Authors   | IEnumerable<string> |  项目作者  |
| DateCreated |   DateTimeOffset    | 项目创建日期 |
|   Authors   | IEnumerable<string> |  项目作者  |
|  Downloads  |         int         | 项目下载数  |

### 详细 `License` 定义
|  参数  |         类型          |  描述  |
|:----:|:-------------------:|:----:|
|  Id  |       string        | TODO |
| Name |       string        | TODO |


## 控制台示例

>[!TIP]
>控制台示例只是为了更加方便的了解如何使用, 不建议直接复制

```csharp
var ModList = GetRandomMod(50);
```
