# Publish your Obsidian Notes

MkDocs template [![Built with Material for MkDocs](https://img.shields.io/badge/Material_for_MkDocs-526CFE?style=for-the-badge&logo=MaterialForMkDocs&logoColor=white)](https://squidfunk.github.io/mkdocs-material/)

Would you like to take _some_ of your notes in [Obsidian](https://obsidian.md/) and make it public?

This template gives you an easy (and automated) way to publish your Obsidian notes (or blog!) on your Github pages.

With this template, you get these **out-of-the-box**:

-   an awesome website based on Material theme, complete with a search bar (Checkout this template repo published [here](https://jobindjohn.github.io/obsidian-publish-mkdocs/))
    ![](2021-11-22-22-49-26.png)
-   get the Obsidian/Roam style `[[wikilinks]]` from your vault in your published notes
-   Toggle between light and dark mode
-   Blog folder

## Quick start

1. Create a **new github repository using this template**. Click the green button at the top or use [this link](https://github.com/jobindjohn/obsidian-publish-mkdocs/generate).

![](2021-11-22-22-54-02.png)

2.  **Give a name** to your repository. By default your notes will be published at `<https://username.github.io/repo-name/>`
    -   Copy only the `main` branch while creating the repo from the template
3.  **Clone** the repository you generated **into your Obsidian folder/vault.**
4.  **Move your notes** that you would like to make public to the `repo-name/docs` folder.
    -   Easiest way to do this would be using drag and drop within Obsidian
5.  Commit and **push** the changes. Github actions will take care of the rest, publishing your notes using [MkDocs](https://www.mkdocs.org/), with the [Material theme](https://squidfunk.github.io/mkdocs-material/).
6.  Go to `Settings > Pages` and select the select the **Source** as your `gh-pages` branch.

![](2021-11-22-22-52-49.png)

**Not working for you?** Open an [issue](https://github.com/jobindjohn/obsidian-publish-mkdocs/issues/new/choose) and let me know what went wrong.

## Configuring your website

### How do I arrange notes as sections and pages?

By default, the sections and pages will follow the folder structure within `/docs`. The folders and sub-folders will show up as sections. Try not to have white spaces in your folder and file names, as these will be converted to HTML links. The webpage heading will be the same as the first-level heading in the markdown note.

-   If you would like to arrange the pages manually, then use the `nav` option in the `mkdocs.yml` [configuration file](https://www.mkdocs.org/#adding-pages) at the root of this repo to set custom page navigation.
    -   For example, see the setup for [the Blue Book](https://lyz-code.github.io/blue-book/) at [github](https://github.com/lyz-code/blue-book/blob/master/mkdocs.yml). Managing each page using `nav` can become cumbersome as the number of notes increase though!
-   The Materials theme provides multiple options to arrange [sections](https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/#navigation-sections), use [navigation tabs](https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/#navigation-tabs), and many other helpful [navigation setups](https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/)

## Alternatives

-   [binyamin/eleventy-garden: :seedling: A starter site for building a mind garden with eleventy](https://github.com/binyamin/eleventy-garden)
-   [datopian/obsidian-flowershow](https://github.com/datopian/obsidian-flowershow): plugin for publishing with flowershow direct from your obsidian vault.
-   [kmaasrud/oboe](https://github.com/kmaasrud/oboe): tool to convert an Obsidian vault into a static directory of HTML files.
-   [Jackiexiao/foam-mkdocs-template](https://github.com/Jackiexiao/foam-mkdocs-template): template for Obsidian/Foam using mkdocs/mkdocs-material/mkdocs-roamlinks-plugin
-   [foambubble/foam-template](https://github.com/foambubble/foam-template): Foam workpace template
-   [ObsidianPublisher/obsidian-mkdocs-publisher-template](https://github.com/ObsidianPublisher/obsidian-mkdocs-publisher-template): Obsidian Mkdocs Publisher, a free obsidian publish alternative throught Mkdocs
-   [KosmosisDire/obsidian-webpage-export](https://github.com/KosmosisDire/obsidian-webpage-export): Webpage HTML Export lets you export single files or whole vaults as HTML websites or documents. It is similar to publish, but you get direct access to the exported HTML.
-   [Enveloppe/obsidian-enveloppe: publish your notes on a GitHub repository from Obsidian Vault](https://github.com/Enveloppe/obsidian-enveloppe)

## Other interesting projects

-   [mathieudutour/gatsby-digital-garden: digital garden with Gatsby](https://github.com/mathieudutour/gatsby-digital-garden)
-   [TuanManhCao/digital-garden: Free Obisidian Publish alternative](https://github.com/TuanManhCao/digital-garden)

```
rsync -avh --delete "/Users/karamfil/Library/Mobile Documents/iCloud~md~obsidian/Documents/Personal/Vim/" ./docs/
```

https://karamfil.github.io/course-vim
