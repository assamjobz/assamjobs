
<!DOCTYPE html>
<html class="v2" dir="ltr" lang="en"><head><script type="text/javascript">
    (function() {
      var container = document.querySelector('#_tcx-q43ic7okqq');
      if (!container) {
        return;
      }

      function addToContainer(url, text) {
        const wrapper = document.createElement('div');
        wrapper.setAttribute('data-tcx-url', url);
        wrapper.innerText = text;
        container.appendChild(wrapper);
      }

      const fetch = window.fetch
      window.fetch = function() {
        return Promise.resolve(fetch.apply(window, arguments))
            .then(async response => {
              if (response.ok) {
                try {
                  const clone = response.clone();
                  const json = await clone.json();
                  addToContainer(clone.url, JSON.stringify(json));
                } catch (err) {}
              }
              return response;
            });
      };

      var XHR = XMLHttpRequest.prototype;
      var send = XHR.send;
      var open = XHR.open;
      XHR.open = function(method, url) {
        this.url = url;
        return open.apply(this, arguments);
      };
      XHR.send = function() {
        this.addEventListener('load', function() {
          try {
            const response = this.response;
            if (response && response.length) {
              const firstChar = response[0];
              if (firstChar === '[' || firstChar === '{') {
                addToContainer(this.url, response);
              }
            }
          } catch (err) {
            // No-op.
          }
        });
        return send.apply(this, arguments);
      };
    })();
  </script>
<link href="https://www.blogger.com/static/v1/widgets/2975350028-css_bundle_v2.css" rel="stylesheet" type="text/css">
<meta content="width=1200" name="viewport">
<meta content="text/html; charset=UTF-8" http-equiv="Content-Type">
<meta content="blogger" name="generator">
<link href="https://assam-jobz.blogspot.com/favicon.ico" rel="icon" type="image/x-icon">
<link href="https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html" rel="canonical">
<link rel="alternate" type="application/atom+xml" title="Assam Jobs | Find Jobs in assam and North East - Atom" href="https://assam-jobz.blogspot.com/feeds/posts/default">
<link rel="alternate" type="application/rss+xml" title="Assam Jobs | Find Jobs in assam and North East - RSS" href="https://assam-jobz.blogspot.com/feeds/posts/default?alt=rss">
<link rel="service.post" type="application/atom+xml" title="Assam Jobs | Find Jobs in assam and North East - Atom" href="https://www.blogger.com/feeds/4600799949292916563/posts/default">

