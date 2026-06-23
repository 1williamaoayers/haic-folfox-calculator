# HAIC-FOLFOX

HAIC-FOLFOX 配药与排程单页计算器。

## 使用方式

直接打开 `HAIC-FOLFOX-方案1-计算器.html` 即可使用。

页面根据身高、体重和方案参数计算体表面积，并生成简洁的自动排程配药单，包括：

- 每组配药内容
- 每组用时
- 泵速
- 当前浓度
- 备药支数

## 文件

- `HAIC-FOLFOX-方案1-计算器.html`：主页面，所有样式和脚本都在单个 HTML 文件内。
- `android/`：Android WebView 壳，用于把同一个 HTML 打包成 APK。
- `.github/workflows/android-apk.yml`：GitHub Actions 构建流程，推送 `main` 后自动构建 APK 并上传到 Release。
- `_d_meta.json`：设计资产记录。

## APK

仓库保留 HTML 版本，同时 GitHub Actions 会把 HTML 复制到 Android assets 中构建 APK。

最新 APK 会发布到 GitHub Releases 的 `latest` 标签中，文件名为 `HAIC-FOLFOX.apk`。

## 版权

(c) CDX
