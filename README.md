Contao jQuery selectBox
===================

Simple extension to provide the [jScrollPane plugin by marcj](http://jscrollpane.kelvinluck.com/) in Contao.

## Styling

If you want to create your own styles without overriding the default one, create your own `j_scrollpane` template and remove or disable the line `$GLOBALS['TL_CSS'][] = …` in the PHP section of the template or set the path to your own styles there.

## Configuration

In order to configure the default initialization, create your own `j_scrollpane` template and change the script part. By default, the scroll pane initializes with the CSS class `.scroll-pane` and with only the default options.