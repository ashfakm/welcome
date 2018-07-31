/* http://meyerweb.com/eric/tools/css/reset/ 2. v2.0 | 20110126
  License: none (public domain)
*/

html, body, div, span, applet, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
a, abbr, acronym, address, big, cite, code,
del, dfn, em, img, ins, kbd, q, s, samp,
small, strike, strong, sub, sup, tt, var,
b, u, i, center,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, embed,
figure, figcaption, footer, header, hgroup,
menu, nav, output, ruby, section, summary,
time, mark, audio, video {
  margin: 0;
  padding: 0;
  border: 0;
  font-size: 100%;
  font: inherit;
  vertical-align: baseline;
}
/* HTML5 display-role reset for older browsers */
article, aside, details, figcaption, figure,
footer, header, hgroup, menu, nav, section {
  display: block;
}
body {
  line-height: 1;
}
ol, ul {
  list-style: none;
}
blockquote, q {
  quotes: none;
}
blockquote:before, blockquote:after,
q:before, q:after {
  content: '';
  content: none;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}

                  
With our main.css file starting to take shape, let’s connect it to our index.html file. Opening the index.html file in our text editor, let’s add the <link> element within our <head> element, just after the <title> element.

Because we’ll be referencing a style sheet within the <link> element, let’s add the relation attribute, rel, with a value of stylesheet.

We also want to include a hyperlink reference, using the href attribute, to our main.css file. Remember, our main.css file is saved within the “stylesheets” folder, which is inside the “assets” folder. Therefore, the href attribute value, which is the path to our main.css file, needs to be assets/stylesheets/main.css.

1
2
3
4
5
6
<head>
  <meta charset="utf-8">
  <title>Styles Conference</title>
  <link rel="stylesheet" href="assets/stylesheets/main.css">
</head>

