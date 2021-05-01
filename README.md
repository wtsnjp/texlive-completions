# Shell completion functions for TeX Live

This project is work-in-progress. At this point, only completion functions for [Zsh](https://www.zsh.org/) are available. Supported commands are:

- `tlmgr`
- `texdoc`

## Installation (Zsh)

* Clone the repository:

```
git clone git://github.com/wtsnjp/texlive-completions.git
```

* Include the directory in your `$fpath`, for example by adding in `~/.zshrc`:

```
fpath=(path/to/texlive-completions/zsh $fpath)
```

## License

This package is distributed under [the MIT license](./LICENSE).

---

Takuto ASAKURA ([wtsnjp](https://github.com/wtsnjp))
