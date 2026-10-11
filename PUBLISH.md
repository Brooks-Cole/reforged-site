# Publishing reforged-site (not done yet — needs Brooks's OK)

```sh
cd /workspace/reforged-site
gh repo create Brooks-Cole/reforged-site --public --source . --push
gh api -X POST repos/Brooks-Cole/reforged-site/pages -f source[branch]=main -f source[path]=/
```

Planned URLs (live ~1 min after Pages builds):
- https://brooks-cole.github.io/reforged-site/
- https://brooks-cole.github.io/reforged-site/privacy.html
- https://brooks-cole.github.io/reforged-site/support.html

After publishing, put the privacy/support URLs into docs/app-store-listing.md (box and Mac) and ~/Desktop/Reforged App Store/Listing.md.
