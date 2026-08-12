# 楼梯设计器 · 自建房/住宅

一个纯 HTML 的楼梯设计工具，无需安装，双击 `staircase-designer-v5.html` 即可在浏览器中使用。

## 在线使用

<https://kawabonka.github.io/staircase-designer/staircase-designer-v5.html>

## 国内镜像

国内网络访问加速地址（始终同步到 main 分支最新版）：

- jsDelivr 官方 CDN 镜像（推荐）：<https://cdn.jsdelivr.net/gh/kawabonka/staircase-designer@main/staircase-designer-v5.html>
- GitHub 加速代理（备用）：<https://ghproxy.net/https://raw.githubusercontent.com/kawabonka/staircase-designer/main/staircase-designer-v5.html>

## 功能

- 楼梯类型选择（一字型 / L 型转角 / U 型转角）
- 基本尺寸参数设置（踏步宽、高、梯宽、层高等）
- L / U 型转角自定义（休息平台、转角踏步、梯井宽、平台形状）
- 净空与撞头提示
- 住宅规范校验（参考 GB 50352）
- 平面图、剖面图、3D 视图与排砖/构件表
- 视图一键最大化，看图更方便
- mm / 英寸单位一键切换
- 方案导出 / 导入（JSON）
- 图纸导出为 SVG 矢量图或 JPG 图片

## 本地使用

直接用浏览器打开 `staircase-designer-v5.html` 即可，所有数据都在本地计算，不上传任何信息。

旧版 `staircase-designer-v4.html`、`staircase-designer-v2.html`、`staircase-designer.html` 仍保留，可继续访问。

## 更新日志

### v5.0（2026-08-12）

- 新增 U 型楼梯休息平台形状选择：矩形 / 三角形，平面图与 3D 视图同步显示
- 优化 U 型楼梯平台踏步绘制，转角表达更清晰
- 新增页脚署名，导出 SVG 图纸同步带页脚

完整更新说明见 [GitHub Release 页面](https://github.com/kawabonka/staircase-designer/releases/tag/v5.0.0)。

### v4.0（2026-08-12）

- 新增单位切换：mm / 英寸一键切换，所有尺寸、校验、图纸和构件表同步换算
- 新增顶部快捷导航：一键跳转“基本尺寸 / 结果摘要 / 规范校验”
- 新增方案保存与导入：可导出 JSON 方案文件，之后一键导入恢复配置
- 新增图纸导出：支持 SVG 矢量图与 JPG 图片
- 新增 U 型转角楼梯：两跑平行 + 顶部休息平台，可设置梯井宽度
- 新增视图最大化：平面图 / 剖面图 / 3D 图一键放大查看
- 优化 3D 视图自动适配与居中显示
- 界面优化：导出按钮与单位按钮更清晰易用

完整更新说明见 [GitHub Release 页面](https://github.com/kawabonka/staircase-designer/releases/tag/v4.0.0)。

### v2.0（2026-08-12）

- 新增“开洞尺寸建议”：直梯给出矩形洞口，L 型转角梯给出 L 形洞口，按 1.85 m 净空高度并预留四周余量计算
- 优化平面图绘制：视图垂直居中显示
- 优化平面图尺寸标注：距离楼梯轮廓收紧，减少遮挡

完整更新说明见 [GitHub Release 页面](https://github.com/kawabonka/staircase-designer/releases/tag/v2.0.0)。

## 发布

本页面通过 GitHub Pages 发布，由 `main` 分支根目录直接托管。
