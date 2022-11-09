# Wiki fzf search script with preview

This is initially stolen from the fzf manpage and modified.

## Requirements

* fzf
* ripgrep
* nvim
* bat

## Installation

Clone the repository
```
git clone https://github.com/juli9797/wikisearch
```
Change permissions
```
chmod +x wikisearch/wiki
```
Symlink to searchpath
```
ln -s wikisearch/wiki ~/bin/wiki
```

## Usage

Navigate to your wikis root directory and run
```
wiki md
```
to fuzy search all files with `.md` extensions in all folders and subfolders.
Each search result can be previewed in the preview screen.
To open the file in nvim press enter.

