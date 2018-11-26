+++
title = "👻Lambda Ghost"
date = 2017-07-28T10:41:09+09:00
draft = false

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["AWS", "AWS Lambda"]

# Project summary to display on homepage.
summary = "Serverless Web Scraping Template by PhatomJS"

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional external URL for project (replaces project detail page).
external_link = ""

# Links (optional).
url_pdf = ""
url_code = "https://github.com/mesh1nek0x0/lambda-ghost"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
## 概要
node-lambdaを利用したサーバレスでWeb Scrapingを行えるサンプル。
その他、ヘッドレスブウラウザに比べて書き方は多少煩雑ですが、軽量で安定しています。

APIが公開されていないデータでも、定期的に実行してSlackへ通知...といったことも実現できます。

※PhontomJSはアーカイブされたため、現在は利用を推奨していません。Headless Chromeを使いましょう。
