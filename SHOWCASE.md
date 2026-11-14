<div align="center">

# PixivPaper Showcase · 实机画面与动态壁纸演示

[简体中文 README](./README.md) | [English README](./README.en.md) | [日本語 README](./README.ja.md)

</div>

---

<a id="wallpaper-live-demo"></a>

## 🎬 Desktop Wallpaper Engine Demo / 桌面动态壁纸实机演示 / デスクトップ壁紙デモ (`paper.gif`)

> 展示独立 `ScreenHost`（Direct3D 11 / DirectComposition / `WorkerW`）在桌面实机运行的动态壁纸、拼图排版、背景与转场效果。  
> *Live desktop capture powered by the isolated `ScreenHost` (D3D11 + DirectComposition + `WorkerW`) wallpaper engine.*

<div align="center">
  <img src="image/paper.gif" alt="PixivPaper 桌面动态壁纸实机演示 Live Wallpaper Demo" width="96%" />
  <br>
  <sub>如因 GitHub 预览体积限制未能直接加载动图，可点击查看原文件：<a href="./image/paper.gif">image/paper.gif</a></sub>
</div>

---

## 🖼️ Main Gallery (Tri-lingual UI) / 三语主界面画廊 / 3言語ギャラリー表示

<table>
<tr>
<td align="center" width="33%">
  <img src="image/1.jpg" width="300" alt="简体中文主界面瀑布流">
  <br><b>简体中文 (zh-CN)</b>
  <br><sub>推荐流瀑布流 · 榜单 · 侧边多屏导航</sub>
</td>
<td align="center" width="33%">
  <img src="image/2.jpg" width="300" alt="English Main Gallery">
  <br><b>English (en-US)</b>
  <br><sub>Masonry gallery · Multi-monitor sidebar</sub>
</td>
<td align="center" width="33%">
  <img src="image/3.jpg" width="300" alt="日本語メインギャラリー">
  <br><b>日本語 (ja-JP)</b>
  <br><sub>ギャラリー一覧 · プレビュー三言語切替</sub>
</td>
</tr>
</table>

---

## ⚙️ Wallpaper Engine & HLSL Editor / 壁纸配置与着色器定制 / 壁紙設定＆HLSLエディタ

<table>
<tr>
<td align="center" width="50%">
  <img src="image/4.jpg" width="430" alt="多屏壁纸与 8 大来源配置">
  <br><b>多屏管理与 8 大图片来源 / Multi-Display & Sources</b>
  <br><sub>独立配置每块屏幕 · 热门 / 发现 / 订阅 / 画师 / 本地文件夹等来源</sub>
</td>
<td align="center" width="50%">
  <img src="image/5.jpg" width="430" alt="转场随机池与实时 HLSL 编辑器">
  <br><b>转场随机池与实时 HLSL 编辑器 / Transitions & Live HLSL Editor</b>
  <br><sub>多选转场候选池 · 滤镜下拉与 HLSL 源码直改即时编译 · 非模态参考手册</sub>
</td>
</tr>
</table>

---

## 🔍 Artwork Viewer, Slideshow & Artist Page / 看图详情、幻灯片与画师主页 / 詳細ビュー＆作者ページ

<table>
<tr>
<td align="center" width="50%">
  <img src="image/10.jpg" width="430" alt="作品详情与相似画师推荐抽屉">
  <br><b>详情大图与探索推荐 / Detail Viewer & Recommendations</b>
  <br><sub>右侧滑出抽屉直接浏览相似画师与代表作品，支持一键关注</sub>
</td>
<td align="center" width="50%">
  <img src="image/11.jpg" width="430" alt="作品详细信息与双语标签抽屉">
  <br><b>作品详情与双语标签 / Artwork Info & Bilingual Tags</b>
  <br><sub>标题/尺寸/时间左键复制 · 简介局部复制 · 标签左键搜索/右键复制</sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
  <img src="image/12.jpg" width="430" alt="详情页视口右键功能菜单">
  <br><b>视口快捷右键菜单 / Context Actions</b>
  <br><sub>复制图片 · 另存为/导出 GIF · 幻灯片 · 直接设为指定屏幕壁纸</sub>
</td>
<td align="center" width="50%">
  <img src="image/13.jpg" width="430" alt="详情幻灯片设置弹窗">
  <br><b>幻灯片设置 / Slideshow Settings</b>
  <br><sub>停留秒数 · 动图播完一轮/跳过 · 多图播头图/逐页/小数秒快播</sub>
</td>
</tr>
<tr>
<td align="center" colspan="2">
  <img src="image/21.jpg" width="680" alt="画师个人主页与作品列表">
  <br><b>画师个人主页 / Artist Profile</b>
  <br><sub>画师头像、统计信息、关注与本地屏蔽开关及全部作品瀑布流</sub>
</td>
</tr>
</table>

---

## 🔎 Search, Subscriptions, Filtering & Network / 搜索订阅、屏蔽管理与网络测速

<table>
<tr>
<td align="center" width="50%">
  <img src="image/7.jpg" width="430" alt="高级搜索与热门推荐标签">
  <br><b>高级搜索与热门标签 / Advanced Search & Trending Tags</b>
  <br><sub>匹配方式 · 年龄分级 · 同义词开关 · 投稿日期范围 · 按 PID/UID 直达</sub>
</td>
<td align="center" width="50%">
  <img src="image/8.jpg" width="430" alt="搜索订阅试运行实时聚合预览">
  <br><b>搜索订阅实时聚合预览 / Subscription Live Bucket Preview</b>
  <br><sub>试运行实时查看命中作品清单，确认无误后再定时自动归档</sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
  <img src="image/6.jpg" width="430" alt="本地屏蔽标签集管理">
  <br><b>本地屏蔽标签集 / Blocked Tag Sets</b>
  <br><sub>内置模板与自定义标签集，支持展开微调、单条停用及独立开关</sub>
</td>
<td align="center" width="50%">
  <img src="image/9.jpg" width="430" alt="网络代理、DoH 与 CDN 测速">
  <br><b>网络代理、DoH 与 CDN 测速 / Proxy, DoH & CDN Benchmark</b>
  <br><sub>支持直连/系统/自定义 HTTP 代理、多组 DoH 安全解析与一键测速</sub>
</td>
</tr>
</table>

---

<div align="center">

[⬅️ 返回简体中文首页](./README.md) &nbsp;|&nbsp; [⬅️ Back to English README](./README.en.md) &nbsp;|&nbsp; [⬅️ 日本語 README に戻る](./README.ja.md)

</div>
