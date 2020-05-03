# The Crypto Masters Website

This is the official website for The Crypto Masters Podcast


## How to run locally

First, you need to install jekyll and the dependencies of { Personal } by running:

```shell
./scripts/install
```

Then, you can build and serve your website by simply running:

```shell
./scripts/serve-production
```

To serve across lan (requires su to forward the port 4000 over lan):

```shell
./scripts/serve-lan-production
```

### Docker

Run using Docker:

```
docker run --rm -it -p 4000:4000 -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll serve --watch --host "0.0.0.0" --config _config.yml,_config.dev.yml
```

Run using Docker with Docker Compose:
```
docker-compose up
```

## OSS used

  1. [Grayscale](http://startbootstrap.com/template-overviews/grayscale/)
  2. [hammer.js](https://hammerjs.github.io/)
  3. [highlightjs](https://highlightjs.org/)
  4. [RRSSB](https://github.com/kni-labs/rrssb)
  5. [timeline](https://github.com/kirbyt/timeline-jekyll-theme)
  6. [typed.js](https://github.com/mattboldt/typed.js/)


