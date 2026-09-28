# 素材来源

当前漫画版的 10 位武将立绘与 23 种卡牌画面由本项目在 `comic-art.js` 中原创绘制为 SVG，配以 CSS 网点、分镜和阴影，无需加载外部图片。

以下为保留在 assets 中的初版历史画像归档，当前漫画版不加载。初版使用 Wikimedia Commons 收录的历史艺术作品。已于 2026-09-09 通过 Commons 文件元数据核实以下六项标记为 Public domain（公共领域）。归档文件保留原始图像。

| 本地文件 | 作品 / 作者 | 来源 |
| --- | --- | --- |
| `caocao.jpg` | 《三才图会》曹操像 / 王圻 | https://commons.wikimedia.org/wiki/File:Cao_Cao_scth.jpg |
| `liubei.jpg` | 历代帝王图中的刘备 / 阎立本 | https://commons.wikimedia.org/wiki/File:Liu_Bei_Tang.jpg |
| `sunquan.jpg` | 历代帝王图中的孙权 / 阎立本 | https://commons.wikimedia.org/wiki/File:Sun_Quan_Tang.jpg |
| `guanyu.jpg` | 关羽历史插画 / 未详 | https://commons.wikimedia.org/wiki/File:Guanyu-1.jpg |
| `zhaoyun.jpg` | 赵云历史插画 / 未详 | https://commons.wikimedia.org/wiki/File:ZhaoYun.jpg |
| `diaochan.jpg` | 清代貂蝉插画 / 未详 | https://commons.wikimedia.org/wiki/File:Diaochan_Qing_Dynasty_Illustration.jpg |

字体为 Google Fonts 提供的 **Noto Serif SC**，使用页面中实际出现的文字子集，包含 400–900 六个字重。字体采用 SIL Open Font License 1.1，全文保存在 `FONT-LICENSE.txt`。字体项目：https://github.com/notofonts/noto-cjk 。

山景、印章、卡牌纹样、界面图标由本项目以 SVG/CSS 绘制。音效使用 Web Audio 实时合成。

曾尝试通过内置 imagegen 工具生成六格武将画像，但工具未返回可用图像文件，因此项目未使用生成图片。尝试的提示词为：六位三国武将（曹操、刘备、孙权、关羽、赵云、貂蝉），严格三列两行肖像图集，水墨与淡彩历史游戏插画，米色宣纸、玉绿和青铜色，不含文字或水印。初版画像来自上表所列历史作品；当前漫画版使用原创 SVG 立绘。
