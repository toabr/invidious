<div align="center">
  <img src="assets/invidious-colored-vector.svg" width="48" height="48" alt="Invidious logo">
  <h1>Invidious</h1>

  <h3>An open source alternative front-end to YouTube</h3>

  <a href="https://invidious.io/">Website</a>
  &nbsp;•&nbsp;
  <a href="https://instances.invidious.io/">Instances list</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/faq/">FAQ</a>
  &nbsp;•&nbsp;
  <a href="https://docs.invidious.io/">Documentation</a>
  &nbsp;•&nbsp;
  <a href="#contribute">Contribute</a>
  &nbsp;•&nbsp;
  <a href="https://invidious.io/donate/">Donate</a>
</div></br></br>

## Proxy Companion Version

Theme: [Tsyron/Invidious-Theme](https://github.com/Tsyron/Invidious-Theme)

### Install

[https://docs.invidious.io/companion-installation](https://docs.invidious.io/companion-installation)

```
$ git clone https://github.com/toabr/invidious.git

$ cd invidious
```

**.env**
```
PUBLIC_URL=
COMPANION_KEY=
HMAC_KEY=

DB_NAME=
DB_USER=
DB_PW=
DB_Host=
DB_PORT=
```

**Start the service**
```
$ docker compose up -d
```

### Proxy settings

[https://docs.invidious.io/companion-nginx](https://docs.invidious.io/companion-nginx)

### Update

```
$ docker compose down

$ git pull

$ docker compose up -d --build
```
