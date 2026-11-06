<p align="center">
  <img src="https://raw.githubusercontent.com/kosatka-cms/kosatka/main/docs/assets/logo.svg" alt="" width="96" height="96">
</p>

<h3 align="center">Kosatka</h3>

<p align="center">
  A CMS written in Go for building any kind of site in the admin, without writing code.<br>
  <a href="https://kosatka-cms.github.io/kosatka/">Documentation</a> ·
  <a href="https://github.com/kosatka-cms/kosatka">Engine</a> ·
  <a href="https://github.com/kosatka-cms/kosatka/releases">Releases</a>
</p>

## Try it

```bash
git clone https://github.com/kosatka-cms/kosatka.git && cd kosatka
docker compose up --build
```

A site with demo content opens at http://localhost:8080; the
administrator's password is in the log: `docker compose logs app | grep password`.

A site adds a module or a file storage with `app module add`, a theme with
`app theme add`, a language with `app translations add`. See
[the documentation](https://kosatka-cms.github.io/kosatka/).

Everything here is MIT licensed.