<link rel="alternate" type="application/atom+xml" title="Assam Jobs | Find Jobs in assam and North East - Atom" href="https://assam-jobz.blogspot.com/feeds/5778184567614263207/comments/default">
<!--[if IE]><script type="text/javascript" src="https://www.blogger.com/static/v1/jsbin/2068738220-ieretrofit.js"></script>
<![endif]-->
<meta content="https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html" property="og:url">
<meta content="Assam Jobs ???Find Jobs in Assam and North East" property="og:title">
<meta content="Assam Jobs Jobs in Assam and North East" property="og:description">
<!--[if IE]> <script> (function() { var html5 = ("abbr,article,aside,audio,canvas,datalist,details," + "figure,footer,header,hgroup,mark,menu,meter,nav,output," + "progress,section,time,video").split(','); for (var i = 0; i < html5.length; i++) { document.createElement(html5[i]); } try { document.execCommand('BackgroundImageCache', false, true); } catch(e) {} })(); </script> <![endif]-->
<title>Assam Jobs | Find Jobs in assam and North East: Assam Jobs</title>
<style id="page-skin-1" type="text/css"><!--
/*-----------------------------------------------
Blogger Template Style
Name:     Picture Window
Designer: Blogger
URL:      www.blogger.com
----------------------------------------------- */
/* Content
----------------------------------------------- */
body {
font: normal normal 15px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
color: #333333;
background: #dddddd url(none) repeat-x fixed bottom center;
}
html body .region-inner {
min-width: 0;
max-width: 100%;
width: auto;
}
.content-outer {
font-size: 90%;
}
a:link {
text-decoration:none;
color: #992211;
}
a:visited {
text-decoration:none;
color: #771100;
}
a:hover {
text-decoration:underline;
color: #cc4411;
}
.content-outer {
background: transparent url(https://resources.blogblog.com/blogblog/data/1kt/transparent/white80.png) repeat scroll top left;
-moz-border-radius: 15px;
-webkit-border-radius: 15px;
-goog-ms-border-radius: 15px;
border-radius: 15px;
-moz-box-shadow: 0 0 3px rgba(0, 0, 0, .15);
-webkit-box-shadow: 0 0 3px rgba(0, 0, 0, .15);
-goog-ms-box-shadow: 0 0 3px rgba(0, 0, 0, .15);
box-shadow: 0 0 3px rgba(0, 0, 0, .15);
margin: 30px auto;
}
.content-inner {
padding: 15px;
}
/* Header
----------------------------------------------- */
.header-outer {
background: #992211 url(https://resources.blogblog.com/blogblog/data/1kt/transparent/header_gradient_shade.png) repeat-x scroll top left;
_background-image: none;
color: #ffffff;
-moz-border-radius: 10px;
-webkit-border-radius: 10px;
-goog-ms-border-radius: 10px;
border-radius: 10px;
}
.Header img, .Header #header-inner {
-moz-border-radius: 10px;
-webkit-border-radius: 10px;
-goog-ms-border-radius: 10px;
border-radius: 10px;
}
.header-inner .Header .titlewrapper,
.header-inner .Header .descriptionwrapper {
padding-left: 30px;
padding-right: 30px;
}
.Header h1 {
font: normal normal 36px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
}
.Header h1 a {
color: #ffffff;
}
.Header .description {
font-size: 130%;
}
/* Tabs
----------------------------------------------- */
.tabs-inner {
margin: .5em 0 0;
padding: 0;
}
.tabs-inner .section {
margin: 0;
}
.tabs-inner .widget ul {
padding: 0;
background: #f5f5f5 url(https://resources.blogblog.com/blogblog/data/1kt/transparent/tabs_gradient_shade.png) repeat scroll bottom;
-moz-border-radius: 10px;
-webkit-border-radius: 10px;
-goog-ms-border-radius: 10px;
border-radius: 10px;
}
.tabs-inner .widget li {
border: none;
}
.tabs-inner .widget li a {
display: inline-block;
padding: .5em 1em;
margin-right: 0;
color: #992211;
font: normal normal 15px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
-moz-border-radius: 0 0 0 0;
-webkit-border-top-left-radius: 0;
-webkit-border-top-right-radius: 0;
-goog-ms-border-radius: 0 0 0 0;
border-radius: 0 0 0 0;
background: transparent none no-repeat scroll top left;
border-right: 1px solid #cccccc;
}
.tabs-inner .widget li:first-child a {
padding-left: 1.25em;
-moz-border-radius-topleft: 10px;
-moz-border-radius-bottomleft: 10px;
-webkit-border-top-left-radius: 10px;
-webkit-border-bottom-left-radius: 10px;
-goog-ms-border-top-left-radius: 10px;
-goog-ms-border-bottom-left-radius: 10px;
border-top-left-radius: 10px;
border-bottom-left-radius: 10px;
}
.tabs-inner .widget li.selected a,
.tabs-inner .widget li a:hover {
position: relative;
z-index: 1;
background: #ffffff url(https://resources.blogblog.com/blogblog/data/1kt/transparent/tabs_gradient_shade.png) repeat scroll bottom;
color: #000000;
-moz-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
-webkit-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
-goog-ms-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
box-shadow: 0 0 0 rgba(0, 0, 0, .15);
}
/* Headings
----------------------------------------------- */
h2 {
font: bold normal 13px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
text-transform: uppercase;
color: #666666;
margin: .5em 0;
}
/* Main
----------------------------------------------- */
.main-outer {
background: transparent none repeat scroll top center;
-moz-border-radius: 0 0 0 0;
-webkit-border-top-left-radius: 0;
-webkit-border-top-right-radius: 0;
-webkit-border-bottom-left-radius: 0;
-webkit-border-bottom-right-radius: 0;
-goog-ms-border-radius: 0 0 0 0;
border-radius: 0 0 0 0;
-moz-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
-webkit-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
-goog-ms-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
box-shadow: 0 0 0 rgba(0, 0, 0, .15);
}
.main-inner {
padding: 15px 5px 20px;
}
.main-inner .column-center-inner {
padding: 0 0;
}
.main-inner .column-left-inner {
padding-left: 0;
}
.main-inner .column-right-inner {
padding-right: 0;
}
/* Posts
----------------------------------------------- */
h3.post-title {
margin: 0;
font: normal normal 18px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
}
.comments h4 {
margin: 1em 0 0;
font: normal normal 18px Arial, Tahoma, Helvetica, FreeSans, sans-serif;
}
.date-header span {
color: #333333;
}
.post-outer {
background-color: #ffffff;
border: solid 1px #dddddd;
-moz-border-radius: 10px;
-webkit-border-radius: 10px;
border-radius: 10px;
-goog-ms-border-radius: 10px;
padding: 15px 20px;
margin: 0 -20px 20px;
}
.post-body {
line-height: 1.4;
font-size: 110%;
position: relative;
}
.post-header {
margin: 0 0 1.5em;
color: #999999;
line-height: 1.6;
}
.post-footer {
margin: .5em 0 0;
color: #999999;
line-height: 1.6;
}
#blog-pager {
font-size: 140%
}
#comments .comment-author {
padding-top: 1.5em;
border-top: dashed 1px #ccc;
border-top: dashed 1px rgba(128, 128, 128, .5);
background-position: 0 1.5em;
}
#comments .comment-author:first-child {
padding-top: 0;
border-top: none;
}
.avatar-image-container {
margin: .2em 0 0;
}
/* Comments
----------------------------------------------- */
.comments .comments-content .icon.blog-author {
background-repeat: no-repeat;
background-image: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAASCAYAAABWzo5XAAAAAXNSR0IArs4c6QAAAAZiS0dEAP8A/wD/oL2nkwAAAAlwSFlzAAALEgAACxIB0t1+/AAAAAd0SU1FB9sLFwMeCjjhcOMAAAD+SURBVDjLtZSvTgNBEIe/WRRnm3U8RC1neQdsm1zSBIU9VVF1FkUguQQsD9ITmD7ECZIJSE4OZo9stoVjC/zc7ky+zH9hXwVwDpTAWWLrgS3QAe8AZgaAJI5zYAmc8r0G4AHYHQKVwII8PZrZFsBFkeRCABYiMh9BRUhnSkPTNCtVXYXURi1FpBDgArj8QU1eVXUzfnjv7yP7kwu1mYrkWlU33vs1QNu2qU8pwN0UpKoqokjWwCztrMuBhEhmh8bD5UDqur75asbcX0BGUB9/HAMB+r32hznJgXy2v0sGLBcyAJ1EK3LFcbo1s91JeLwAbwGYu7TP/3ZGfnXYPgAVNngtqatUNgAAAABJRU5ErkJggg==);
}
.comments .comments-content .loadmore a {
border-top: 1px solid #cc4411;
border-bottom: 1px solid #cc4411;
}
.comments .continue {
border-top: 2px solid #cc4411;
}
/* Widgets
----------------------------------------------- */
.widget ul, .widget #ArchiveList ul.flat {
padding: 0;
list-style: none;
}
.widget ul li, .widget #ArchiveList ul.flat li {
border-top: dashed 1px #ccc;
border-top: dashed 1px rgba(128, 128, 128, .5);
}
.widget ul li:first-child, .widget #ArchiveList ul.flat li:first-child {
border-top: none;
}
.widget .post-body ul {
list-style: disc;
}
.widget .post-body ul li {
border: none;
}
/* Footer
----------------------------------------------- */
.footer-outer {
color:#eeeeee;
background: transparent url(https://resources.blogblog.com/blogblog/data/1kt/transparent/black50.png) repeat scroll top left;
-moz-border-radius: 10px 10px 10px 10px;
-webkit-border-top-left-radius: 10px;
-webkit-border-top-right-radius: 10px;
-webkit-border-bottom-left-radius: 10px;
-webkit-border-bottom-right-radius: 10px;
-goog-ms-border-radius: 10px 10px 10px 10px;
border-radius: 10px 10px 10px 10px;
-moz-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
-webkit-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
-goog-ms-box-shadow: 0 0 0 rgba(0, 0, 0, .15);
box-shadow: 0 0 0 rgba(0, 0, 0, .15);
}
.footer-inner {
padding: 10px 5px 20px;
}
.footer-outer a {
color: #ffffdd;
}
.footer-outer a:visited {
color: #cccc99;
}
.footer-outer a:hover {
color: #ffffff;
}
.footer-outer .widget h2 {
color: #bbbbbb;
}
/* Mobile
----------------------------------------------- */
html body.mobile {
height: auto;
}
html body.mobile {
min-height: 480px;
background-size: 100% auto;
}
.mobile .body-fauxcolumn-outer {
background: transparent none repeat scroll top left;
}
html .mobile .mobile-date-outer, html .mobile .blog-pager {
border-bottom: none;
background: transparent none repeat scroll top center;
margin-bottom: 10px;
}
.mobile .date-outer {
background: transparent none repeat scroll top center;
}
.mobile .header-outer, .mobile .main-outer,
.mobile .post-outer, .mobile .footer-outer {
-moz-border-radius: 0;
-webkit-border-radius: 0;
-goog-ms-border-radius: 0;
border-radius: 0;
}
.mobile .content-outer,
.mobile .main-outer,
.mobile .post-outer {
background: inherit;
border: none;
}
.mobile .content-outer {
font-size: 100%;
}
.mobile-link-button {
background-color: #992211;
}
.mobile-link-button a:link, .mobile-link-button a:visited {
color: #ffffff;
}
.mobile-index-contents {
color: #333333;
}
.mobile .tabs-inner .PageList .widget-content {
background: #ffffff url(https://resources.blogblog.com/blogblog/data/1kt/transparent/tabs_gradient_shade.png) repeat scroll bottom;
color: #000000;
}
.mobile .tabs-inner .PageList .widget-content .pagelist-arrow {
border-left: 1px solid #cccccc;
} 

--></style>
<style id="template-skin-1" type="text/css"><!--
body {
min-width: 1367px;
}
.content-outer, .content-fauxcolumn-outer, .region-inner {
min-width: 1367px;
max-width: 1367px;
_width: 1367px;
}
.main-inner .columns {
padding-left: 0;
padding-right: 0px;
}
.main-inner .fauxcolumn-center-outer {
left: 0;
right: 310px;
/* IE6 does not respect left and right together */
_width: expression(this.parentNode.offsetWidth -
parseInt("0") -
parseInt("310px") + 'px');
}
.main-inner .fauxcolumn-left-outer {
width: 0;
}
.main-inner .fauxcolumn-right-outer {
width: 310px;
}
.main-inner .column-left-outer {
width: 0;
right: 100%;
margin-left: -0;
}
.main-inner .column-right-outer {
width: 310px;
margin-right: -310px;
}
#layout {
min-width: 0;
}
#layout .content-outer {
min-width: 0;
width: 800px;
}
#layout .region-inner {
min-width: 0;
width: auto;
}
body#layout div.add_widget {
padding: 8px;
}
body#layout div.add_widget a {
margin-left: 32px;
}
--></style>
<link href="https://www.blogger.com/dyn-css/authorization.css?targetBlogID=4600799949292916563&amp;zx=e163fb53-5df9-48ad-acb6-08fd7a6bd571" media="all" onload="if(media!='all')media='all'" rel="stylesheet"><noscript><link href='https://www.blogger.com/dyn-css/authorization.css?targetBlogID=4600799949292916563&amp;zx=e163fb53-5df9-48ad-acb6-08fd7a6bd571' rel='stylesheet'/></noscript>
<meta name="google-adsense-platform-account" content="ca-host-pub-1556223355139109">
<meta name="google-adsense-platform-domain" content="blogspot.com">

