# hugo-site-builder
Hugo site building, Hugo v 0.69.2

## Create a new site

```bash
docker run --rm -it -v $PWD:/src -p 1313:1313 -u hugo smathewthomas/hugo-site-builder hugo new site my-new-website
```

## Create a new post 

```bash
docker run --rm -it -v $PWD:/src -u hugo smathewthomas/hugo-site-builder hugo new content/blog/my-new-post.md
```

## Build your static site into public/

```bash
docker run --rm -it -v $PWD:/src -u hugo smathewthomas/hugo-site-builder hugo -D
```
