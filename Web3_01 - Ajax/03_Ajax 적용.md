## Ajax 적용
```
<h1><a href="index.html">WEB</a></h1>
<input id="night_day" type="button" value="night" onclick="
  nightDayHandler(this);
">
<ol>
  <li><a href="1.html">HTML</a></li>
  <li><a href="2.html">CSS</a></li>
  <li><a href="3.html">JavaScript</a></li>
</ol>
<h2>WEB</h2>
<p>The World Wide Web (abbreviated WWW or the Web) is...</p>
```
- fetch API 적용
```
<h1><a href="index.html">WEB</a></h1>
<input id="night_day" type="button" value="night" onclick="
  nightDayHandler(this);
">
<ol>
  <li><a onclick="
    fetch('html').then(function(response){
      response.text().then(function(text){
        document.querySelector('article').innerHTML = text;
      })
    });
  ">HTML</a></li>
  <li><a onclick="
    fetch('css').then(function(response){
      response.text().then(function(text){
        document.querySelector('article').innerHTML = text;
      })
    });
  ">CSS</a></li>
  <li><a onclick="
    fetch('javascript').then(function(response){
      response.text().then(function(text){
        document.querySelector('article').innerHTML = text;
      })
    });
  ">JavaScript</a></li>
</ol>

<article>
  <h2>WEB</h2>
  <p>The World Wide Web (abbreviated WWW or the Web) is...</p>
</article>
```
