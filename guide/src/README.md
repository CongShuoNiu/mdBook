# K8s 学习记录

## Kubernetes 基本概念与组件

Kubernetes（简称 K8S） 的出现是容器化技术发展的必然结果，容器化是应用程序级别的虚拟化，运行单个内核上有多个独立的用户空间实例，这些实例就是容器；容器提供了将应用程序的代码、运行时、系统工具、系统库和配置打包到一个实例中的标准方法，而且容器是共享一个内核的；由于容器技术的兴起，导致大量的容器应用出现，所以就出现了一些用来支持应用程序容器化部署和组织的容器编排技术，一些流行的开源容器编排工具有 Docker Swarm、Kubernetes 等，但是在发展过程中 Kubernetes 现在已经成为了容器编排领域事实上的一个标准了。

**mdBook** is a command line tool to create books with Markdown.
It is ideal for creating product or API documentation, tutorials, course materials or anything that requires a clean,
easily navigable and customizable presentation.

* Lightweight [Markdown] syntax helps you focus more on your content
* Integrated [search] support
* Color [syntax highlighting] for code blocks for many different languages
* [Theme] files allow customizing the formatting of the output
* [Preprocessors] can provide extensions for custom syntax and modifying content
* [Backends] can render the output to multiple formats
* Written in [Rust] for speed, safety, and simplicity
* Automated testing of [Rust code samples]

This guide is an example of what mdBook produces.
mdBook is used by the Rust programming language project, and [The Rust Programming Language][trpl] book is another fine example of mdBook in action.

[Markdown]: format/markdown.md
[search]: guide/reading.md#search
[syntax highlighting]: format/theme/syntax-highlighting.md
[theme]: format/theme/index.html
[preprocessors]: format/configuration/preprocessors.md
[backends]: format/configuration/renderers.md
[Rust]: https://www.rust-lang.org/
[trpl]: https://doc.rust-lang.org/book/
[Rust code samples]: cli/test.md

## Contributing

mdBook is free and open source. You can find the source code on
[GitHub](https://github.com/rust-lang/mdBook) and issues and feature requests can be posted on
the [GitHub issue tracker](https://github.com/rust-lang/mdBook/issues). mdBook relies on the community to fix bugs and
add features: if you'd like to contribute, please read
the [CONTRIBUTING](https://github.com/rust-lang/mdBook/blob/master/CONTRIBUTING.md) guide and consider opening
a [pull request](https://github.com/rust-lang/mdBook/pulls).

## License

The mdBook source and documentation are released under
the [Mozilla Public License v2.0](https://www.mozilla.org/MPL/2.0/).
