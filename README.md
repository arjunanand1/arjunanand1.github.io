# Arjun Anand Website

Personal website hosted with GitHub Pages at https://arjunanand1.github.io.

## Update The Website

From this repository directory:

```bash
git status
git add .
git commit -m "Update website"
git push origin master
```

GitHub Pages will rebuild the site after the push. You can check the deployment status in the repository's Actions tab:

https://github.com/arjunanand1/arjunanand1.github.io/actions

## Preview Locally

If Ruby dependencies are installed, run:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.
