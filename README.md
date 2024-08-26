# Go Stellar Vector!

## Read this first!

Creating links is very simple:

1. Add the following: 
```
---
location: <url the link has to point to>
slug: <optional; link url: go.stellarvector.be/{slug}>
---
```
2. To a file named `{slug}.md` where slug is the url you want the link to use
3. The `slug` is optional.
   By default the filename will be used, but if you want to overwrite it, use the `slug` property.
   Using the filename is preferred, use `slug` only if your link is difficult to identify by name, e.g. with a 'hidden' link
4. That's it!

## Examples

To make sure that `https://go.stellarvector.be/hi-there` redirects to `https://example.com/hi` use either:

file: `hi-there.md` with contents:
```
---
location: https://example.com/hi
---
```

or file: `<.*>.md` with contents:
```
---
location: https://example.com/hi
slug: hi-there
---
```
