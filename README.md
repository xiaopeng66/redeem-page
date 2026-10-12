# 兑换页

静态兑换页。打开页面、输入兑换码，浏览器本地解出访问地址（网站或下载直链）。

当前这一版的 200 个码都指向 `https://xiaopeng66.github.io/ai-welfare-daily/`，按钮显示「打开网站」。

页面是纯静态单文件（`index.html`），不含任何明文下载链接，也不含明文兑换码 —— 里面只有密文，
兑换码本身在你的本地生成记录里。因此这个仓库公开也无所谓：没有码就解不出任何东西。

线上地址：<https://xiaopeng66.github.io/redeem-page/>

生成方式：在本地项目 `redeem-shop` 里运行 `npm run static`（详见该项目的 README）。
重新生成后把 `index.html` 覆盖到本目录再推一次即可。
