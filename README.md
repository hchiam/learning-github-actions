# Learning GitHub Actions

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Testing out `markdown-link-check` on this repo:

<https://github.com/gaurav-nelson/github-action-markdown-link-check>

<https://github.com/marketplace/actions/markdown-link-check>

## Setup

```bash
mkdir .github
mkdir .github/workflows
touch .github/workflows/action.yml
```

Then edit `action.yml`

When you push, you'll see results here: <https://github.com/hchiam/learning-github-actions/actions>

More info: <https://docs.github.com/en/free-pro-team@latest/actions/quickstart>

Intentionally broken link: <https://github.com/hchiam/learning-github-actions/actionsy>

## Example output

Successfully detected broken link in `README.md`!

<img src="results-example.png">