<script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.lb.en.NnK9YPjtg-w.O/m=profile/exm=gapi_iframes,gapi_iframes_style_bubble,plusone/rt=j/sv=1/d=1/ed=1/rs=AHpOoo9KePDGVlGjp-rlXwDM1kUO2Eh4gg/cb=gapi.loaded_2?le=scs" async=""></script><script type="text/javascript" src="//pagead2.googlesyndication.com/pagead/js/google_top_exp.js"></script><style>.gc-bubbleDefault{table-layout:auto!important}.gc-bubbleDefault,.gc-reset{background-color:transparent!important;text-align:left;padding:0!important;margin:0!important;border:0!important}.pls-bubbleTop{border-bottom:1px solid #ccc!important}.pls-contentLeft,.pls-topTail,.pls-vertShimLeft{background-image:url(//ssl.gstatic.com/s2/oz/images/stars/po/bubblev1/border_3.gif)!important}.pls-topTail{background-repeat:repeat-x!important;background-position:bottom!important}.pls-vertShim{background-color:#fff!important;text-align:right}.tbl-grey .pls-vertShim{background-color:#f5f5f5!important}.pls-vertShimLeft{background-repeat:repeat-y!important;background-position:100%!important;height:4px}.pls-vertShimRight{height:4px}.pls-confirm-container .pls-vertShim{background-color:#fff3c2!important}.pls-contentWrap{background-color:#fff!important;position:relative!important;vertical-align:top}.pls-contentLeft{background-repeat:repeat-y;background-position:100%;vertical-align:top}.pls-dropRight{background-image:url(//ssl.gstatic.com/s2/oz/images/stars/po/bubblev1/bubbleDropR_3.png)!important;background-repeat:repeat-y!important}.pls-dropBL,.pls-dropBottom,.pls-dropRight,.pls-dropTR .pls-dropBR,.pls-tailleft,.pls-vert,.pls-vert img{vertical-align:top}.pls-dropBottom{background-image:url(//ssl.gstatic.com/s2/oz/images/stars/po/bubblev1/bubbleDropB_3.png)!important;background-repeat:repeat-x!important;width:100%}.pls-topLeft{text-align:right}.pls-topLeft,.pls-topRight{background:inherit!important;vertical-align:bottom}.pls-topRight{text-align:left}.pls-bottomLeft{background:inherit!important;text-align:right}.pls-bottomRight{background:inherit!important;text-align:left;vertical-align:top}.pls-tailbottom,.pls-tailleft,.pls-tailright,.pls-tailtop{display:none;position:relative}.pls-dropBL,.pls-dropBR,.pls-dropTR,.pls-tailbottom,.pls-tailleft,.pls-tailright,.pls-tailtop{background-image:url(//ssl.gstatic.com/s2/oz/images/stars/po/bubblev1/bubbleSprite_3.png)!important;background-repeat:no-repeat}.tbl-grey .pls-dropBL,.tbl-grey .pls-dropBR,.tbl-grey .pls-dropTR,.tbl-grey .pls-tailbottom,.tbl-grey .pls-tailleft,.tbl-grey .pls-tailright,.tbl-grey .pls-tailtop{background-image:url(//ssl.gstatic.com/s2/oz/images/stars/po/bubblev1/bubbleSprite-grey.png)!important}.pls-tailbottom{background-position:-23px 0}.pls-confirm-container .pls-tailbottom{background-position:-23px -10px}.pls-tailtop{background-position:-19px -20px}.pls-tailright{background-position:0 0}.pls-tailleft{background-position:-10px 0}.pls-tailtop{vertical-align:top}.gc-bubbleDefault td{line-height:0;font-size:0}.pls-tailbottom,.pls-topLeft img,.pls-topRight img{vertical-align:bottom}.bubbleDropTR,.pls-bottomLeft,.pls-bottomLeft img,.pls-dropBottom img,.pls-dropBottomL img,.pls-dropBottomR img{vertical-align:top}.pls-dropTR{background-position:0 -22px}.pls-dropBR{background-position:0 -27px}.pls-dropBL{background-position:0 -16px}.pls-spacerbottom,.pls-spacerleft,.pls-spacerright,.pls-spacertop{position:static!important}.pls-spinner{bottom:0;position:absolute;left:0;margin:auto;right:0;top:0}</style><script async="" src="https://www.gstatic.com/feedback/js/help/prod/service/lazy.min.js"></script></head>
<body class=" variant-shade">
 
