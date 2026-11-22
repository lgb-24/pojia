# 破甲 POJIA · WorkBuddy 执行内核

> 四层注入，全程可还原。把 WorkBuddy（腾讯 · Electron 版）改造成「破甲」执行内核。

这是 `lgb-24/pojia` 的 GitHub Pages 站点源码，用于展示并分发 **WorkBuddy 破甲插件 v1.2**。

## 站点内容

- 单页落地页：`index.html`（内联 CSS/JS，零依赖、纯静态）
- 插件分发包：`downloads/WorkBuddy破甲插件-v1.2.zip`（1.57 MB）
  - SHA-256：`107DFBED36ECF054B1F1472642D88C49F6AD6D400215160FEFE211C15EB9A592`

## 本地预览

```bash
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 发布

推送到 `main` 分支后，在仓库 Settings → Pages 中将 Source 设为 `Deploy from a branch` / `main` / `/ (root)` 即自动发布。

访问地址：https://lgb-24.github.io/pojia/
