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

## 指令碼:
```markdown
javascript: (function() {
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
})();
```
```
