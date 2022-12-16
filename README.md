# Unheard Health

To run locally:

```
docker run --name blog --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:3 jekyll serve --watch --drafts
```