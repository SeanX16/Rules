# Scripts

目前只有哔哩哔哩 iOS 端 App 的处理脚本。个人修改主要针对 `我的` 页面。

`BilibiliAds_mixed-js.conf` 里只有 `我的` 页面和 `tab` 的处理替换为了我自己的js脚本

`BilibiliAds_own-js.conf` 里所有 @ddgksf2013 的脚本全部替换为了我自己的js脚本

------------

### ID 和对应元素（由 Stream 软件在 iPhone 上抓包 JSON 整理得到）：

#### 国内版：
| ID  | 元素             | ID  | 元素             | ID  | 元素             | ID  | 元素             |
|------|----------------|------|----------------|------|----------------|------|----------------|
| 396  | 离线缓存       | 397  | 历史记录       | 3072 | 我的收藏       | 2830 | 稍后再看       |
| 171  | 创作中心       | 172  | 稿件管理       | 533  | 数据中心       | 174  | 有奖活动       |
| 709  | 开播福利       | 707  | 主播中心       | 2647 | 直播数据       | 708  | 主播活动       |
| 400  | 我的课程       | 401  | 看视频免流量   | 402  | 个性装扮       | 404  | 我的钱包       |
| 403  | 游戏中心       | 623  | 会员购         | 406  | 我的直播       | 3046 | 必火推广       |
| 913  | 数字周边       | 514  | 社区中心       | 968  | 工房           | 990  | 能量加油站     |
| 407  | 联系客服       | 812  | 听视频         | 964  | 未成年人守护   | 410  | 设置           |

#### 港版：
| ID  | 元素           | ID  | 元素           | ID  | 元素           | ID  | 元素         |
|------|--------------|------|--------------|------|--------------|------|------------|
| 494  | 离线缓存     | 495  | 历史记录     | 496  | 我的收藏     | 3084 | 稍后再看   |
| 500  | 联系客服     | 501  | 设置         | 741  | 我的钱包     | 742  | 稿件管理   |

---------------

原作者：[@ddgksf2013](https://github.com/ddgksf2013)

源文件：
[`BilibiliAds.conf`](https://raw.githubusercontent.com/ddgksf2013/Rewrite/master/AdBlock/BilibiliAds.conf)，
[`bilibili_json.js`](https://raw.githubusercontent.com/ddgksf2013/Scripts/master/bilibili_json.js)