<div class="body-fauxcolumns">
<div class="fauxcolumn-outer body-fauxcolumn-outer">
<div class="cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left">
<div class="fauxborder-right"></div>
<div class="fauxcolumn-inner">
</div>
</div>
<div class="cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
</div>
<div class="content">
<div class="content-fauxcolumns">
<div class="fauxcolumn-outer content-fauxcolumn-outer">
<div class="cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left">
<div class="fauxborder-right"></div>
<div class="fauxcolumn-inner">
</div>
</div>
<div class="cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
</div>
<div class="content-outer">
<div class="content-cap-top cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left content-fauxborder-left">
<div class="fauxborder-right content-fauxborder-right"></div>
<div class="content-inner">
<header>
<div class="header-outer">
<div class="header-cap-top cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left header-fauxborder-left">
<div class="fauxborder-right header-fauxborder-right"></div>
<div class="region-inner header-inner">
<div class="header section" id="header" name="Header"><div class="widget Header" data-version="1" id="Header1">
<div id="header-inner">
<div class="titlewrapper">
<h1 class="title">
<a href="https://assamjobs.w3spaces.com/">
Assam Jobs | Find Jobs in assam and North East 
</a> 
</h1>
</div>
<div class="descriptionwrapper">
Assam jobs, assam requirements <p class="description"><span></span></p>
</div>
</div>
</div></div>
</div>
</div>
<div class="header-cap-bottom cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
</header>
<div class="tabs-outer">
<div class="tabs-cap-top cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left tabs-fauxborder-left">
<div class="fauxborder-right tabs-fauxborder-right"></div>
<div class="region-inner tabs-inner">
<div class="tabs no-items section" id="crosscol" name="Cross-Column"></div>
<div class="tabs no-items section" id="crosscol-overflow" name="Cross-Column 2"></div>
</div>
</div>
<div class="tabs-cap-bottom cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
<div class="main-outer">
<div class="main-cap-top cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left main-fauxborder-left">
<div class="fauxborder-right main-fauxborder-right"></div>
<div class="region-inner main-inner">
<div class="columns fauxcolumns">
<div class="fauxcolumn-outer fauxcolumn-center-outer">
<div class="cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left">
<div class="fauxborder-right"></div>
<div class="fauxcolumn-inner">
</div>
</div>
<div class="cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
<div class="fauxcolumn-outer fauxcolumn-left-outer">
<div class="cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left">
<div class="fauxborder-right"></div>
<div class="fauxcolumn-inner">
</div>
</div>
<div class="cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
<div class="fauxcolumn-outer fauxcolumn-right-outer">
<div class="cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left">
<div class="fauxborder-right"></div>
<div class="fauxcolumn-inner">
</div>
</div>
<div class="cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
<!-- corrects IE6 width calculation -->
<div class="columns-inner">
<div class="column-center-outer">
<div class="column-center-inner">
<div class="main section" id="main" name="Main"><div class="widget Blog" data-version="1" id="Blog1">
<div class="blog-posts hfeed">

          <div class="date-outer">
        
