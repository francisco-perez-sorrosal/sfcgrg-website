# San Francisco Cognitive Science Reading Group Website Project

Holds an [mdBook](https://github.com/rust-lang/mdBook) project for creating the github pages that contain  documentation related to the reading group

[![Manual](https://img.shields.io/badge/book-master-blue.svg)](https://francisco-perez-sorrosal.github.io/sfcgrg-website/)

## Author instructions

**Note:** You must have access to this github project.

### Modify and existing page content

Directly modify the coresponding markdown files in the `sfcsrg-pages/src` directory.

### Add a new section

1. Add the new markdown file with the new content.
2. Add the new section in the bookDirectly modify the coresponding markdown files `sfcsrg-pages/src/SUMMARY.md` file.

## Dev instructions

Use this only if you want to work directly with the contents through the `mdBook` project.

### Install Rust/mdBook

Refer to this:

1. [Install Rust and Cargo (Rust's package manager)](https://doc.rust-lang.org/cargo/getting-started/installation.html)
2. [Install mdBook](https://rust-lang.github.io/mdBook/guide/installation.html)

Then:

```sh
cd sfcsrg-pages
mdbook build . --open
```

This will create the static directory for the contents under the `book` directory and will open a webpage in your browser showing the contents. Finally, modify the contents under the markdown files in the `src` directory by following the [Author Instructions](#author_instructions) section.