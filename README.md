baseURL = 'https://kureisersen.github.io/'
languageCode = 'en-us'
title = 'KureiSersen site'
theme = 'paper'
paginate = 5
hasCJKLanguage = true

[params]
avatar = 'qaz1006ing@gmail.com'
name = 'Edwin.Liang'
bio = "Whether you're passing by occasionally or visiting frequently, I sincerely appreciate your support and attention. I hope my blog can bring you inspiration and joy, as we grow together in this ocean of knowledge!"
github = 'KureiSersen'
math = true

[menu]
  [[menu.main]]
    identifier = "about"
    url = "/about/"
    weight = 10
  [[menu.main]]
    identifier = "contact"
    url = "/contact/"
    weight = 10

[taxonomies]
tag = "tags"

[markup.goldmark.renderer]
  unsafe = true

[services]
  [services.disqus]
    shortname = 'https-kureisersen-github-io'
