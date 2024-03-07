See https://github.com/renovatebot/renovate/discussions/27777 for issue description

Run using Docker

```
docker run --rm -it -v "./config.js:/usr/src/app/config.js" --env GITHUB_COM_TOKEN=<token> --env RENOVATE_TOKEN=<token> renovate/renovate:37.231.0-full
```