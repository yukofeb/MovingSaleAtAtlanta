# MovingSaleAtAtlanta
## Site Link
[Moving Sale Site](http://yukofeb.github.io/MovingSaleAtAtlanta/)  

## Development Memo
[ブログシステムHugoを構築してGithub Pagesで運用する - yukofebの日記](http://yukofeb.hatenablog.com/entry/2016/02/25/024349)    

## References
[無料の画像結合ツール - フォトコンバイン](http://photocombine.net/cb/)  
[Placehold.jp｜ダミー画像生成 モック用画像作成](http://placehold.jp/)  
[画像サイズ変更ツール](http://neutralx0.net/tool/img.html)  

## Tips
Build Hugo.  
[Hugo - Hosting on GitHub Pages](https://gohugo.io/tutorials/github-pages-blog/)  

Template I used.  
[Hugo Theme: Agency](http://themes.gohugo.io/agency/)  

Check.  

```
$ hugo server --watch -t agency
```

Generate.  

```
$ hugo -t agency
```

After commit.  

```
# push to master
$ git push origin master

# push to gh-pages
$ git subtree push --prefix=public git@github.com:yukofeb/MovingSaleAtAtlanta.git gh-pages
```
