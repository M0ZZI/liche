# liche

[![Circle CI](https://img.shields.io/circleci/project/github/raviqqe/liche.svg?style=flat-square)](https://circleci.com/gh/raviqqe/liche)
[![Go Report Card](https://goreportcard.com/badge/github.com/raviqqe/liche?style=flat-square)](https://goreportcard.com/report/github.com/raviqqe/liche)
[![License](https://img.shields.io/github/license/raviqqe/liche.svg?style=flat-square)](LICENSE)

[![asciicast](https://asciinema.org/a/148110.png)](https://asciinema.org/a/148110)

`liche` is a command to check links in Markdown and HTML files.
It checks all `a` and `img` tags in specified files.

## Installation

```sh
go get -u github.com/raviqqe/liche
```

## Usage

```sh
liche file.md
liche file1.md file2.md
```

## Supported properties

- HTML tags: `a`, `img`
- HTML attributes: `href`, `src`
- Schemes: `http`, `https`

## License

[MIT](LICENSE)