<h2 class="date-header"><span>Tuesday, February 4, 2020</span></h2>

          <div class="date-posts">
        
<div class="post-outer">
<div class="post hentry uncustomized-post-template" itemprop="blogPost" itemscope="itemscope" itemtype="http://schema.org/BlogPosting">
<meta content="4600799949292916563" itemprop="blogId">
<meta content="5778184567614263207" itemprop="postId">
<a name="5778184567614263207"></a>
<h3 class="post-title entry-title" itemprop="name">
Assam Jobs
</h3>
<div class="post-header">
<div class="post-header-line-1"></div>
</div>
<div class="post-body entry-content" id="post-body-5778184567614263207" itemprop="description articleBody">
<div dir="ltr" style="text-align: left;" trbidi="on">
<br>
<div dir="ltr"> AssamJobz.Com website serves as a Hook-Up to get inform regarding several jobs in Assam which also encompasses the broadcast of Public Sector jobs of Assam and North Eastern States.

Remaining updated with this website people can accumulate the news of latest job opportunities in Assam . This website also provides clue regarding jobs of Central Govt. , Educational fields, Public Sector , Bank and assorted Emulative examinations starting from. <br/>
<a href="http://assamjobz.com/">Assam jobs</a>, assam requirements, assam job vacancies, vecancy in assam, sakari in assam, sarkari sakori in axom, govt jobs north east and assam, jobs in Tripura, jobs in Nagaland, jobs in mijoram, jobs in Arunachal Pradesh, jobs in Meghalaya, jobs in manipur, jobs in North East, assamjobz, <a href="http://assamjobz.com/">AssamJobz.com</a>, assam career, assamcareer, find job in assam and north east, gu results, gu registration, gu apply, University results assam, Gauhati University, Guwahati University, hslc result assam, hs result assam, BA results assam, tdc results assam, works in Assam, work in North East, post in assam, University entrance apply and dates, bodoland University, tejpur University, assam tet, matric results, higher secondary result, admit card download assam, exam date assam, jobassam, job in North East India, govt jobs, assam government job, central government job for assam, all job details of assam. New job in assam. New job vacancies in assam, New job posts in assam, public sector jobs in Assam, railway jobs in assam, Guwahati jobs, </div>
<div dir="ltr">
<br></div>
JobsBengal.Com keeps you updated with jobs vacancy news, exam results, admit cards and student related information in <a href="https://jobsbengal.com/">West Bengal Jobs</a>, Our motive is to build your career with ease. Your one stop information portal for all your needs,
<div dir="ltr">
<b><a href="http://assamjobz.com/"><br></a></b></div> 
<div dir="ltr">
<b><a href="https://jobsbengal.com/">Browse Jobs in West Bengal</a></b></div>
<br></div>
<div dir="ltr">
<b><a href="http://assamjobz.com/">Browse Jobs in Assam</a></b></div>
<br></div>
<div style="clear: both;"></div>
</div>
<div class="post-footer">
<div class="post-footer-line post-footer-line-1">
<span class="post-author vcard">
</span>
<span class="post-timestamp">
at
<meta content="https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html" itemprop="url">
<a class="timestamp-link" href="https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html" rel="bookmark" title="permanent link"><abbr class="published" itemprop="datePublished" title="2020-02-04T03:11:00-08:00">February 04, 2020</abbr></a>
</span>
<span class="post-comment-link">
</span>
<span class="post-icons">
<span class="item-control blog-admin pid-1785915528">
<a href="https://www.blogger.com/post-edit.g?blogID=4600799949292916563&amp;postID=5778184567614263207&amp;from=pencil" title="Edit Post">
<img alt="" class="icon-action" height="18" src="https://resources.blogblog.com/img/icon18_edit_allbkg.gif" width="18">
</a>
</span>
</span>
<div class="post-share-buttons goog-inline-block">
<a class="goog-inline-block share-button sb-email" href="https://www.blogger.com/share-post.g?blogID=4600799949292916563&amp;postID=5778184567614263207&amp;target=email" target="_blank" title="Email This"><span class="share-button-link-text">Email This</span></a><a class="goog-inline-block share-button sb-blog" href="https://www.blogger.com/share-post.g?blogID=4600799949292916563&amp;postID=5778184567614263207&amp;target=blog" onclick="window.open(this.href, &quot;_blank&quot;, &quot;height=270,width=475&quot;); return false;" target="_blank" title="BlogThis!"><span class="share-button-link-text">BlogThis!</span></a><a class="goog-inline-block share-button sb-twitter" href="https://www.blogger.com/share-post.g?blogID=4600799949292916563&amp;postID=5778184567614263207&amp;target=twitter" target="_blank" title="Share to Twitter"><span class="share-button-link-text">Share to Twitter</span></a><a class="goog-inline-block share-button sb-facebook" href="https://www.blogger.com/share-post.g?blogID=4600799949292916563&amp;postID=5778184567614263207&amp;target=facebook" onclick="window.open(this.href, &quot;_blank&quot;, &quot;height=430,width=640&quot;); return false;" target="_blank" title="Share to Facebook"><span class="share-button-link-text">Share to Facebook</span></a><a class="goog-inline-block share-button sb-pinterest" href="https://www.blogger.com/share-post.g?blogID=4600799949292916563&amp;postID=5778184567614263207&amp;target=pinterest" target="_blank" title="Share to Pinterest"><span class="share-button-link-text">Share to Pinterest</span></a>
</div>
</div>
<div class="post-footer-line post-footer-line-2">
<span class="post-labels">
</span>
</div>
<div class="post-footer-line post-footer-line-3">
<span class="post-location">
</span>
</div>
</div>
</div>
<div class="comments" id="comments">
<a name="comments"></a>
</div>
</div>
<div class="inline-ad">
<!--Can't find substitution for tag [adCode]-->
</div>

        </div></div>
      
