Fast SASS / SCSS Utils
======================

Requires Compass for font-face mixin

Font
----

~~~ scss
@include load-font("FontFamily","folder/font-file-name");
~~~

Dimensions
----------

~~~ scss
.w500 {
  @include force-height(500px);
}
~~~