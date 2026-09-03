# 语层翻译 LexiLayer Translator · 使用文档

本仓库只包含语层翻译扩展的官方使用文档站点，通过 GitHub Actions 自动部署到 GitHub Pages：

**线上地址：<https://vastnext.github.io/lexilayer-docs/>**

## 仓库内容

- `index.html`：使用文档单页（中文）
- `assets/`：产品截图与图标
- `.github/workflows/pages.yml`：Pages 部署工作流（push 到 `main` 触发）

本仓库不含扩展源码。扩展源码与文档站点源文件维护在主项目仓库 `VastNext/LexiLayer-Translator` 的 `site/` 目录。

## 更新流程

1. 在主项目仓库中修改 `site/index.html` 或 `site/assets/`。
2. 将 `site/` 下的内容同步覆盖到本仓库根目录（保持 `.github/` 不变）。
3. 推送到本仓库 `main`，部署工作流会自动发布新版本。
