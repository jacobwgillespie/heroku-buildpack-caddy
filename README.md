# heroku-buildpack-caddy

This is a [Heroku buildpack](https://devcenter.heroku.com/articles/buildpacks) for installing the [Caddy server](https://caddyserver.com/).

### Environment Variables

| Variable | Description
| -------- | -----------
| `CADDY_REPO` | The GitHub repository used to find Caddy releases.  Defaults to `mholt/caddy`.
| `CADDY_VERSION` | The version of Caddy to install.
