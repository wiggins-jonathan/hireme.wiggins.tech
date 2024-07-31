Résumé & portfolio site for [hireme.wiggins.tech](https://hireme.wiggins.tech)

# Dependencies
- [Docker](https://docker.com)
- [Hugo](https://gohugo.io)
- [node.js](https://nodejs.org)

# Installation
- Initialize a Hugo module: `hugo mod init <repo_name>`
- Add a `module` section to `hugo.yaml`:
```yaml
module:
  imports:
    - path: github.com/hugo-toha/toha/v4
```
- Download the theme: `hugo mod tidy`
- Install node dependencies: `npm install`
- Pull the hugo container & run the site: `docker compose up -d`
