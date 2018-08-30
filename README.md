# athena

A clean and readable Hugo theme (port of https://github.com/broccolini/athena).

[![screenshot](https://raw.githubusercontent.com/mtn/athena-hugo-theme/master/images/screenshot.png)](https://raw.githubusercontent.com/mtn/athena-hugo-theme/master/images/screenshot.png)

It's responsive by default, and can be quickly be set up with minimal configuration.

## Getting Started

Clone the theme into themes/athena:

    git clone https://github.com/mtn/athena-hugo-theme.git themes/athena

Then, you can view a live-reloading server with `hugo server -w`.

## Configuration

There aren't a ton of configuration options. This `config.toml` roughly summarizes configuration. If you want to add something, feel free to make proposals and/or pull requests.

```
baseURL = "http://example.org/"
languageCode = "en-us"
title = "Athena Hugo Theme"
theme = "athena"

[params]
description = "a-description"
dateform = "Jan 2, 2006"
disable_next_prev = true
github_repo = "your-repo"
github_username = "your-username"
```

## Final Notes

Credit for the design goes to [broccolini](https://github.com/broccolini). I really liked this theme, and wanted to bring it to a broader audience :)

This was hacked together rather quickly, so there might be issues!

## License

Licensed under the MIT License. See the [LICENSE](https://github.com/mtn/athena-hugo-theme/blob/master/LICENSE.md) file for more details.