</div>
<div class="blog-pager" id="blog-pager">
<span id="blog-pager-newer-link">
<a class="blog-pager-newer-link" href="https://assam-jobz.blogspot.com/2020/02/assam-jobs-jobs-in-assam-and-north-east.html" id="Blog1_blog-pager-newer-link" title="Newer Post">Newer Post</a>
</span>
<a class="home-link" href="https://assam-jobz.blogspot.com/">Home</a>
</div>
<div class="clear"></div>
<div class="post-feeds">
</div>
</div><div class="widget FeaturedPost" data-version="1" id="FeaturedPost1">
<div class="post-summary">
</div>
<style type="text/css">
    .image {
      width: 100%;
    }
  </style>
<div class="clear"></div>
</div><div class="widget PopularPosts" data-version="1" id="PopularPosts1">
<div class="widget-content popular-posts">
<ul>
<li>
<div class="item-content">
<div class="item-title"><a href="https://assamjobz.com/assam-hs-result-2020-ahsec-exam-result-2020/">Assam HS Result / Class 12th Result Assam</a></div>
<div class="item-snippet">  HS Final Year Exam Results 2020   Will Be Live From 9 A.M  CLICK HERE</div>
</div>
<div style="clear: both;"></div>
</li>
<li>
<div class="item-content">
<div class="item-title"><a href="https://assam-jobz.blogspot.com/">Assam Jobs, Jobs in Assam and North East India</a></div>
<div class="item-snippet">   A Premier Website for Latest Government and Private Sector&nbsp; Jobs , Recruitment, Vacancies and Sakori in&nbsp; Assam &nbsp;and North East India Stat...</div>
</div>
<div style="clear: both;"></div>
</li>
<li>
<div class="item-content">
<div class="item-title"><a href="https://jobsbengal.com/">Jobs Bengal</a></div>
<div class="item-snippet">   JobsBengal.Com keeps you updated with jobs vacancy news, exam results, admit cards and student related information in West Bengal, Our motive is to build your career with ease. Your one stop information portal for all your needs</div>
</div>
</li> 
<li>
<div style="clear: both;"></div>
<div class="item-content">
<div class="item-title"><a href="https://assamjobz.com/assamese-translator/">Assamese Translator</a></div>
<div class="item-snippet"> Assamese Translator English to Assamese Translation   </div>
</div>
<div style="clear: both;"></div>
</li>
</ul>
<div class="clear"></div>
</div>
</div></div>
</div>
</div>
<div class="column-left-outer">
<div class="column-left-inner">
<aside>
</aside>
</div>
</div>
<div class="column-right-outer">
<div class="column-right-inner">
<aside>

