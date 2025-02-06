# dmall-port

## 项目前言
在C++与其他语言的互操作领域，我们长期面临着工具链复杂、配置繁琐的困境。

dmall-port项目应运而生，旨在为C++开发者提供一套行为统一简洁、高效的语言互操作解决方案。

## 项目介绍
在编程的世界里，C++如同伟大航路，强大而充满挑战。而其他语言则如同分散的四个大陆，各具特色却难以互通。

dmall-port项目，正如海贼王中的All Blue，是我们追寻的梦想之地。我们致力于在C++与其他语言之间架起桥梁，让开发者能够自由穿梭于不同的编程世界。

就像路飞寻找One Piece一样，我们相信：
- Python的优雅如同东海，温柔而富有生机
- Lua的轻巧如同南海，灵活而充满可能
- JavaScript的活力如同西海，无处不在
- Go的高效如同北海，冷峻而强大
- C#的全面如同红土大陆，坚实而可靠

让我们一起开启这段伟大的航程，打破语言的壁垒，创造属于所有开发者的All Blue！

## 移植状态

| 语言       | 状态     | 进度  | 备注          |
|------------|----------|-------|---------------|
| Python     | 已实现   | 100%    |  pybind11的优雅让整个系统非常完美 堪称典范             |
| Lua        | 已实现   | 100%    |  sol2的优雅让整个系统非常完美 堪称典范              |
| JavaScript | 已实现   | 100%    |     genepi API有点粗糙 没有找到更好的替代品          |
| JavaScript | 已实现   | 100%    |     使用emsdk实现，目前看好像还行          |
| Go         | 未实现   | 20%    | 仅完成demo |
| C#         | 已实现   | 50%    | 完成demo, 流程跑通, 代码生成器还未实现 |

## 移植计划

### Python
- 使用pybind11 完成自动化bind
- 项目名字 dmgen4pybind

### Lua
- 使用sol2 完成自动化bind
- 项目名字 dmgen4cpp [未改名]

### JavaScript
- 使用genepi 完成自动化bind
- 项目名字 dmgen4node

### JavaScript
- 使用emsdk实现 完成自动化bind
- 项目名字 dmgen4wasm

### Go
- 使用swig 完成自动化bind
- 项目名字 dmgodemo

### C#
- 使用CppCsharp完成bind
- 项目名字 dmcsharp-dmprojectinfo

## 开发指南
1. 每个语言的移植将创建独立分支
2. 移植完成后将合并到主分支
3. 每个语言移植需包含单元测试
4. 保持API接口一致性

## 贡献指南
欢迎提交Pull Request，请遵循以下规范：
- 每个语言移植创建独立目录
- 保持代码风格一致
- 提供完整的文档和测试用例

## 总结
pybind11, sol2 实现堪称完美, 对比其他语言 貌似没有这么好的支持库.
