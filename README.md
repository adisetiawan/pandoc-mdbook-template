# Pandoc mdbook template

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/adisetiawan/pandoc-mdbook-template/blob/master/LICENSE)

## Description

This repositoy is a cloned version of this [simple pandoc book template](https://github.com/wikiti/pandoc-book-template) with one exception:

> Instead of using pandoc html generation, it use [mdbook](https://github.com/rust-lang/mdBook) to generate nice html from markdown.


## Prerequisite

* [Pandoc](http://pandoc.org)
* [mdbook](https://github.com/rust-lang/mdBook)

## Folder Structure

```
my-book/         # Root directory.
|- ebook/        # Folder used to store builded (output) files.
|- ebook/        # Folder used to store mdbook output
|- src/chapters/     # Markdowns files; one for each chapter.
|- src/chapters/images/       # Images folder.
|                      |- cover.png  # Cover page for epub.
|- metadata.yml  # Metadata content (title, author...).
|- Makefile      # Makefile used for building our books.
|- book.toml     # mdbook configuration
```

## How to use

Please check [simple pandoc book template](https://github.com/wikiti/pandoc-book-template) readme, for instuction how to use. I've added extra command to build mdbook html files.

`make web` or you can simply use `mdbook build`

## References
- [simple pandoc book template](https://github.com/wikiti/pandoc-book-template)
- [Pandoc](http://pandoc.org/)
- [Pandoc Manual](http://pandoc.org/MANUAL.html)
- [mdBook](https://github.com/rust-lang/mdBook)
- [Wikipedia: Markdown](http://wikipedia.org/wiki/Markdown)