</div>
</div>
</div>
<div style="clear: both"></div>
<!-- columns -->
</div>
<!-- main -->
</div>
</div>
<div class="main-cap-bottom cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
<footer>
<div class="footer-outer">
<div class="footer-cap-top cap-top">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
<div class="fauxborder-left footer-fauxborder-left">
<div class="fauxborder-right footer-fauxborder-right"></div>
<div class="region-inner footer-inner">
<div class="foot no-items section" id="footer-1"></div>
<table border="0" cellpadding="0" cellspacing="0" class="section-columns columns-2">
<tbody>
<tr>
<td class="first columns-cell">
<div class="foot no-items section" id="footer-2-1"></div>
</td>
<td class="columns-cell">
<div class="foot no-items section" id="footer-2-2"></div>
</td>
</tr>
</tbody>
</table>
<!-- outside of the include in order to lock Attribution widget -->
<div class="foot section" id="footer-3" name="Footer"><div class="widget Attribution" data-version="1" id="Attribution1">
<div class="widget-content" style="text-align: center;">
All Rights Reserved. Created By  <a href="https://www.assamjobz.com" target="_blank">Assam Jobs</a>.
</div>
<div class="clear"></div>
</div></div>
</div>
</div>
<div class="footer-cap-bottom cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
</footer>
<!-- content -->
</div>
</div>
<div class="content-cap-bottom cap-bottom">
<div class="cap-left"></div>
<div class="cap-right"></div>
</div>
</div>
</div>
<script type="text/javascript">
    window.setTimeout(function() {
        document.body.className = document.body.className.replace('loading', '');
      }, 10);
  </script>
<script src="https://apis.google.com/js/plusone.js" type="text/javascript" gapi_processed="true"></script>

