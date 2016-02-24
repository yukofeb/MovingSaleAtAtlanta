# MovingSaleAtAtlanta
## Site Link
[Moving Sale Site](http://yukofeb.github.io/MovingSaleAtAtlanta/)  

## Develop Memo
Build Hugo.  
[Hugo - Hosting on GitHub Pages](https://gohugo.io/tutorials/github-pages-blog/)  

Template I used.  
[Hugo Theme: Agency](http://themes.gohugo.io/agency/)  

Check.  

```
$ hugo server --watch -t agency
```

Push to gh-pages.  

```
$ git subtree push --prefix=public git@github.com:yukofeb/MovingSaleAtAtlanta.git gh-pages
```
