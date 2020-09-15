# 简单书写
## 在当前文件夹下创建一本书
```bash
gitbook init
```

>注：会生成`README.md`和 `SUMMARY.md`两个文件, `README.md`是对书籍的简单介绍, `SUMMARY.md`是书籍的目录结构

## 编译并用本地端口预览

```bash
gitbook serve
# gitbook build仅仅是生成本地的静态文件
```

## 对`SUMMARY.md`目录进行构造

- 可复制则创建同级标题
- 缩进并`-空格`创建子标题
- `[TitleName](FileName.md)`这样的关系链接目录和文件
- 在同级文件下创建对应的`FileName.md`
- 参照`Markdown`和`HTML`的语法写作
- 图片链接、视频链接参考`Markdown`和`HTML`

> `Markdown`:https://blog.csdn.net/qq_39800978/article/details/101763497
>
> `HTML`:https://blog.csdn.net/qq_39800978/article/details/101763497