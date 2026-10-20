[English](README.md) | [简体中文](README.zh-CN.md)

# LiteMesh 项目主页

本仓库包含 LiteMesh 项目主页的源代码，用于展示研究摘要、方法介绍及实验结果。

**LiteMesh: An Efficient Quality-Aware Algorithm for Feature-Preserving Triangle Mesh Simplification**

## 项目地址

- 项目主页：https://longwuya.github.io/LiteMesh-homepage/
- 算法代码：https://github.com/longwuya/LiteMesh
- 主页源代码：https://github.com/longwuya/LiteMesh-homepage

## 页面内容

- Abstract：研究摘要。
- Introduction：方法介绍与演示视频。
- Results：实验结果与方法对比。
- Citation：论文引用信息。

## 本地预览

在仓库目录运行：

```sh
python -m http.server 8010 --bind 127.0.0.1
```

本地访问地址：http://127.0.0.1:8010/

## 部署与维护

网站使用静态 HTML、CSS 和 JavaScript 构建，通过 GitHub Pages 发布，无需运行 LiteMesh 算法或配置后端服务。

- 发布分支：`main`。
- 发布目录：仓库根目录。
- 更新方式：提交并推送页面修改后，由 GitHub Pages 自动部署。

页面作者信息、所属机构、研究文字和实验图注应与项目论文资料保持一致。图片及演示视频位于仓库内，可随页面一同部署。

## 目录说明

```text
index.html   页面内容
style.css    页面样式
page.js      导航与交互
images/      实验图片
icon/        机构校标
fonts/       本地字体及许可证
video.mp4    方法演示视频
```
