# RSC 比赛签到页（编程猫佛山北滘校区）

静态部署页，源文件为 `编程猫佛山北滘校区参赛时间汇总.html`（已复制为本仓库 index.html）。

## 更新方式
1. 修改源文件后，复制到本目录覆盖 index.html
2. `git add index.html && git commit -m "更新说明"`
3. `git push origin main` → GitHub Pages 自动更新（约1分钟生效）

## 访问地址
https://liqiuyan02-dotcom.github.io/rsc-checkin-schedule/

## 多老师实时同步（LeanCloud）
页面内置云同步框架，填入凭据即启用：
在 index.html 中搜索 `const LC = { appId: "", appKey: "", serverURL: "" }`，
填入 LeanCloud 应用的 AppID / AppKey / 服务器URL（并在 LeanCloud 控制台创建 Class: Checkin）后推送即可。
留空 = 各设备独立存储（单机模式）。