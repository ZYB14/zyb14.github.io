# 兼容性

## 技术支持：轻风科技

使用不兼容浏览器会导致出现不正常页面

| 浏览器 | 更新及支持          |
| ------- | ------------------ |
| IE   | :x: |
| EDGE   | :white_check_mark:                |
| Safair   | :white_check_mark: |
| 谷歌浏览器   | :white_check_mark:                |
## 不在兼容 IE6、IE7、IE8、IE9、IE10、IE11

为了兼容这个曾经的浏览器霸主，网页设计人员需要做大量的代码工作。对于普通用户而言，低版本 IE 更是一个岌岌可危的安全隐患，在 Windows 历史上几次大的木马病毒事件都是利用 IE 漏洞进行传播。所以，请和我们一起抵制 IE 的过期版本！

## 对旧版 Internet Explorer 的支持服务已终止
从 2016 年 1 月 12 日开始，仅面向受支持操作系统的最新版 Internet Explorer 将收到技术支持和安全更新。Internet Explorer 11 是最新版的 Internet Explorer，将继续在 Windows 7、Windows 8.1 和 Windows 10 上收到安全更新、兼容性修复程序和技术支持。

## 这意味着什么？
这意味着您应该采取行动。2016 年 1 月 12 日之后，Microsoft 将不再为 Internet Explorer 早期版本提供安全更新或技术支持。安全更新用于修补可能被恶意软件利用的漏洞，从而为提高用户及其数据的安全性提供帮助。定期安全更新帮助保护计算机不受恶意攻击，因此升级和保持最新很重要。

## 我如何升级 Internet Explorer？
* 中小型企业：对于考虑浏览器升级的中小型企业，选择有很多。没有 Web 应用程序的中小型组织（员工在 500 人以下）可使用自动更新进行自动更新。对于依赖现有 Web 应用程序的中小型企业，可以寻找 Microsoft 认证合作伙伴以了解符合其业务需要的最佳方案。

* 企业客户：Microsoft 为大型组织（员工在 500 人以上）提供丰富的技术资源、工具和专家指导，以帮助这些组织轻松部署和管理 Windows、Office 以及 Internet Explorer 产品和技术。通过联系您的 Microsoft 销售代表、Microsoft Services 部门或 Microsoft 认证合作伙伴，详细了解迁移和部署计划。了解如何通过访问 TechNet 自行试用和部署最新版本的 Edge。

## 使用 Internet Explorer 早期版本的潜在风险
2016 年 1 月 12 日后运行 Internet Explorer 早期版本可能使您面临潜在风险，例如：

* 安全性：没有关键的浏览器安全更新，您的 PC 可能易受有害病毒、间谍软件和其他恶意软件的攻击，它们可以窃取或损害您的业务数据和信息。

* 合规性：需要遵守法规规定（如 HIPAA）的企业应执行尽职调查，以评估它们使用不受支持的软件是否仍能满足合规性要求。

* 缺乏独立软件 (ISV) 支持：许多独立软件供应商 (ISV) 都不再支持 Internet Explorer 早期版本。例如，Office 365 采用现代 Web 标准，而且与最新浏览器一起使用时运行最出色。


### 轻风科技首席执行官的一些句话：
> 因为轻风实在是支付不起高昂的带宽费，所以将官网托管至github。
> 网站空间由github提供
> 网站CDN由cloudflare提供
* 轻风科技永久网址：https://qingfengnb.cn
* 源码为开源项目，可直接部署至自己存储库！
* github开源地址：https://github.com/imsyy/home
* 此仓库网站源码为魔改版本，建议使用官方原版！
* 版本所有，违者必究，请不要恶意使用此模版！

<p>
<strong><h2>無名の主页</h2></strong>
简单的小主页，原来的看够了，重新弄了一个
</p>

