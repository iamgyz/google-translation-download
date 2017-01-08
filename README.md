## 請將以下連結加入書籤
[Google Translation Download](javascript: (function() {
    if(document.getElementById("_d")!=null)
      return;
    var _d = document.createElement("span");
    _d.setAttribute("id","_d");
    _d.innerHTML="<strong><a>請先按播放</a></strong>";
    var _r =  document.getElementById('gt-submit');
    _r.parentNode.insertBefore(_d, _r.nextSibling);
    ws.prototype.play = function(a) {
      ws.v.play.call(this, a);
      xs(this, this.a);
      this.a = null;
      null != this.b[a] ? (this.a = this.b[a],this.b[a] = null,this.a.play()) : (this.a = ys(this, a),this.a.autoplay = !0);
      var show="<strong><a href='";
      show+=this.a.src;
      show+="' download>下載音訊</a></strong>";
      _d.innerHTML=show
    };
    alert("指令插入完成!\n請先按播放，再按下載音訊");
})();)
## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/iamgyz/google-translation-download/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/iamgyz/google-translation-download/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
