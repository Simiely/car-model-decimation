# CHANGELOG.md · 版本记录

> 项目无正式版本号，按提交里程碑记录。

## 里程碑

- **接入文档检查（2026-11-17）**：接入 knowledge-base 的**单项目规范**（spec 2.1.3 / repo-kit 2.7.2，profile `link-only`）；新增 `schema/taxonomy.json`、`tools/repo-kit/`、`tools/update-repo-kit.ps1`、`schema/kit.lock.json` 与 CI；检查范围只含链接与入口（link-only）：**不要求 frontmatter**——两个站走 GitHub Pages + Jekyll，带 frontmatter 的 `.md` 会被渲染成额外页面；验收：`REPO CHECK: PASS`（ERROR=0）、`KIT LOCK: PASS (v2.7.2, spec=2.1.3)`；本次不改落地页与 `车模减面的思考.md`，只加机器层
- **交互式文档完成**：index.html（单文件、内联 CSS/JS、零依赖）——工作流卡片展开、打比方折叠块、文献 [n] 浮层、效率对比切换
- **方法论文档**：车模减面的思考.md（逐条技术论证 + 参考文献 [1]~[10]）
- **技术核查**：DEV_README 记录 9 条核查修正（QEM 归属/Shrinkwrap 机制/Catmull-Clark 三类点/法线烘焙 UV/范围限定/面数预算/弱包裹/标注审计/部署工程）
- **部署**：GitHub Pages 上线（simiely.github.io/car-model-decimation）

## 备注

- 无版本 tag / Release；仓库含 260710Fianl 空占位文件（无内容）
