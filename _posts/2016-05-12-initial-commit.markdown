---
layout: post
title:  "Initial commit"
date:   2016-08-17 12:55:43 +0530
comments: true
categories: jekyll
---
Get to know me via this blog and &nbsp; &nbsp; &nbsp;<a href="http://facebook.com/rishi25m"><i class="fa fa-facebook"></i></a> &nbsp; &nbsp; &nbsp;<a href="http://github.com/rishimi"><i class="fa fa-github"></i></a>&nbsp; &nbsp; &nbsp;<a href="/RishiMishra.PDF"><i class="fa fa-file-pdf-o" aria-hidden="true"></i></a>
<br />
<br /> Get this theme [here][theme-github]. Thanks `github-pages` for hosting this blog!. This site is made using the static site generator	`jekyll`. The comment section is provided using [disqus][disqus-url] 

[theme-github]: https://github.com/hemangsk/DevJournal
[disqus-url]: https://disqus.com/
{% if page.comments %}
<div id="disqus_thread"></div>
<script>

/**
 *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
 *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables */
/*
   var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable

   };
*/
(function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = '//rishimi-githib-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
 })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
