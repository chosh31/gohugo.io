# hugo
- A Fast and Flexible Static Site Generator built with love in GoLang.
- http://gohugo.io

## getting started
- brew install hugo
- hugo help
- hugo version
- hugo new site quickstart

cd quickstart;\
git init;\
git submodule add https://github.com/budparr/gohugo-theme-ananke.git themes/ananke;\

# Edit your config.toml configuration file
# and add the Ananke theme.
echo 'theme = "ananke"' >> config.toml

hugo new posts/my-first-post.md

netlify - hosting
https://www.netlify.com/