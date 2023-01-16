# busuanzi-modified

基于不蒜子2.3官网数据自定义访问量(site_pv, site_uv, page_pv)。Customize your site view count based on busuanzi.

## 修改

你可以自定义`busuanzi.pure.js`中的第75, 80, 85行，分别对应了站点访问量、独立访客和文章阅读量。取一个你喜欢的数字，然后自行压缩并托管。

## 部署

将你的网站从`busuanzi.ibruce.info`引用的`busuanzi.pure.mini.js`替换为新的js地址，如本仓库的`https://raw.githubusercontent.com/Pil0tXia/busuanzi-modified/main/busuanzi.pure.mini.js`

你也可以使用CDN加速访问：

- jsDelivr: `https://cdn.jsdelivr.net/gh/Pil0tXia/busuanzi-modified/busuanzi.pure.mini.js`

- 渺软公益CDN：`https://jsd.onmicrosoft.cn/gh/Pil0tXia/busuanzi-modified/busuanzi.pure.mini.js`

- 我自用的CDN（不作任何SLA保障）：`https://static.pil0txia.com/assets/busuanzi/2.3/busuanzi.pure.mini.js`

如果你正在使用 Hexo 的 Butterfly 主题，请参考[这篇文档](https://butterfly.js.org/posts/4aa8abbe/#%E8%A8%AA%E5%95%8F%E4%BA%BA%E6%95%B8-busuanzi-UV-%E5%92%8C-PV)修改地址。

## 建议

建议将其用来迁移站点历史访问量即可，例如从@记录迁移到了www，却丢失了以前的访问量。数字改得太大，SEO指数却很低，会被人笑话的。这只是一个建议。
