多仓
-----
https://raw.iqiq.io/cracada/tvb/main/duo.json  

单仓
-----
https://raw.iqiq.io/cracada/tvb/main/dan.json  

本地仓
-----
https://raw.iqiq.io/cracada/tvb/main/bendi.json  

搬运线路
---
https://raw.iqiq.io/cracada/tvb/main/json/duoduo.json  
https://raw.iqiq.io/cracada/tvb/main/json/lianying.json  
https://raw.iqiq.io/cracada/tvb/main/json/qiaoji.json  
https://raw.iqiq.io/cracada/tvb/main/json/xiaoya.json  
https://raw.iqiq.io/cracada/tvb/main/json/yimu.json  

网络线路
---
南风： https://agit.ai/Yoursmile7/TVBox/raw/branch/master/XC.json  
菜妮丝： https://tvbox.cainisi.cf/  
神器每日推送: https://xn--m7r412advb92j21st65a.tk/pz.json  
饭太硬： http://xn--sss604efuw.ga/tv  
蜂蜜 https://ghproxy.com/raw.githubusercontent.com/FongMi/CatVodSpider/main/json/config.json  
老刘备 https://raw.iqiq.io/liu673cn/box/main/m.json  
霜辉月明py： https://raw.iqiq.io/lm317379829/PyramidStore/pyramid/py.json  
小雅js：http://drpy.site/js1  
巧技 http://pandown.pro/tvbox/tvbox.json  [2](http://cdn.qiaoji8.com/tvbox.json)  
恋影：https://www.lianyingtv.com/lianyingjingjian.html  
运输车： https://gitee.com/lekanbox/ysc/raw/master/ysc.json  




直播
---
https://raw.iqiq.io/cracada/tvb/main/tv.json  

壁纸
---
https://www.crsay.com/addons/tvbox/wp/  


IPTV
---
https://raw.iqiq.io/zbefine/iptv/main/iptv.txt  
https://raw.iqiq.io/whpsky/iptv/main/chinatv.txt  
https://raw.iqiq.io/vamoschuck/TV/main/M3U  
https://raw.iqiq.io/wuyun999/wuyun/main/zb/aptv.txt  
https://raw.iqiq.io/hussobaba/AILE-Tv/main/TEBER_TV.m3u  
https://raw.iqiq.io/goolguy007/radioer/main/TVradio  
https://raw.iqiq.io/zhanghongguang/zhanghongguang.github.io/main/CNTV.m3u  
https://raw.iqiq.io/fanmingming/live/main/tv/m3u/global.m3u  
https://raw.iqiq.io/YanG-1989/m3u/main/yu.m3u  
https://raw.iqiq.io/Kimentanm/aptv/master/m3u/ya.m3u  
https://github.com/youshandefeiyang/IPTV/tree/main/main  
bestv.m3u    BESTV源  
ghyx.m3u    GHYX源  
sxg.m3u    SXG-IPV6源  
aishang.m3u    爱尚源  
cqyx.m3u    CQYX源  



EPG 节目单  
---
https://epg.112114.xyz/pp.xml  
http://epg.51zmt.top:8000/e.xml  
https://epg.pw/xmltv.html?lang=zh-hant  

```
{
  "lives": [
    {
      "name": "TVLive",
      "type": 0,
      "url": "https://raw.iqiq.io/cracada/tvb/main/live/mytv.txt",
      "epg": "http://epg.112114.xyz/?ch={name}&date={date}",
      "logo": "https://epg.112114.xyz/logo/{name}.png",
      "ua": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/108.0.0.0 Safari/537.36",
      "boot": false
    }
  ]
}
```
 



配置相关
---
```
{
    // 代码配置相关
    "IsRecodeLog":true, // 是否记录文件日志
    
    // 默认配置相关
    "ForceChangeAPIUrl": true, //强制替换首页默认API地址，防止API失效不更新包的手段
    "APIUrl":"https://raw.iqiq.io/cracada/tvb/main/json/yimu.json", //首页默认API地址
    "HomeID": "csp_SP360", //厂长
    "HomeShowType": 1, //默认首页推荐 0 豆瓣热播 1 数据源推荐 2 历史
    "HomeSearchType": 0, //默认搜索展示 0 列表 1 缩略图
    "HomeFastSearch": false, //默认聚合模式
    "HomeDNSType": 0, //默认安全DNS 0 关闭 1 腾讯 2 阿里 3 360
    "HomeHistoryNum": 1, //默认历史记录 0 30条 1 50条 2 70条
    "HomePictureZoom": 0, //默认画面缩放 0 默认 1 16:9 2 4:3 3 填充 4 原始 5 裁剪
    "HomeWindowPreview": true, //默认窗口预览
    
homeshowsource???
    
    // 直播配置相关
    "Live":{
        "Channel": "CCTV-13", // 频道名字
        "ChannelReverse": false, // 换台反转
        "CrossGroup": false, // 跨选分类
        "ConnectTimeout": 1, // 超时换源时间 0 5s 1 10s 2 15s 3 20s 4 25s 5 30s
        "ShowNetSpeed": true, // 显示网速
        "ShowTime": true // 显示时间
    },
    
    // 更新相关
    "IsForceUpdate":false, //是否强制显示更新UI
    "UpdateData":{  //更新数据
        "NewVersion":"1.0.3", //最新版本号
        "ForceUpdate":false, //是否强制更新
        "UpdateDesc":       //更新描述
           "写了也不会看\n所以不写了", // \n\n\n所有更新记录:https://mayishidai.cn/tv/apk/%E6%9B%B4%E6%96%B0%E6%97%A5%E5%BF%97.txt
           "UpdateDownloadUrl":"http:///releases/update.apk" //更新下载地址
    }
}
```
