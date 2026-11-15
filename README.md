# wesleyhlee.github.io

My portfolio site, served by GitHub Pages at **https://wesleyhlee.com** (custom domain, set in the `CNAME` file) and **https://wesleyhlee.github.io**.

## Filling it in

Everything lives in `index.html`. Search for `EDIT:` comments — each one marks a spot to replace:

- Name, page title and description (top of the file and the hero)
- Intro sentence and resume link (add a `resume.pdf` to the repo)
- Projects: copy an `<article class="project">` block per project; put screenshots in an `images/` folder
- About text, skills and experience timeline
- Contact email and social links

Commit the change and GitHub Pages republishes in about a minute.

## HTTPS

1. Point the domain's DNS at GitHub Pages (A records for `@` to 185.199.108.153, .109.153, .110.153, .111.153; CNAME for `www` to `wesleyhlee.github.io`).
2. In **Settings → Pages**, wait for the DNS check and certificate to finish, then tick **Enforce HTTPS**.
3. Keep every asset URL in the page on `https://` (or relative) so nothing loads insecurely.
