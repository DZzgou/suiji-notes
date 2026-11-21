# 随记 V1.0 · 极简备忘录

面向中老年商务人士的轻量级手机备忘录。白底深蓝、默认 20px 正文、大点击区域、固定底部新建按钮。

## 功能
- 笔记：快速新建、标题选填、空标题自动使用正文第一行、约 500ms 自动保存、全文搜索、置顶、回收站恢复。
- 待办：添加、勾选完成、删除。
- 字体：标准 18px、大字 20px、特大 24px。
- 数据：IndexedDB 本地保存、JSON 导出、合并导入、导入前安全备份、备份提醒。
- PWA：HTTPS 安装、离线应用壳缓存。

## GitHub Pages
在仓库 Settings → Pages → Build and deployment 中，将 Source 设为 **GitHub Actions**。`main` 分支更新后自动部署。

网站地址：<https://dzzgou.github.io/suiji-notes/>

## 手机安装
- Android：Chrome 打开网站，选择「安装应用」或「添加到主屏幕」。
- iPhone：Safari 打开网站，选择「分享 → 添加到主屏幕」。

## 数据与隐私
笔记和待办保存在当前设备的 IndexedDB 中。本版本不提供账号和云同步。换设备、清理浏览器数据或卸载前，请在设置中导出 JSON 备份。公开仓库只包含应用源代码，不包含用户笔记。
