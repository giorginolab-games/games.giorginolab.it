# GiorginoLab Games

Jekyll showcase for the public games at https://games.giorginolab.it.

Game entries live in `_data/games.yml`. Only list public repositories; this is an explicitly curated collection, not a client-side GitHub API feed.

## Local preview

Run `bundle install`, then `bundle exec jekyll serve`. Open http://localhost:4000.

## Deployment

The Pages workflow builds and deploys pushes to `main`. Set the repository's Pages source to GitHub Actions and its custom domain to `games.giorginolab.it`. Configure a DNS CNAME from `games` to `giorginolab-games.github.io`, then enable HTTPS when GitHub finishes provisioning the certificate.

The `CNAME` file preserves the domain in the built output. Game links use their existing GitHub Pages addresses.

Editorial context: https://www.giorginolab.it/ and the three public project READMEs. The research direction is presented as exploratory; no learning outcomes or publications are claimed.
