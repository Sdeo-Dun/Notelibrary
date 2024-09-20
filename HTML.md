# html文件的基本语法、方法
- 声明整体
```html
<!DOCTYPE html>
<!-- 声明标签，HTML文档 -->
```
- 声明整体语言、属性、文件属性
```html
<html lang="zh">
<!-- 声明页面的语言 -->
```

*** 
1. 页面属性思绪图
> 声明为HTML5文档 · **[声明整体文件属性](HTML.md "首页")**
>>
>> 完整HTML页面
>>
>> `<html>` 页面中根元素
>>>> 头部元素和可见的标题
>>>>
>>>> `<head>`
>>>>> `<meta charset="utf-8">` 元数据\定义页面数据的编码格式
>>>>>
>>>>> `<title>标题名称</title>` 整个页面的标题
>>>>
>>>> `</head>`
>>>>
>>>> 可见的页面内容、元素
>>>>
>>>> `<body>`
>>>>> `<h1>页面内容的大标题</h1>`
>>>>>
>>>>> `<p>页面内容的一个段落</p>`
>>>>
>>>> `</body>`
>>
>> `</html>`

- 头部标签声明
```html
<head>
    <meta charset="UTF-8">
    <!-- 声明页面的编码 -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- 声明页面的浏览器 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- 声明页面与设备 -->
    <meta name="author" lang="zh" content="DengShaoyu,17681306381,15395507856,qq2412874626">
    <!-- 声明站长 -->
    <meta name="keywords"  lang="zh" content="SYD,shaoyudeng,syd,shaoyudeng.top,MC,我的世界,Minorcerft,游戏,无限世界,优惠,我的世界会员,我的世界模组,MOD,mod,js,综合游戏,游戏,FPS,fps,盒子世界，世界，我的世界高清图,综合游戏网,游戏插件,游戏模组,">
    <!-- 声明搜索关键字 -->
    <meta name="description" lang="zh"  content="综合游戏网,游戏插件,游戏模组,免费游戏,免费DLC,免费插件,免费模组"/>
    <!-- 声明页面描述 -->
    <Meta name="Copyright" Content="本页版权归DengShaoyu所有© All Rights Reserved © ">
    <!--以上是版权 -->
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <!-- 引入logo.iconic图片 -->
    <title>Document</title>
    <!-- 声明页面的主题、标题、题目 -->
</head>
```
- 页面主体使用方法
```html
<body>
<!-- 声明页面的主体 -->
    <div class="main_box">
        <!-- 声明页面的主体盒子 -->
        <div class="main_n_box">
            <!-- 声明页面的主体盒子之中的盒子 -->
            <img src="" alt="logo" title="logo,首标图" width="60px" height="40px">
            <!-- 声明页面的主体图片（logo） -->
        </div>
    </div>
</body>
```
- 页面内容标题
```html
<h1>第壹标题，在页面内容中是最大的标题</h1>
<h2>第贰标题，在页面内容中第二大的标题</h2>
<h3>第叁标题，在页面内容中第三大的标题</h3>
<h4>第肆标题，在页面内容中第四大的标题</h4>
<h5>第伍标题，在页面内容中第五大的标题</h5>
<h6>第陆标题，在页面内容中第六大的标题</h6>
```
- 页面内容段落
```html
<p>第一个段落，是页面内容</p>
```
