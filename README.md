# Modern Web Guidance CN

**用中文描述需求，找到现代 Web 平台的对应指南。**

基于 [GoogleChrome/modern-web-guidance](https://github.com/GoogleChrome/modern-web-guidance) 的小幅适配，独立维护、非官方。

## 保留什么

保留上游的检索、取回指南、核对实现和说明采用依据的完整流程，以及浏览器兼容性与回退要求。附带 **210 份原始指南快照**，覆盖 HTML、CSS、性能、可访问性和浏览器能力。

中文补充负责把业务说法转成上游要求的简短英文检索词，区分检索词与指南 ID，并用中文解释适用条件。核心指南保留原文技术内容（清理行尾空格与文件尾空行），不为了中文化改写技术规则。

## 安装与调用

```bash
npx skills add batespaige357-tech/modern-web-guidance-cn --skill modern-web-guidance-cn
```

对助手说：“用 modern-web-guidance-cn 查这个中文需求对应的浏览器指南，再按项目支持范围实现。”Codex 可使用 `$modern-web-guidance-cn`。手动安装时复制 `skills/modern-web-guidance-cn` 完整目录。

动态检索仍依赖上游 `modern-web-guidance` CLI、Node.js 和网络；本仓库没有同名 CLI，也没有捆绑其实现。指南快照可本地查阅，但不保证是最新浏览器支持情况。宽范围现代化扫描只适用于用户明确要求的任务。

## 来源与检查

Apache-2.0，保留完整许可证，并在 [NOTICE](NOTICE) 与 [CHANGES.md](CHANGES.md) 标明来源和改动。不使用上游品牌图片。

已检查正文完整保留、210 份指南快照、UTF-8、本地引用及技能格式。未执行下载的工具、联网 CLI 检索、浏览器兼容测试或助手行为评估；未运行前端编译。不含示例网页、效果截图或前后对比。
