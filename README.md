jQuery UI - WP Admin Theme
==========================

Javascript files for [jQuery UI](http://jqueryui.com/) are shipped with WordPress core, not so css files.

This repo contain less files to build a css theme for jQuery UI that don't clash too much with WordPress admin styles.

Widget colors changes according to current admin color theme (currently, only the default 8 admin themes are supported).

#Usage

The file [`jquery-ui.less`](jquery-ui.less) includes all the files in right order, so just compile it with your favourite tool.

jQuery UI needs some images for icons, repo contain that images in the `img` subfolder.
If you move the images folder, open the `jquery-ui.less` file and on [first line](jquery-ui.less#L1) adjust the less variable `@imgpath` accordingly.

#License

Less code I wrote is released under MIT (include css code from jQuery UI, released under MIT).

Icon images are copyright of jQuery Foundations and [released under MIT](https://jquery.org/license/).
