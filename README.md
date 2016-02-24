## Netflix OSS on Heroku Demo: Zuul Proxy Server

This project demonstrates the use of Netflix OSS with Spring Cloud on Heroku. It defines a Zuul server
that proxies request to backing services run at httpbin.org.

### Quickstart

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

### Local development

```
$ git clone https://github.com/kissaten/heroku-zuul-server-demo
$ cd heroku-zuul-server-demo
$ heroku create
$ git push heroku master
$ heroku open index.html
```

### License

MIT