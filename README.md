# Rust Cookbook 中文版

[![Build Status travis]][travis]
[![LICENSE-MIT](https://img.shields.io/badge/license-MIT-green)](https://raw.githubusercontent.com/rust-lang-cn/rust-cookbook-cn/master/LICENSE-MIT)
[![LICENSE-APACHE](https://img.shields.io/badge/license-Apache%202-blue)](https://raw.githubusercontent.com/rust-lang-cn/rust-cookbook-cn/master/LICENSE-APACHE)
[![GitHub last commit](https://img.shields.io/github/last-commit/rust-lang-cn/rust-by-example-cn?color=gold)](https://github.com/rust-lang-cn/rust-cookbook-cn/commits/master)
[![GitHub contributors](https://img.shields.io/github/contributors/rust-lang-cn/rust-by-example-cn?color=pink)](https://github.com/rust-lang-cn/rust-cookbook-cn/graphs/contributors)
![Locatized 100%](https://img.shields.io/badge/localized-100%25-purple)
[![rustwiki.org](https://img.shields.io/website?up_message=rustwiki.org&url=https%3A%2F%2Frustwiki.org)](https://rustwiki.org)

[Build Status travis]: https://api.travis-ci.com/rust-lang-cn/rust-cookbook-cn.svg?branch=master
[travis]: https://travis-ci.com/rust-lang-cn/rust-cookbook-cn

> Chinese translation of the [Rust Cookbook][rust-cookbook].
>
> 中文译注：
>
> 1. 《Rust Cookbook 中文版》已经有由 [zzy] 翻译[完整的版本][full-version]，故本仓库不再单独翻译，而直接采用 zzy 翻译的内容，若对翻译内容改正和完善，可到 [zzy 维护的仓库上提出和 PR][full-version]。在此，*rust-lang-cn* 对译者表示衷心的感谢，您的翻译对我们使用中文资料学习和了解 Rust 起到极大作用。
> *rust-lang-cn* 只会对格式和部分内容进行微调，其余内容我们建议大家都反馈到原仓库。中文翻译版（位于 *src* 目录）的版权我们也遵循原仓库的[MIT] 和 [Apache 2.0] 双协议，本仓库下的英文版内容以及其他文件均保持 Rust 官方的原有授权协议（即 CC0 协议，公有领域作品）。
> 3. 我们怀着朴素的理想，努力将 Rust 资源翻译成中文，让中文世界中拥有更多官方的 Rust 资源，本组织也欢迎 Rust 爱好者加入进来，成为我们组织的贡献者以及拥有者。

[zzy]: https://github.com/zzy
[full-version]: https://github.com/zzy/rust-cookbook-zh-cn

**[Read it here]**.

This _Rust Cookbook_ is a collection of simple [Rust] examples that
demonstrate good practices to accomplish common programming tasks,
using the crates of the Rust ecosystem.

These examples are complete, and suitable for copying directly into
new cargo projects. They are tested and guaranteed to work.

## Read it offline

If you'd like to read it locally:

```bash
$ git clone https://github.com/rust-lang-nursery/rust-cookbook
$ cd rust-cookbook
$ cargo install mdbook --vers "0.4.5"
$ mdbook serve --open
```

The output can also be opened from the `book` subdirectory in your web browser.

```bash
$ xdg-open ./book/index.html # linux
$ start .\book\index.html    # windows
$ open ./book/index.html     # mac
```

[Read it here]: https://rust-lang-nursery.github.io/rust-cookbook
[Rust]: https://www.rust-lang.org/

## Contributing

This project is intended to be easy for new [Rust] programmers to
contribute to, and an easy way to get involved with the Rust
community. It needs and welcomes help.

For details see [CONTRIBUTING.md] on GitHub.

[CONTRIBUTING.md]: https://github.com/rust-lang-nursery/rust-cookbook/blob/master/CONTRIBUTING.md

## License [![CC0-badge]][CC0-deed]

Rust Cookbook is licensed under Creative Commons Zero v1.0 Universal License
([LICENSE-CC0](LICENSE-CC0) or https://creativecommons.org/publicdomain/zero/1.0/legalcode)

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in Rust Cookbook by you, as defined in the CC0-1.0 license, shall be
[dedicated to the public domain][CC0-deed] and licensed as above, without any additional
terms or conditions.

[CC0-deed]: https://creativecommons.org/publicdomain/zero/1.0/deed.en
[CC0-badge]: https://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg
