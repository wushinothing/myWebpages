# 我的静态网页（GitHub Pages 托管）

本文件夹用于把课本【实例 3-1】的网页挂到 GitHub Pages 上，供全世界访问。

## 文件说明

| 文件 | 来源 | 说明 |
| --- | --- | --- |
| `index.html` | （选学内容）Word 教程里的示例 | 红色背景的首页。仓库有 `index.html` 时，访问 `https://用户名.github.io/仓库名/` 即可看到它 |
| `ex3_1.html` | 软件.zip 中的 `ex3_1.html` | 课本 103 页【实例 3-1】「我的第一个网页」 |

## 关于编码

压缩包里原始的 `ex3_1.html` 是 GBK 编码且没有声明字符集，直接传到 GitHub Pages（服务器按 UTF-8 发送）时中文会变成乱码。
因此这里保存为 UTF-8，并补了一行 `<META charset="UTF-8">`，其余代码与原文完全一致。

## 访问地址

- 首页：`https://用户名.github.io/仓库名/`
- 实例 3-1：`https://用户名.github.io/仓库名/ex3_1.html`

> 有多个 html 文件时，网址必须具体到文件名（也就是上面第二条）。
