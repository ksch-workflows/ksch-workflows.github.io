# KSCH Workflows Website

## Dependencies

- https://gohugo.io/
- https://themes.gohugo.io/syna/

## Run development server

With the following command you can preview the website locally:

```
hugo server -D
```

## Publish website

The website is hosted on GitHub Pages.
So in order to publish an update, compile the website into the `docs/` directory, create a git commit and then push this commit to GitHub.

```
hugo --destination docs/
git add docs/
git commit -m "Update website"
git push
```

## References

- https://blog.okkur.org/articles/create-syna-blog/
- https://maketext.io/
