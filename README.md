# RiichiCityUnlock
麻雀一番街解锁全部角色、皮肤、装扮等，基于[mitmproxy](https://github.com/mitmproxy/mitmproxy)的中间人攻击方式。

使用体验和真正拥有一样，只是别人看不到。

**警告：本程序首次发布后不到24小时，一番街官方就更新了校验代码，由此可见此程序已被一番街官方注意到，请务必使用小号体验！！！！**

## 📢用前须知
> 注意：解锁人物仅在本地有效，别人还是只能看到你原来的角色  
  
> 魔改千万条，安全第一条。<br />使用不规范，账号两行泪。
  
> 警告：<br />麻雀一番街游戏官方可能会检测并封号！<br />如产生任何后果与作者无关！<br />使用本脚本则表示同意此条款！

![人畜无害](https://hbimg.huaban.com/fbf520dd2ff8b5c1ca40b6bab6279ceeb498533a86c07-80kWzq_fw658)  

### ✈️Telegram频道&交流群
频道 [@Riichi_City](https://t.me/Riichi_City)

交流 [@Riichi_City_Chat](https://t.me/Riichi_City_Chat)

### ☕请作者喝咖啡
[点我为作者发电（爱发电，支持微信/支付宝）](https://afdian.com/a/Avenshy)

[点我为作者发电（Patreon，支持信用卡/Paypal）](https://patreon.com/Avenshy)

## 🥰当前功能
- [x] 解锁所有角色与皮肤
- [x] 解锁所有装扮
- [x] 解锁所有称号
- [x] 解锁所有加载CG
- [x] 支持星标角色
- [x] 自定义名称
- [x] 支持大厅自定义方案
- [ ] 支持保存装扮方案
- [ ] TODO……

## 🧐使用说明
1. 下载并解压
2. 运行`run.exe`
3. 打开代理软件（如[Proxifier](https://www.proxifier.com/)）
4. 将麻雀一番街程序加入代理，代理地址为 `127.0.0.1` ，端口 `41110`，具体配置过程可参考[MajsoulMax的使用说明](https://github.com/Avenshy/MajsoulMax?tab=readme-ov-file#%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)
5. 启动游戏

## 💸捐赠说明
注意：该程序可以免费使用，非必须捐赠，下方有操作说明。

注意：请先测试好能够使用，再考虑捐赠。

### 💢为什么要启用捐赠模式
1. 官方多次封堵和加密，花费大量时间和精力
2. 程序功能需要服务器支撑，服务器有固定开支
3. 作者维护需要动力push
4. ~~作者没钱了~~
   
### 🤗捐赠模式和免费模式的区别
免费模式下不会影响程序的使用，只是装扮无法在游戏中显示出来（获取所有装扮需要服务器支持）。

如需免费使用，可以修改程序文件夹下的`/config/settings.mod.yaml` 文件，将装扮修改为你想要使用的装扮id，重新启动RiichiCityUnlock即可。

除去特殊装扮外，装扮id都是有规律的，前2位为固定数字不变，后3位为当前装扮的序号，因此只需要修改后3位即可。

目前本程序所使用到的前两位id和对应关系，如下表所示：
| ID | NAME_ENG        | NAME_CHN          |
|:--:|------------------|-------------------|
| 13 | RiichiStick     | 立直棒            |
| 14 | CardBack        | 牌背              |
| 15 | Tablecloth      | 桌布              |
| 16 | SpecialEffect   | 特效              |
| 17 | LiZhiEffect     | 立直特效          |
| 18 | HallBGM         | 大厅BGM           |
| 19 | RankBGM         | 段位战BGM         |
| 20 | LZBGM           | 段位战BGM         |
| 24 | SceneEffect     | 场景特效          |
| 25 | HallBg          | 大厅背景          |
| 26 | CardFace        | 牌面             |
| 30 | AvatarFrame     | 头像框            |
| 36 | TableEdge       | 牌桌边框          |
| 37 | PersonalHead    | 个人头像          |
| 38 | Gallery         | 画廊背景          |

### 😘如何定价
1. 暂定10元/月（按31天算），根据金额计算时长
2. 一次性购买多月有折扣，时长越长，折扣越大
3. 不定时有活动

### 🤔如何捐赠&使用
1. 在[爱发电为作者发电](https://afdian.com/a/Avenshy)
2. 点击右上角头像进入** 我的主页 **
3. 查看当前浏览器地址，复制`/u/`后面的用户id。例如当前地址为 `https://afdian.com/u/adf397fe8374811eaacee52540025c377` ，则复制 `adf397fe8374811eaacee52540025c377` 这一串
4. 进入RiichiCityUnlock程序文件夹，找到 `/config/settings.yaml` 文件，将 `id: free` 中的 `free` 修改为刚刚复制的用户id
5. 保存并关闭，启动RiichiCityUnlock

## ⏬下载地址
[Releases](https://github.com/Avenshy/RiichiCityUnlock/releases/latest) 
