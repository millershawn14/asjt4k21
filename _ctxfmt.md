# 上下文对照测试

下面每一节都只用同一种 URL 写法（`<code>http://域名/路径</code>`），但**上下文不同**，
用来定位到底是什么把链接化打断了。

## 1. markdown 段落 + 纯文字，URL 紧贴 code

<code>http://txey.lrltd.cn/Article/details/P10001.sHtML</code>

## 2. markdown 段落 + 前面有竖线管道

 | 来源：<code>http://txey.lrltd.cn/Article/details/P10002.sHtML</code>

## 3. markdown 段落 + 带 br 标签在 URL 前

<br> | 来源：<code>http://txey.lrltd.cn/Article/details/P10003.sHtML</code>

## 4. 整段裸 HTML（模拟生成器实际输出）

<h3>标题四</h3><br><p>正文一段。<br><br> | 来源：<code>http://txey.lrltd.cn/Article/details/P10004.sHtML</code></p><br><br>

## 5. 整段裸 HTML + br 紧贴 code

<h3>标题五</h3><br><p>正文一段。<br><br> | 来源：<code>http://txey.lrltd.cn/Article/details/P10005.sHtML</code></p><br><br>

## 6. 完全复刻生成器的一整块（h1 + p + h2 + h3 + p）

<h1> AI Builders Digest 今日热点快报</h1><br><p><strong>2026年09月22日 10时00分00秒(UTC+8)</strong></p><br><hr><br><h2>一、国内时政</h2><br><h3>标题六</h3><br><p>正文一段。<br><br> | 来源：<code>http://txey.lrltd.cn/Article/details/P10006.sHtML</code></p><br><br>

## 7. 纯 markdown 语法（对照，作为保险方案）

- 来源：<http://txey.lrltd.cn/Article/details/P10007.sHtML>
- 来源：[链接](http://txey.lrltd.cn/Article/details/P10008.sHtML)

---

对照标记：P10001 ~ P10008
