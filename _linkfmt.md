# 链接渲染格式对照测试

本文件用于实测：在 GitHub 的 markdown 渲染下，哪种写法能变成**真正可点的 `<a href>`**。

## A. 裸 URL 带协议

http://txey.lrltd.cn/Article/details/A00001.sHtML

## B. 裸 URL 带协议 + 问号紧跟域名

http://txey.lrltd.cn?/Article/details/B00002.sHtML

## C. 尖括号自动链接

<http://txey.lrltd.cn/Article/details/C00003.sHtML>

## D. markdown 链接语法

[来源](http://txey.lrltd.cn/Article/details/D00004.sHtML)

## E. 裸 HTML 锚标签

<a href="http://txey.lrltd.cn/Article/details/E00005.sHtML">来源</a>

## F. code 包裹裸域名（当前用的写法）

<code>txey.lrltd.cn?/Article/details/F00006.sHtML</code>

## G. code 包裹带协议 URL

<code>http://txey.lrltd.cn/Article/details/G00007.sHtML</code>

## H. 反引号包裹带协议 URL

`http://txey.lrltd.cn/Article/details/H00008.sHtML`

## I. 参考式链接

[来源][ref-i]

[ref-i]: http://txey.lrltd.cn/Article/details/I00009.sHtML

## J. HTML 锚 + 目标属性

<a href="http://txey.lrltd.cn/Article/details/J00010.sHtML" target="_blank" rel="nofollow">来源</a>

---

统计用：本文共有 10 种写法，域名均为 txey.lrltd.cn。
