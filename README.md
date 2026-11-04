# GiorginoLab Games

Jekyll showcase for the public games at https://giorginolab-games.github.io/games.giorginolab.it/.

Game entries live in `_data/games.yml`. Only list public repositories; this is an explicitly curated collection, not a client-side GitHub API feed.

## Local preview

Run `bundle install`, then `bundle exec jekyll serve`. Open http://localhost:4000/games.giorginolab.it/.

## Deployment

The Pages workflow builds and deploys pushes to `main` using GitHub Actions. The `url` and `baseurl` in `_config.yml` match the current GitHub Pages project URL.

To use `games.giorginolab.it` later, verify the domain with GitHub, set it as the repository's Pages custom domain, configure a DNS CNAME from `games` to `giorginolab-games.github.io`, and enable HTTPS when the certificate is provisioned. Also change `url` in `_config.yml` to `https://games.giorginolab.it` and `baseurl` to `""`.

Game links use their existing GitHub Pages addresses.

Editorial context: https://www.giorginolab.it/ and the public project READMEs. The research direction is presented as exploratory; no learning outcomes or publications are claimed.
