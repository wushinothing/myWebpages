# 我的个人主页（GitHub Pages）

## 在线地址

- 首页：https://wushinothing.github.io/myWebpages/
- 实例 3-1：https://wushinothing.github.io/myWebpages/ex3_1.html

## 文件说明

| 文件 | 作用 |
| --- | --- |
| `index.html` | 美化后的个人主页。**你只需要改 3 处**：姓名、班级、学号 |
| `ex3_1.html` | 课本 103 页【实例 3-1】「我的第一个网页」，保留原始内容 |

## 怎么填写 index.html

用记事本或 VS Code 打开 `index.html`，搜索 `【` 就能定位到要改的地方：

```html
<span class="v"><span class="blank">【填写姓名】</span></span>
<span class="v"><span class="blank">【填写班级】</span></span>
<span class="v"><span class="blank">【填写学号】</span></span>
```

把 `【填写姓名】` 之类的替换成你自己的信息，`<span class="blank">` 这个标签留着不用动，
它会保留浅紫色的底和虚线下划线，让填进去的内容看起来像填写在横线上。

改完保存，在浏览器里双击 `index.html` 就能立刻看到效果。

## 改完怎么发布到网上

在 VS Code 的终端里执行（三条命令）：

```bash
git add -A
git commit -m "填写个人信息"
git push
```

推送成功后等 1～2 分钟，刷新 https://wushinothing.github.io/myWebpages/ 就是新版了。

## 关于编码

压缩包里原始的 `ex3_1.html` 是 GBK 编码且没有声明字符集，直接传到 GitHub Pages
（服务器按 UTF-8 发送）中文会变成乱码。因此这里保存为 UTF-8 并补了一行
`<META charset="UTF-8">`，其余代码与原文完全一致。
