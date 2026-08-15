## timnavigate.com

This repository contains the sources of [www.timnavigate.com](https://www.timnavigate.com)

When `CNAME` and `A` DNS records has been excluded from domain registry, then URL for drafts and A/B testing is [timnavigate.github.io](https://timnavigate.github.io)

##### local dependencies:
- gem 3.5.4
- rbenv 1.2.0
- ruby 3.3.0
- bundler 2.5.4
- jekyll 3.9.4

more information: [jekyll installation](https://jekyllrb.com/docs/installation/) 

##### bash:
```bash
$ bundle exec jekyll build
$ bundle exec jekyll serve --drafts
```
