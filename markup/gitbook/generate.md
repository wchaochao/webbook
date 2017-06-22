# 生成

gitbook可生成为静态网站，pdf, epub, mobi等多种格式

## 生成静态网站

```cmd
gitbook build ./ ./output
```

## 生成pdf, epub, mobi

依赖：ebook-convert

```cmd
gitbook pdf ./ ./mybook.pdf

gitbook epub ./ ./mybook.epub

gitbook epub ./ ./mybook.mobi
```