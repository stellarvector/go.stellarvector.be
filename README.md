# Go Stellar Vector!

## Read this first!

Creating links is very simple:

1. Add the following: 
```
---
location: <url the link has to point to>
---
```
1. To a file named `{slug}.md` where slug is the url you want the link to use
2. You can use folders to create path elements
3. That's it!

## Examples

To make sure that `https://go.stellarvector.be/hi-there` redirects to `https://example.com/hi` create:

file: `hi-there.md` with contents:
```
---
location: https://example.com/hi
---
```
