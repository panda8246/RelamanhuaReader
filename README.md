# RelaManga Reader（双页/右到左/全屏覆盖）

适用于热辣漫画（`relamanhua.org` / `www.relamanhua.org`）章节页的 **PC 端双页阅读器**：横屏双页并排、右到左翻页、第 1 页单独显示。

## 使用方法（最简）

1. 安装浏览器用户脚本管理器：Tampermonkey（或 Violentmonkey）。
2. 新建脚本，将 `git/src/RelaMangaReader.js` 的内容 **整段复制粘贴** 进去并保存。
3. 打开任意章节页（URL 形如 `https://www.relamanhua.org/comic/*/chapter/*`）。
4. 按 `R` 进入/退出全屏阅读器。

## 快捷键（右到左）

- `R`：进入/退出阅读器
- `Esc`：退出阅读器
- `←`：下一组（Next spread）
- `→`：上一组（Prev spread）
- 点击屏幕：左半屏=下一，右半屏=上一
- `G`：切换配对模式（首单/双起）

## 说明

- 第 1 页默认单独一屏；从第 2 页起两页一组（如 `2-3`、`4-5`）。
- 脚本仅在章节页生效（见脚本头部 `@match`）。
