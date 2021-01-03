# test
---
_Advertisement :)_

- _[pica]_
- high quality and fast image resize in browser. 
- _[babelfish]_
- developter friendly i18n with plurals support and easy syntax.

You will like those prjects!

---

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading 
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___
---
***


## Typographic replacements
 Enable typographer option to see result. 
 
 (c) (C) (r) (R) (tm) (TM) (p) (P) +-
 
 test.. test... test..... test?..... test!....
 
 !!!!!! ???? ,, -- ---
 
 "Smartypants, double quotes" and 'single quotes'
 
 ## Emphasis
 
 **THis is bold test**
__This is bold test__
 *This is italic text*
 _This is italic text_
 ~~Strikethrough~~
 
 ## Blockquotes
 
 > Blockquotes can also be nested...
 >> ...by using additional greater than signs right next to each other...
 >>> ...or with spaces between arrows. 
 
 
 + 순서없음
     - 홍길동
         * 중대장
             + 프로실망러
            

|              |수학         |평가      |
|:--- | ---: | :---: |
|철수   | 90   | 참잘했어요. |
|영희   | 50   | 분발하세요. |
            
            
<script type="text/javascript" 
src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML">
</script>
(function () {
  var newMathJax = 'https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js';
  var oldMathJax = 'cdn.mathjax.org/mathjax/latest/MathJax.js';

  var replaceScript = function (script, src) {
    //
    //  Make redirected script
    //
    var newScript = document.createElement('script');
    newScript.src = newMathJax + src.replace(/.*?(\?|$)/, '$1');
    //
    //  Move onload and onerror handlers to new script
    //
    newScript.onload = script.onload; 
    newScript.onerror = script.onerror;
    script.onload = script.onerror = null;
    //
    //  Move any content (old-style configuration scripts)
    //
    while (script.firstChild) newScript.appendChild(script.firstChild);
    //
    //  Copy script id
    //
    if (script.id != null) newScript.id = script.id;
    //
    //  Replace original script with new one
    //
    script.parentNode.replaceChild(newScript, script);
    //
    //  Issue a console warning
    //
    console.warn('WARNING: cdn.mathjax.org has been retired. Check https://www.mathjax.org/cdn-shutting-down/ for migration tips.')
  }

  if (document.currentScript) {
    var script = document.currentScript;
    replaceScript(script, script.src);
  } else {
    //
    // Look for current script by searching for one with the right source
    //
    var n = oldMathJax.length;
    var scripts = document.getElementsByTagName('script');
    for (var i = 0; i < scripts.length; i++) {
      var script = scripts[i];
      var src = (script.src || '').replace(/.*?:\/\//,'');
      if (src.substr(0, n) === oldMathJax) {
        replaceScript(script, src);
        break;
      }
    }
  }
})();
$$f(x)= if x < x_[min] : (x/x_[min])^a$$             

