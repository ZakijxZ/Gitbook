# 简单书写
## 在当前文件夹下创建一本书
```bash
gitbook init
```

> #### Hint::注意
>
> 默认生成`README.md`和 `SUMMARY.md`两个文件, `README.md`是对书籍的简单介绍, `SUMMARY.md`是书籍的目录结构

## 目录结构

对`SUMMARY.md`进行排版，这里建议将前后顺序通过手动命名的方式加入，不建议使用自动标号

- 可复制创建同级标题
- 缩进并`-空格`创建子标题
- 以`[TitleName](FileName.md)`的关系链接目录和文件
- 在同级文件夹下创建对应的`FileName.md`
- 参照`Markdown`和`HTML`的语法写作
- 图片链接、视频链接参考`Markdown`和`HTML`

> `Markdown`:[点我跳转](https://blog.csdn.net/qq_39800978/article/details/101763497)
>
> `HTML`:[点我跳转](https://blog.csdn.net/qq_39800978/article/details/101763497)

## 编译并本地预览

```bash
gitbook serve # 实际是编译和本地预览的结合
# gitbook build仅仅是生成本地的静态文件
```