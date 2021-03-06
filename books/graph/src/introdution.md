## 安装

从这里下载[GitHub Releases page](https://github.com/rust-lang/mdBook/releases)

## 命令行工具

mdbook命令行工具用于创建和构建图书。安装mdbook后，可以在终端执行mdbook help命令查看可用的命令。

下面的部分提供了关于不同命令的深入信息。

    mdbook init <directory> — Creates a new book with minimal boilerplate to start with.
    mdbook build — Renders the book.
    mdbook watch — Rebuilds the book any time a source file changes.
    mdbook serve — Runs a web server to view the book, and rebuilds on changes.
    mdbook test — Tests Rust code samples.
    mdbook clean — Deletes the rendered output.
    mdbook completions — Support for shell auto-completion.
    
## 配置
```yaml
[output.html]
# theme = "my-theme"
default-theme = "Coal"
# preferred-dark-theme = "navy"
# curly-quotes = true
# mathjax-support = false
# copy-fonts = true
# # additional-css = ["custom.css", "custom2.css"]v
# # additional-js = ["custom.js"]
# no-section-label = false
# git-repository-url = "https://github.com/rust-lang/mdBook"
# git-repository-icon = "fa-github"
# edit-url-template = "https://github.com/rust-lang/mdBook/edit/master/guide/{path}"
# site-url = "/example-book/"
# cname = "myproject.rs"
# input-404 = "introdution.md"
```

## 目录的创建
```yaml
# Summary

[Introduction](README.md)

# User Guide

- [Installation](guide/installation.md)
- [Reading Books](guide/reading.md)
- [Creating a Book](guide/creating.md)

# Reference Guide

- [Command Line Tool](cli/README.md)
    - [init](cli/init.md)
    - [build](cli/build.md)
    - [watch](cli/watch.md)
    - [serve](cli/serve.md)
    - [test](cli/test.md)
    - [clean](cli/clean.md)
    - [completions](cli/completions.md)
- [Format](format/README.md)
    - [SUMMARY.md](format/summary.md)
        - [Draft chapter]()
    - [Configuration](format/configuration/README.md)
        - [General](format/configuration/general.md)
        - [Preprocessors](format/configuration/preprocessors.md)
        - [Renderers](format/configuration/renderers.md)
        - [Environment Variables](format/configuration/environment-variables.md)
    - [Theme](format/theme/README.md)
        - [index.hbs](format/theme/index-hbs.md)
        - [Syntax highlighting](format/theme/syntax-highlighting.md)
        - [Editor](format/theme/editor.md)
    - [MathJax Support](format/mathjax.md)
    - [mdBook-specific features](format/mdbook.md)
    - [Markdown](format/markdown.md)
- [Continuous Integration](continuous-integration.md)
- [For Developers](for_developers/README.md)
    - [Preprocessors](for_developers/preprocessors.md)
    - [Alternative Backends](for_developers/backends.md)

-----------

[Contributors](misc/contributors.md)

```
详细说明请参考[说明文档](https://rust-lang.github.io/mdBook/index.html)
