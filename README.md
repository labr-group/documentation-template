# Documentation Template

A simple guide on documenting your repository

## Overview

Documentation for your repository is incredibly important because it allows future and current developers to better understand your code.  
We keep our documentation in a `docs/` folder at the very base of our repo. This allows us to host our documentation via GitHub pages when our repositories become public (if they aren't already).  

## Markdown

Our documentation uses something called **Markdown**. Markdown allows us to quickly and easily style our documentation. What you're reading right now is styled using Markdown!  
Not familiar with Markdown? Check out [this cheatsheet](markdown-cheat-sheet.md)

## Folder Overview

All documentation should go in a `docs` folder in your repo. Within that docs folder is a `static` folder containing all your static content (such as images).

```js
your-repo/
        docs/
                static/
                    /* all static content goes here, such as images */
                index.md // this is the main entrypoint for your documentation
                content-1.md // some file with documentation
                content-2.md // some file with documentation
        /* all of your other code is in the main folder of your repo */
```

## index.md

In your `docs` folder, you should make an [index.md](docs/index.md) file. This is the starting point of your documentation. Make sure you link all of your other markdown files in the index.md file, to make it easier for readers to navigate!
