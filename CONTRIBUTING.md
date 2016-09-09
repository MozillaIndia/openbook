# Contributing to TMIOB

TMIOB is published using [Leanpub](https://leanpub.com/). The content is written using Markdown in English. The repository structure follows the structure of a standard Leanpub book.

## Before you contribute

- **Read the [Leanpub Manual](https://leanpub.com/help/manual)**: This will help you understand how publishing using Leanpub actually works and what syntax you are supposed to follow while writing the book.
- **Be collaborative, for quality's sake**: We are trying to write a book collaboratively, yet maintain a high standard of quality. So, please don't be upset about pointy questions, lengthy revisions and rewrite requests regarding your contribution.
- **Be clear, but not dilute**: Use clear expressions and lucid language, but do not compromise on technical accuracy.
- **Be constructive in criticism**: If you can improve something, voice it. [File an issue](https://github.com/MozillaIndia/openbook/issues). If you find something annoying, try to articulate it, or better, fix it and submit a pull request!

## Repository structure

- The `/manuscript/` directory has the source files. All contributions that need to show up in the book, go here.
- The `/manuscript/Book.txt` lists the files in the order in which they appear in the book.
- Images are stored in the `/manuscript/images/` directory.
- Parts, chapters and sub-(sub-sub-)sections are present in each Markdown file.

## Branch strategy

This repository has 2 main branches:

- **`master`**: This is the default branch, and is used for development. Any changes to the `master` branch trigger a new preview of the book in Leanpub.
- **`publish`**: Once the `master` branch has stable enough content, it is merged to `publish`. As the name suggests, pushing to the `publish` branch triggers a publish on Leanpub, making the changes publicly available in the book.

## Writing a new chapter

If you want to write a new chapter, follow this process:

- Create a new file in the `/manuscript/` folder ending with a `.md` extension.
- Write your content in that file.
- Do _not_ edit the `/manuscript/Book.txt` file. That way, we can do a peer-review of your submission and get it cleaned up before adding it to the book.
- Create pull request to the `master` branch.

## Editing an existing chapter

If you want to edit an existing chapter, simply edit the text and send a PR.

## Version strategy

TODO
