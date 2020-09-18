

###  bannerEntity:首页Banner Json串

>   如果要打开的网页需要同步教务处cookie，可直接在url后面添加openWithJwcCookie=true即可，
    如：http://zhjw.qfnu.edu.cn/jsxsd/grxx/xsxx?openWithJwcCookie=true（如果不明白怎么配置，可以先问我然后再配置）


### show_spalsh_ad

>   是否显示启动页广告 （false不显示，true显示）


### website

>   前端域名配置： 自己服务器：http://app.zhuandian.site/jwc/#/ github代理：https://ydjw.github.io/jwc/#/ 有时候可能会卡，建议两个服务切换下使用

### kxr

> 开学日期,需要设定为第一个星期一


###  splash_img

> 闪屏页图片（不配置在线splash请把“splashImgUrl”参数设置成“”，自动加载bing图片），autoScale：图片是否启用缩放动画，默认true，imgDesc：图片描述介绍，不需要描述，用空字符串占位即可



###  notification_label
> 首页消息滚动黄条（内容长度小于1个字符则首页不显示黄条，有内容则在黄条内滚动消息）


### appSecondFloor

> app首页下拉进入二楼页面配置，showSecondFloor：是否开启二楼入口，secondFloorImg：开启二楼入口后用户下拉可见的图片url，secondFloorUrl：进入二楼后加载的H5页地址