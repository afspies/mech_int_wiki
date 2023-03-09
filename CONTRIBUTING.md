# Contributing to the Mechanistic Interpretability Wiki
As the wiki is made through [gitbooks](https://afspies.gitbook.io/mechanistic-interpretability-wiki/), new content can be added to the wiki either through gitbook.com (request access from [afspies@imperial.ac.uk](mailto:afspies@imperial.ac.uk) or through github via pull-requests using markdown files directly.

Contributions to existing pages or addition of new pages is very welcome! Contributors will be accredited on the published wiki too.

## Links
You need to use relative paths based on the current file location, might need a couple of ```../../../``` before finding the file you want to link to.

## Assets
We recommend adding an assets folder inside the directory where you need it. You can then access your assets from your markdown file by doing ```./assets/my-image.png.```

## Publishing
When you are done with your changes, you will need to make a PR which once merged it will take a few minutes before your changes appears on docs.devland.is.

### Gitbooks Special Behaviour
See the [gitbooks docs](https://docs.gitbook.com/getting-started/publishing) for more details. The following two snippets might be particularly useful:

* If you want to have a different title in the navigation than on the page itself, you can do so by adding a html comment like this to the top of your file:
```<!-- gitbook-navigation: "Navigation Title" -->```
* For some reason, if you don't want your markdown file to be part of the main table of contents file, but still included inside the GitBook, you can add the following html comment ```<!-- gitbook-ignore -->``` as the first line of the file. 

*Credits: these guidelines are based on those of [island.is](https://github.com/island-is/island.is/blob/main/handbook/repository/gitbook-contribute.md).*
