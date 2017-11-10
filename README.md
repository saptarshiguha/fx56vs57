Dear Reader,

This is an attempt to write Mozilla Data Science Reports using the R bookdown
package which converts R Markdown to Gitbook formats.

For an example of this document
see [here](https://metrics.mozilla.com/protected/sguha/sentiment/).

This is a rough template you can follow. Keep the following

- _output.yml
- _bookdown.yml
_ css/ folder
- images/ folder

And be sure to read the [manual](https://bookdown.org/yihui/bookdown/).
Also when you run the command `render_bookdown`, you'll need to copy both the
`css` and `images` folder to the output destination. Bookdown doesn't do that
(or maybe it does using some includes options?)
