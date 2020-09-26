# 插件安装

## 给Book加插件

- 新建一个`book.json`文件
- 去[NPM](https://www.npmjs.com/)官网找自己想要的插件并按照要求配置的编写
- 执行`gitbook install`进行安装

## 常用的三款插件

> [gitbook-plugin-donate(打赏按钮)]( https://www.npmjs.com/package/gitbook-plugin-donate)
>
> [gitbook-plugin-github-buttons(GitHub按钮)](https://www.npmjs.com/package/gitbook-plugin-github-buttons) 
>
> [gitbook-plugin-edit-link(GitHub编辑按钮)](https://www.npmjs.com/package/gitbook-plugin-edit-link)
>
> [gitbook-plugin-callouts(标注)](https://www.npmjs.com/package/gitbook-plugin-callouts)
>
> - 用法
>
> ```markdown
> > #### type::title
> >
> > cotent
> ```
>
> - 具体关键字
>
> ```markdown
> > #### Info::Info
> > #### Note::Note
> > #### Tag::Tag
> > #### Comment::Comment
> > #### Hint::Hint
> > #### Success::Success
> > #### Warning::Warning
> > #### Caution::Caution
> > #### Danger::Danger
> > #### Quote::Quote
> ```
>
> - 具体样式
>
> > #### Info::信息
> >
> > 你好
>
> 断
>
> > #### Note::Note
> >
> > 注意
>
> 断
>
> > #### Tag::Tag
>
> 断
>
> > #### Comment::Comment
>
> 断
>
> > #### Hint::Hint
>
> 断
>
> > #### Success::Success
>
> 断
>
> > #### Warning::Warning
>
> 断
>
> > #### Caution::Caution
>
> 断
>
> > #### Danger::危险
>
> 断
>
> > #### Quote::引用
> >
> > 你好
>
> 断
>
> [gitbook-plugin-multipart(分多部分)](https://www.npmjs.com/package/gitbook-plugin-multipart)




## 配置实例

以下是我的一本书的配置，可以

```json

{
    "title": "Gitbook简要说明",
    "description": "用于介绍Gitbook的简单使用",
    "author": "Zakijxz",
    "language": "zh-hans",
    "root": ".",
    "plugins": ["donate",
        "github-buttons",
        "edit-link",
        "toolbar-button",
        "theme-comscore",
        "anchors",
        "-lunr",
        "-search",
        "search-plus",
        "disqus",
        "-highlight",
        "prism",
        "prism-themes",
        "github-buttons",
        "splitter",
        "-sharing",
        "sharing-plus",
        "tbfed-pagefooter",
        "expandable-chapters-small",
        "copy-code-button",
        "callouts",
        "lightbox",
        "pageview-count",
        "chapter-fold",
        "expandable-chapters-small",
        "anchor-navigation-ex",
        "multipart"],
    "pluginsConfig": {
        "donate": {
            "wechat": "https://lotzxj.gitee.io/hjtech/images/wechatpay.png",
            "alipay": "https://lotzxj.gitee.io/hjtech/images/alipay.jpg",
            "title": "坚持原创，您的支持是我继续努力的源泉！",
            "button": "Donate",
            "alipayText": "支付宝",
            "wechatText": "微信"
        },
        "github-buttons": {
            "buttons": [{
              "user": "ZakijxZ",
              "repo": "ZakijxZ.github.io",
              "type": "star",
              "size": "small"
            }
            ]
        },
        "edit-link": {
            "base": "需要具体化",
            "label": "编辑"
        },
        "toolbar-button": {
            "url": "待修改",
            "icon": "fa-file-pdf-o",
            "label": "下载PDF"
        },
        "callouts": {
            "showTypeInHeader": false
        },
        "theme-default": {
            "showLevel": false
        },
        "disqus": {
            "shortName": "lotz"      //需要去注册
        },
          "prism": {
            "css": [
              "prism-themes/themes/prism-atom-dark.css"     //代码块的主题
            ]
        },
        "sharing": {
            "douban": false,
            "facebook": false,
            "google": false,
            "hatenaBookmark": false,
            "instapaper": false,
            "line": false,
            "linkedin": true,
            "messenger": false,
            "pocket": false,
            "qq": true,
            "qzone": false,
            "stumbleupon": false,
            "twitter": false,
            "viber": false,
            "vk": false,
            "weibo": true,
            "whatsapp": false,
            "all": [
              "douban",
              "facebook",
              "google",
              "instapaper",
              "line",
              "linkedin",
              "messenger",
              "pocket",
              "qq",
              "qzone",
              "stumbleupon",
              "twitter",
              "viber",
              "vk",
              "weibo",
              "whatsapp"
            ]
        },
        "tbfed-pagefooter": {
            "copyright": "<a href='https://zakijxz.github.io/'>Z先森</a>",
            "modify_label": "最后更新：",
            "modify_format": "YYYY-MM-DD HH:mm:ss"
        },
        "anchor-navigation-ex":{
            "showLevel":false,
            "showGoTop":true
        }
    }
}
```

