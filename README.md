# googoraa-hugo-theme

Theme used in Googoraa Hugo Blog (excluding blog post)

## Set Up:

1. create new hugo site
2. clone this repo into theme directory of your new hugo site
3. in cofig.toml copy & paste:

```
BaseURL = "https://googoraa.github.io/"
languageCode = "en-us"
title = "Googoraa"
theme = "googoraa-hugo-theme"
paginate = 20
disqusShortname = "googoraa"

[markup.goldmark.renderer]
    unsafe= true

[params]
    description = "A Hubby Blog"
    gravatar = "76070efc166f53a9ca25f8ff7b5ccd5d"
    # Google Analytics 4
    googleAnalyticsID = "G-GR2RY1GHZE"
```

## image Note:

smartphone screenshot style image shortcode: must add ``smartphone-screenshot` to set size

- see post: https://googoraa.github.io/linux/what-is-torrent/

```
{{< imgWCap `imagename.extension` `image atl text` `image cap` `smartphone-screenshot` >}}
```
