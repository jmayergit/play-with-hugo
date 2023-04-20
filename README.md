### Prerequisites

Docker 🐳

### From 0 to 🦸‍♂️

```
docker compose up
```

http://localhost:1313

### Run hugo commands

```
yarn hugo [command]
```

#### How this project was bootstrapped

Guide: https://dev.to/robinvanderknaap/setup-hugo-using-docker-43pm
Bootstrap command: `docker run --rm -v $(pwd):/src klakegg/hugo:0.107.0-ext-alpine new site test`

...plus tard

Quick Start: https://gohugo.io/getting-started/quick-start/
```
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke themes/ananke
echo "theme = 'ananke'" >> config.toml
```