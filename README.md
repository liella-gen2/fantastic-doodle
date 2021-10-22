# Notifications of `Liella! Generation II`

Here's the nontification board of `Liella! Generation II`

Hope you all enjoy our works!

## [`Main Site (主站传送门): https://liella-gen2.github.io/`](https://liella-gen2.github.io/)

and [Source](https://github.com/liella-gen2/notifications/) on [our GitHub](https://github.com/liella-gen2/)

## NOTIFICATIONS

* `2021-10-23 00:54:24` Site updated on branch [`master`](https://github.com/liella-gen2/liella-gen2.github.io/tree/master) [`#00973f7`](https://github.com/liella-gen2/liella-gen2.github.io/commit/00973f734af8e9d56dd565eec57122c0b3118c1f)
  1. Added support of [`LaTeX`](https://www.latex-project.org/) based on [`MathJax`](https://www.mathjax.org/).\
     加入了基于 [`MathJax`](https://www.mathjax.org/) 的 [`LaTeX`](https://www.latex-project.org/) 支持。
  2. Added audio player [`APlayer`](https://aplayer.js.org/), using [Hexo tag-plugin](https://hexo.io/zh-cn/docs/tag-plugins/) [`hexo-tag-aplayer`](https://github.com/MoePlayer/hexo-tag-aplayer/).\
     加入了音频播放器 [`APlayer`](https://aplayer.js.org/) ，使用 [Hexo 标签插件](https://hexo.io/zh-cn/docs/tag-plugins/) [`hexo-tag-aplayer`](https://github.com/MoePlayer/hexo-tag-aplayer/) 实现。
  3. New post! (投递文章): [`/2021/10/22/test2/`](https://liella-gen2.github.io/2021/10/22/test2/) 测试页面2, 长篇文字测试
  4. New post! (投递文章)：[`/2021/10/22/test3/`](https://liella-gen2.github.io/2021/10/22/test3/) 测试页面3, 音频播放器
  5. New post! (投递文章): [`/2021/10/23/test4/`](https://liella-gen2.github.io/2021/10/23/test4/) 测试页面4, 数学公式
  6. Base16 theme constructed! Currently using the one named `liellized`.

* `2021-10-21 01:10:57` Site updated on branch [`master`](https://github.com/liella-gen2/liella-gen2.github.io/tree/master) [`#2db76e5`](https://github.com/liella-gen2/liella-gen2.github.io/commit/2db76e5c29e7658a5447714371b1de26027d6bd5)
  1. Page added! (增加页面): [`/tags/`](https://liella-gen2.github.io/tags/)
  2. Page added! (增加页面): [`/categories/`](https://liella-gen2.github.io/categories/)
  3. Page added! (增加页面): [`/search/`](https://liella-gen2.github.io/search/)
  4. Tags added! (设置Tags):\
     [`#Chihori (涩谷 千穗理)`](https://liella-gen2.github.io/tags/Chihori-涩谷-千穗理/)
     [`#Chisato (岚 千砂都)`](https://liella-gen2.github.io/tags/Chisato-岚-千砂都/)
     [`#Kanako (涩谷 香菜子)`](https://liella-gen2.github.io/tags/Kanako-涩谷-香菜子/)
     [`#Kanon (涩谷 香音)`](https://liella-gen2.github.io/tags/Kanon-涩谷-香音/)
     [`#Kuku (唐 可可)`](https://liella-gen2.github.io/tags/Kuku-唐-可可/)
     [`#Otoha (涩谷 音羽)`](https://liella-gen2.github.io/tags/Otoha-涩谷-音羽/)
     [`#Ren (叶月 恋)`](https://liella-gen2.github.io/tags/Ren-叶月-恋/)
     [`#Sou (平安名 薮)`](https://liella-gen2.github.io/tags/Sou-平安名-薮/)
     [`#Sumire (平安名 堇)`](https://liella-gen2.github.io/tags/Sumire-平安名-堇/)
  5. 基于CSS设计了模仿[萌娘百科](https://zh.moegirl.org.cn/)的黑幕功能。\
     基础状态:
     ![仿萌娘百科黑幕，hidiv-demo.jpeg](https://github.com/liella-gen2/notifications/blob/main/hidiv-demo.jpeg?raw=true)
     指针停留上方:
     ![仿萌娘百科黑幕（hover激活状态），hidiv-hover.jpeg](https://github.com/liella-gen2/notifications/blob/main/hidiv-hover.jpeg?raw=true)

* `2021-10-20 20:02:38` Site updated on branch [`master`](https://github.com/liella-gen2/liella-gen2.github.io/tree/master) [`#7852297`](https://github.com/liella-gen2/liella-gen2.github.io/commit/7852297ef2136acb77a023da8a2fb05585e9c638)
  1. Page added! (增加页面): [`/2021/10/20/test/`](https://liella-gen2.github.io/2021/10/20/test/)

* `2021-10-20 12:44`
  1. 建立了公告板

## `(°∀°)ﾉ`

```js
const http = require("http");
const hostname = "127.0.0.1";
const port = 1337;
http.createServer((req, res) => {
  res.writeHead(200, { "Content-Type": "text/plain" });
  res.end("できっこないよって思ってたことも 踏みだせばほら叶うんだ\n");
}).listen(port, hostname, () => {
  console.log(`At http://${hostname}:${port}/ 今、始まるよSymphony`);
});
(() => {
    const liella = require("Liella");
    liella.restart("Generation II!");
    })();
```
