# RE-Amachiromaker

> 复活被甘城猫猫下线的捏脸网站。

## 二改说明

本项目是 [NekoQiye/RE-Amachiromaker](https://github.com/NekoQiye/RE-Amachiromaker) 的二改版本。

按原作者要求：**二改需在 GitHub 拉分支，并标注原项目地址**。本分支即依此发布，原项目地址见上。

更早的原作者为 [Charlie Chiang](https://github.com/charlie0129)（Amachiromaker）。图片版权归甘城なつき（[amashiro.com](https://amashiro.com/)）所有，请勿商用或二次售卖。许可条款见 [LICENSE](LICENSE)。

## 本分支相对原项目的改动

- **图片资源本地化**：将全部引用图片镜像到仓库 `app/` 目录，不再依赖外部 CDN，可完全离线自托管
- **界面重构**：配色与视觉参考 [甘城なつき官方网站](https://amashiro.com/)，改为白/浅蓝扁平配色与硬阴影，移除站内 Emoji 及多余的入场动画
- **缺陷修复**：
  - 移动端开启「减少动态效果」时看板娘剧烈抖动
  - 看板娘气泡文字溢出屏幕，且被项目信息卡片遮挡
  - 深色模式下贴图缩略图不可见
  - 预设数据损坏时整站白屏
  - 旧版移动浏览器保存 PSD 失败

## 功能

- **缩略图预览**：所有选项卡均配备缩略图
- **深色模式**：支持日间/夜间主题切换
- **导出**：支持保存 PNG 与 PSD，支持预设的导出与载入

## 如何构建

站点为纯静态页面，无需服务端。

1. 下载或克隆本仓库全部文件
2. 安装 Python（如果尚未安装）
3. 在终端中运行：

   ```bash
   python -m http.server 8000 --directory <项目根目录>
   ```

4. 在浏览器中访问：

   ```
   http://localhost:8000
   ```

## 在线体验

原项目的部署地址：

- https://nacho.zako.wf/
- https://www.hutaotao.top/amachiromaker/

本二改分支的部署地址：（部署后补充）

## 预览

<p align="center">
  <img src="readme-assets/screenshot.png" alt="界面截图" width="100%">
  <br>
  <em>原项目界面（供参考，本分支已改为浅蓝扁平风格）</em>
</p>

<p align="center">
  <img src="readme-assets/gif1.gif" alt="动画演示" width="90%">
  <br>
  <em>动画演示</em>
</p>

## 特别说明

原存储库因版权原因不包含图像资源。本二改分支出于自托管部署的需要，已将图片镜像至仓库内 `app/` 目录；图片版权均归甘城なつき所有，请勿商用或二次售卖，再分发前请自行确认合规。

## 支持项目

如果喜欢这个项目，请给原项目 [NekoQiye/RE-Amachiromaker](https://github.com/NekoQiye/RE-Amachiromaker) 一个 Star。

---

<p align="center">Made by NekoQiye, forked and modified</p>