<script type="text/javascript" src="https://www.blogger.com/static/v1/widgets/1699748815-widgets.js"></script>
<script type="text/javascript">
window['__wavt'] = 'AOuZoY4mSFaMc40jJwAKRnwK6-C3aGenxQ:1650178871910';_WidgetManager._Init('//www.blogger.com/rearrange?blogID\x3d4600799949292916563','//assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html','4600799949292916563');
_WidgetManager._SetDataContext([{'name': 'blog', 'data': {'blogId': '4600799949292916563', 'title': 'Assam Jobs | Find Jobs in assam and North East', 'url': 'https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html', 'canonicalUrl': 'https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html', 'homepageUrl': 'https://assam-jobz.blogspot.com/', 'searchUrl': 'https://assam-jobz.blogspot.com/search', 'canonicalHomepageUrl': 'https://assam-jobz.blogspot.com/', 'blogspotFaviconUrl': 'https://assam-jobz.blogspot.com/favicon.ico', 'bloggerUrl': 'https://www.blogger.com', 'hasCustomDomain': false, 'httpsEnabled': true, 'enabledCommentProfileImages': true, 'gPlusViewType': 'FILTERED_POSTMOD', 'adultContent': false, 'analyticsAccountNumber': '', 'encoding': 'UTF-8', 'locale': 'en', 'localeUnderscoreDelimited': 'en', 'languageDirection': 'ltr', 'isPrivate': false, 'isMobile': false, 'isMobileRequest': false, 'mobileClass': '', 'isPrivateBlog': false, 'isDynamicViewsAvailable': true, 'feedLinks': '\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Assam Jobs | Find Jobs in assam and North East - Atom\x22 href\x3d\x22https://assam-jobz.blogspot.com/feeds/posts/default\x22 /\x3e\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/rss+xml\x22 title\x3d\x22Assam Jobs | Find Jobs in assam and North East - RSS\x22 href\x3d\x22https://assam-jobz.blogspot.com/feeds/posts/default?alt\x3drss\x22 /\x3e\n\x3clink rel\x3d\x22service.post\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Assam Jobs | Find Jobs in assam and North East - Atom\x22 href\x3d\x22https://www.blogger.com/feeds/4600799949292916563/posts/default\x22 /\x3e\n\n\x3clink rel\x3d\x22alternate\x22 type\x3d\x22application/atom+xml\x22 title\x3d\x22Assam Jobs | Find Jobs in assam and North East - Atom\x22 href\x3d\x22https://assam-jobz.blogspot.com/feeds/5778184567614263207/comments/default\x22 /\x3e\n', 'meTag': '', 'adsenseHostId': 'ca-host-pub-1556223355139109', 'adsenseHasAds': false, 'adsenseAutoAds': false, 'ieCssRetrofitLinks': '\x3c!--[if IE]\x3e\x3cscript type\x3d\x22text/javascript\x22 src\x3d\x22https://www.blogger.com/static/v1/jsbin/2068738220-ieretrofit.js\x22\x3e\x3c/script\x3e\n\x3c![endif]--\x3e', 'boqCommentIframeForm': false, 'loginRedirectParam': '', 'view': '', 'dynamicViewsCommentsSrc': '//www.blogblog.com/dynamicviews/4224c15c4e7c9321/js/comments.js', 'dynamicViewsScriptSrc': '//www.blogblog.com/dynamicviews/ca7d44e6ce638742', 'plusOneApiSrc': 'https://apis.google.com/js/plusone.js', 'disableGComments': true, 'sharing': {'platforms': [{'name': 'Get link', 'key': 'link', 'shareMessage': 'Get link', 'target': ''}, {'name': 'Facebook', 'key': 'facebook', 'shareMessage': 'Share to Facebook', 'target': 'facebook'}, {'name': 'BlogThis!', 'key': 'blogThis', 'shareMessage': 'BlogThis!', 'target': 'blog'}, {'name': 'Twitter', 'key': 'twitter', 'shareMessage': 'Share to Twitter', 'target': 'twitter'}, {'name': 'Pinterest', 'key': 'pinterest', 'shareMessage': 'Share to Pinterest', 'target': 'pinterest'}, {'name': 'Email', 'key': 'email', 'shareMessage': 'Email', 'target': 'email'}], 'disableGooglePlus': true, 'googlePlusShareButtonWidth': 0, 'googlePlusBootstrap': '\x3cscript type\x3d\x22text/javascript\x22\x3ewindow.___gcfg \x3d {\x27lang\x27: \x27en\x27};\x3c/script\x3e'}, 'hasCustomJumpLinkMessage': false, 'jumpLinkMessage': 'Read more', 'pageType': 'item', 'postId': '5778184567614263207', 'pageName': 'Assam Jobs', 'pageTitle': 'Assam Jobs | Find Jobs in assam and North East: Assam Jobs', 'metaDescription': ''}}, {'name': 'features', 'data': {'sharing_get_link_dialog': 'true', 'sharing_native': 'false'}}, {'name': 'messages', 'data': {'edit': 'Edit', 'linkCopiedToClipboard': 'Link copied to clipboard!', 'ok': 'Ok', 'postLink': 'Post Link'}}, {'name': 'template', 'data': {'name': 'Picture Window', 'localizedName': 'Picture Window', 'isResponsive': false, 'isAlternateRendering': false, 'isCustom': false, 'variant': 'shade', 'variantId': 'shade'}}, {'name': 'view', 'data': {'classic': {'name': 'classic', 'url': '?view\x3dclassic'}, 'flipcard': {'name': 'flipcard', 'url': '?view\x3dflipcard'}, 'magazine': {'name': 'magazine', 'url': '?view\x3dmagazine'}, 'mosaic': {'name': 'mosaic', 'url': '?view\x3dmosaic'}, 'sidebar': {'name': 'sidebar', 'url': '?view\x3dsidebar'}, 'snapshot': {'name': 'snapshot', 'url': '?view\x3dsnapshot'}, 'timeslide': {'name': 'timeslide', 'url': '?view\x3dtimeslide'}, 'isMobile': false, 'title': 'Assam Jobs', 'description': 'Assam Jobs Jobs in Assam and North East', 'url': 'https://assam-jobz.blogspot.com/2020/02/assam-jobs-assam-requirements-assam-job.html', 'type': 'item', 'isSingleItem': true, 'isMultipleItems': false, 'isError': false, 'isPage': false, 'isPost': true, 'isHomepage': false, 'isArchive': false, 'isLabelSearch': false, 'postId': 5778184567614263207}}]);
_WidgetManager._RegisterWidget('_NavbarView', new _WidgetInfo('Navbar1', 'navbar', document.getElementById('Navbar1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_HeaderView', new _WidgetInfo('Header1', 'header', document.getElementById('Header1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogView', new _WidgetInfo('Blog1', 'main', document.getElementById('Blog1'), {'cmtInteractionsEnabled': false, 'lightboxEnabled': true, 'lightboxModuleUrl': 'https://www.blogger.com/static/v1/jsbin/3413754346-lbx.js', 'lightboxCssUrl': 'https://www.blogger.com/static/v1/v-css/3523451998-lightbox_bundle.css'}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_FeaturedPostView', new _WidgetInfo('FeaturedPost1', 'main', document.getElementById('FeaturedPost1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PopularPostsView', new _WidgetInfo('PopularPosts1', 'main', document.getElementById('PopularPosts1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PopularPostsView', new _WidgetInfo('PopularPosts2', 'sidebar-right-1', document.getElementById('PopularPosts2'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_ProfileView', new _WidgetInfo('Profile1', 'sidebar-right-1', document.getElementById('Profile1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogArchiveView', new _WidgetInfo('BlogArchive1', 'sidebar-right-1', document.getElementById('BlogArchive1'), {'languageDirection': 'ltr', 'loadingMessage': 'Loading\x26hellip;'}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_PageListView', new _WidgetInfo('PageList1', 'sidebar-right-2-1', document.getElementById('PageList1'), {'title': '', 'links': [{'isCurrentPage': false, 'href': 'https://assam-jobz.blogspot.com/', 'title': 'Home'}], 'mobile': false}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_BlogSearchView', new _WidgetInfo('BlogSearch1', 'sidebar-right-2-2', document.getElementById('BlogSearch1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_ReportAbuseView', new _WidgetInfo('ReportAbuse1', 'sidebar-right-3', document.getElementById('ReportAbuse1'), {}, 'displayModeFull'));
_WidgetManager._RegisterWidget('_AttributionView', new _WidgetInfo('Attribution1', 'footer-3', document.getElementById('Attribution1'), {}, 'displayModeFull'));
</script>

</body></html>