![無名の主页](https://s2.loli.net/2022/07/14/K5JigfvDoNewtuS.webp)

>主页的 Logo 字体已经过压缩，若用本站 Logo 以外的字母会变回默认字体，这里是 [完整字体](https://file.4everland.app/font/Other/Pacifico-Regular.ttf)

### Demo

>由于 CDN 缓存原因，查看最新效果可能需要 `Ctrl` + `F5` 强制刷新浏览器缓存

- [無名の主页](https://www.imsyy.top)
- [無名の主页 - 备用线路](https://home-imsyy.vercel.app/)

### 功能

- [x] 载入动画
- [x] 站点简介
- [x] Hitokoto 一言
- [x] 日期及时间
- [x] 实时天气
- [x] 时光进度条
- [x] 移动端适配

* [ ] 播放器取消使用 Aplayer

### 部署

* **安装** [node.js](https://nodejs.org/zh-cn/) **环境**

  > node > 16.16.0  
  > npm > 8.15.0
  
* 然后以 **管理员权限** 运行 `cmd` 终端，并 `cd` 到 项目根目录
* 在 `终端` 中输入：

```bash
# 安装 yarn
npm install -g yarn

# 安装依赖
yarn install

# 预览
yarn dev

# 构建
yarn build
```
> 构建完成后，静态资源会在 **`dist` 目录** 中生成，可将 **`dist` 文件夹下的文件**上传至服务器，也可使用 `Vercel` 等托管平台一键导入并自动部署

### 天气

天气及地区获取需要 `高德开放平台` 相关 API

- 前往 [高德开放平台控制台](https://console.amap.com/dev/index) 创建一个 `Web 服务` 类型的 `Key`，并将 `Key` 填入 `.env` 中的 `VITE_WEATHER_KEY` 中

也可自行更换其他方式



```bash
# 歌曲 API 地址
VITE_SONG_API = "https://api-meting.imsyy.top"
# 歌曲服务器 ( netease-网易云, tencent-qq音乐 )
VITE_SONG_SERVER = "netease"
# 播放类型 ( song-歌曲, playlist-播放列表, album-专辑, search-搜索, artist-艺术家 )
VITE_SONG_TYPE = "playlist"
# 播放 ID
VITE_SONG_ID = "7452421335"
```

### 字体

现采用 `HarmonyOS Sans` 开源字体，采用字体拆分，提升加载速度

>由于本站 `CDN` 已开启防盗链，**非本站域名不可访问**，请将字体引入链接更改为下方内容，否则 **自定义字体将失效**
>
>`https://s1.hdslb.com/bfs/static/jinkela/long/font/regular.css`

<details>
<summary>旧版方式</summary>

>由于本项目引入了中文字体，需要压缩中文字体以提高网页加载速度（ 也可以取消使用中文字体 ）

#### 中文字体去除繁体

- 安装 `Python 3.7` 和 `pip`
- 运行 `pip install fonttools`
- 下载 [sc_unicode.txt](https://gist.githubusercontent.com/imaegoo/d64e5088b723c2e02c40985f55ff12db/raw/5ebd2ce49418c73459a9dfe050483409306a6c1d/sc_unicode.txt)
- 运行 `pyftsubset 字体名称.ttf --unicodes-file=sc_unicode.txt`

#### 字体进一步压缩

- 编译安装 `Google woff2`

```bash
sudo apt-get install -y git g++ make
git clone --recursive https://github.com/google/woff2.git
cd woff2
make clean all
```

- 再压缩字体

```
./woff2_compress ./字体名称.ttf
```

- 最终可对原字体进行缓加载，**先行加载压缩后的字体**

>详细信息可前往 [虹墨空间站](https://www.imaegoo.com/2020/chinese-font-compress/) 查看原文

</details>

### 技术栈

* [Vue](https://cn.vuejs.org/)
* [Vite](https://vitejs.cn/vite3-cn/)
* [Pinia](https://pinia.vuejs.org/zh/)
* [IconPark](https://iconpark.oceanengine.com/official)
* [xicons](https://xicons.org/)
* [Aplayer](https://aplayer.js.org/)

### API
* [MetingAPI By 武恩赐](https://api.wuenci.com/meting/api/)
* [小歪 API](https://api.ixiaowai.cn/)
* [高德开放平台](https://lbs.amap.com/)
* [Hitokoto 一言](https://hitokoto.cn/)

<a title="SSL" target="_blank" href="https://myssl.com/seal/detail?domain=blog.imsyy.top"><img src="https://img.shields.io/badge/MySSL-安全认证-brightgreen"></a>&nbsp;<a title="CDN" target="_blank" href="https://cdnjs.com/"><img src="https://img.shields.io/badge/CDN-Cloudflare-blue"></a>&nbsp;<a title="Copyright" target="_blank" href="https://imsyy.top/"><img src="https://img.shields.io/badge/Copyright%20%C2%A9%202020--2023-%E7%84%A1%E5%90%8D-red"></a>

### English-REAME
<p>
<strong><h2>無名の主页</h2></strong>
Simple little homepage, had enough of the original one and made a new one
</p>

![無名の主页](https://s2.loli.net/2022/07/14/K5JigfvDoNewtuS.webp)

>The logo font on the home page has been compressed, so if you use a font other than this logo, it will change back to the default font, Here is the [full font](https://file.4everland.app/font/Other/Pacifico-Regular.ttf)  

### Demo

>Due to CDN caching, you may need `Ctrl` + `F5` to force a browser cache refresh to see the latest results

- [無名の主页](https://www.imsyy.top)
- [無名の主页 - 备用线路](https://home-imsyy.vercel.app/)

### Functions

- [x] Loading animation
- [x] Site description
- [x] Hitokoto
- [x] Date and time
- [x] Live weather
- [x] Time progress bar
- [x] Mobile adaptation

* [ ] Player cancels using Aplayer

### Deployment

```bash
yarn install
yarn dev
yarn build
```
> Once the build is complete, the files in the `dist` folder can be uploaded to the server or imported and automatically deployed with one click using a hosting platform such as `Vercel`.

### Weather

Weather and area access requires `高德开放平台` related API

- Go to [高德开放平台控制台](https://console.amap.com/dev/index) to create a `Key` of type `Web Service` and fill the `Key` into `VITE_WEATHER_KEY` in `.env` 

It can also be replaced by other methods


```bash
# Songs API address
VITE_SONG_API = "https://api-meting.imsyy.top"
# Song server ( netease-netease, tencent-qq music )
VITE_SONG_SERVER = "netease"
# Playback type ( song-song, playlist-playlist, album-album, search-search, artist-artist )
VITE_SONG_TYPE = "playlist"
# Playback ID
VITE_SONG_ID = "7452421335"
```

### Fonts

Now using `HarmonyOS Sans` open source font, using font splitting to improve loading speed

>Because this site's `CDN` has opened anti-leech, **non-site domain name is not accessible**, please change the font import link to the following content, otherwise **custom fonts will be invalid**
>
>`https://cdn.jsdelivr.net/gh/imsyy/file/font/HarmonyOS_Sans/regular.min.css`

<details>
<summary>old way</summary>

>As Chinese fonts are introduced in this project, Chinese fonts need to be compressed to improve the loading speed of the page (you can also cancel the use of Chinese fonts)

#### Chinese font removal traditional

- Install `Python 3.7` and `pip`
- Run `pip install fonttools`
- Download [sc_unicode.txt](https://gist.githubusercontent.com/imaegoo/d64e5088b723c2e02c40985f55ff12db/raw/5ebd2ce49418c73459a9dfe050483409306a6c1d/sc_unicode.txt)
- Run `pyftsubset font-name.ttf --unicodes-file=sc_unicode.txt`

#### fonts further compressed

- Compile and install ``Google woff2``

```bash
sudo apt-get install -y git g++ make
git clone --recursive https://github.com/google/woff2.git
cd woff2
make clean all
```

- Compress the font again

```
. /woff2_compress . /font_name.ttf
```

- Eventually the original font can be slow loaded, **load the compressed font first**

>For more information, please go to [虹墨空间站](https://www.imaegoo.com/2020/chinese-font-compress/) to view the original article

</details>

### Technology Stack

* [Vue](https://cn.vuejs.org/)
* [Vite](https://vitejs.cn/vite3-cn/)
* [Pinia](https://pinia.vuejs.org/zh/)
* [IconPark](https://iconpark.oceanengine.com/official)
* [xicons](https://xicons.org/)
* [Aplayer](https://aplayer.js.org/)

### API

* [MetingAPI By 武恩赐](https://api.wuenci.com/meting/api/)
* [小歪 API](https://api.ixiaowai.cn/)
* [高德开放平台](https://lbs.amap.com/)
* [Hitokoto 一言](https://hitokoto.cn/)

<a title="SSL" target="_blank" href="https://myssl.com/seal/detail?domain=blog.imsyy.top"><img src="https://img.shields.io/badge/MySSL-安全认证-brightgreen"></a>&nbsp;<a title="CDN" target="_blank" href="https://cdnjs.com/"><img src="https://img.shields.io/badge/CDN-Cloudflare-blue"></a>&nbsp;<a title="Copyright" target="_blank" href="https://imsyy.top/"><img src="https://img.shields.io/badge/Copyright%20%C2%A9%202020--2023-%E7%84%A1%E5%90%8D-red"></a>

  
