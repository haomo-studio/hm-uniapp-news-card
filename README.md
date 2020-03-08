> 官网: [https://haomo-tech.com](https://haomo-tech.com)

> 作者: 毫末科技

> 邮箱: hxg@haomo-studio.com

## 技术支持

毫末科技将长期迭代本组件。需要技术支持，请进钉钉群：

<img style="width:150px" src="http://downloads.haomo-tech.com/%E6%AF%AB%E6%9C%ABuniapp%E7%BB%84%E4%BB%B6%E6%8A%80%E6%9C%AF%E6%94%AF%E6%8C%81.jpg">

## 概述

毫末uni-app新闻卡片组件。支持H5/小程序(微信、支付宝、头条、百度、QQ)/App；组件可自适应各种屏幕大小的手机。

本组件库提供了以下功能：

* xxx

效果预览：http://uniapp.haomo-tech.com

## 使用

在script中引用：

```javascript
import HmNewsCard from '@/components/hm-news-card/index.vue'
export default {
    components: {HmNewsCard}
}
```

在template中使用：

```html
```

详细用法请见[组件Storyboard](http://)

## 属性说明

| 属性名    | 类型    | 默认值 | 说明                                                                       |
|-----------|---------|--------|----------------------------------------------------------------------------|
| title     | String  | -      | 标题文字                                                                   |
| extra     | String  | -      | 标题额外信息                                                               |
| note      | String  | -      | 底部信息                                                                   |
| thumbnail | String  | -      | 标题左侧缩略图                                                             |
| mode      | String  | basic  | 卡片模式 ，可选值， basic：基础卡片 ；style ：图文卡片 ； title ：标题卡片 |
| is-full   | Boolean | false  | 卡片内容是否通栏，为true时将去除padding值                                  |
| is-shadow | Boolean | false  | 卡片内容是否开启阴影                                                       |

## 事件说明

| 事件称名 | 事件说明           | 返回参数 |
|----------|--------------------|----------|
| @click   | 点击 Card 触发事件 | -        |

## 更新日志

### 0.0.1(2020-03-07)

* 实现xxx功能
* 修复xxx Bug
* 完善xxx功能