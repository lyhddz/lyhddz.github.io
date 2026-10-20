# 站点静态产物

本目录由 `../export_static.js` 自动生成,**请勿手工改动**。每次跑导出器都会清空再重建。

## 部署

本仓库为 [GitHub Pages](https://pages.github.com/) 站点仓库,**仓库名必须是 `<你的用户名>.github.io`**,否则所有绝对路径会 404。

部署步骤见项目根目录 [`免费上线指南.md`](../免费上线指南.md) 或 [`GitHub部署指南.md`](../GitHub部署指南.md)。

## 修改内容并推送

在项目根目录:

```bat
deploy.bat
```

或在 git bash:

```bash
./deploy.sh
```

会依次完成: 导出静态站 → git add → commit → push。

## 关于源码

源码、配置文件、`db.json`(含管理员密码、公司真实信息) **不在本仓库**,只在本机。