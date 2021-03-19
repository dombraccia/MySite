## How to update your site

Because I know I am going to forget how to do this, here is how to update your website:

1. Make changes to this site (adding blog posts, updating resume, etc.) and test changes with:

```
hugo server -D
```

and navigate to localhost:1313/ in a web browser to check them out.

2. After adding whatever changes you have made, commit them to this repo, the `dombraccia/MySite` one.

3. Then, run 

```
## to export these changes to the publishing directory, `dombraccia.github.io`
hugo

## to make these changes public
cd dombraccia.github.io
git add *
git commit -m "."
git push origin main
```

And your new changes should be made public!
