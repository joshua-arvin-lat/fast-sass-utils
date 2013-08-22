Fast SASS / SCSS Utils
======================

Requires Compass for font-face mixin

Font
----

~~~ scss
@include load-font("FontFamily","folder/font-file-name");
~~~

Layout Classes
--------------

- left
- right
- clear

~~~ html
<div class='left'>Content</div>
<div class='left'>Content</div>
<div class='left'>Content</div>
<div class='right'>Content</div>
<div class='clear'>Clear Fix</div>
~~~

Dimensions
----------

~~~ scss
.h500 {
  @include force-height(500px);
}

.w500 {
  @include force-width(500px);
}
~~~

Quick Background Classes
------------------------

- bg-white  
- bg-red  
- bg-blue  
- bg-green

Quick Padding Classes
---------------------

- pad-top-10, pad-top-20, pad-top-30
- pad-bottom-10, pad-bottom-20, pad-bottom-30
- pad-right-10, pad-right-20, pad-right-30
- pad-left-10, pad-left-20, pad-left-30

Quick Margin Classes
--------------------

- right10, right20, right30
- left10, left20, left30
- bottom10, bottom20, bottom30
- top10, top20, top30
