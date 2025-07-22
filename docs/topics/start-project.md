# Start Project

The objective of this project is document the best way to _document_ projects. These projects could be a software project or any kind of project technical that you want.

All documentation of this project is already published in [fluchini.github.io](https://fluchini.github.io/alna-docs/) :simple-github:

## Alna Docs

This documentation is built using Markdown, MkDocs and Material. For more information visit:

* Markdown: [markdownguide.org](https://www.markdownguide.org/)
* MkDocs: [mkdocs.org](https://mkdocs.org)
* Material: [squidfunk.github.io](https://squidfunk.github.io/mkdocs-material/)

## Start Project.

1. Clone Git: `git clone https://github.com/fluchini/alna-docs.git`
2. Go to the project folder.
3. Install MkDocs: `pip install mkdocs`
4. Run the command: `mkdocs serve -a localhost:7101`
5. Go to page: `http://127.0.0.1:7101/`

## Compile and Serve Docs

* `mkdocs build` - Package the files in a folder called `site` for publication.
* `mkdocs serve` - Start a _live-loading_ server to check and edit the documentation.
* `mkdocs help` - Show MkDocs options.

## Layout of Project

    mkdocs.yml       # Configuration file.
    docs/
        overview.md  # Main page (home).
        ...          # Others Markdown pages, images and files.
