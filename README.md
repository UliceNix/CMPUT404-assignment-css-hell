Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Code is licensed under the Apache 2.0 license.

Documentation on Changes in Part 1
==================================

* Linked one css file "masterStyleSheet.css" to each gutenberg HTML file by
  using "<link rel="stylesheet" href="masterStyleSheet.css">"
* Created a linear-gradient to simulate the old book feel. Honestly, mine may
  be too old as it's inspired by looking at my Edgar Allan Poe stories book
  published in early 1900s. And in case linear-gradient is not supported in
  some browser, a pure colour was set as the fallback.
* Overridden the header font to be Baskerville, "Baskerville Old Face",
  "Goudy Old Style", Garamond, "Times New Roman", serif
* Specifically set h2s to have a double lined border, and positioned it properly
  by using margin and padding.
* Set the font in p to be "Palatino Linotype", "Book Antiqua", Palatino, serif;
  and spaced them rather generously by using letter-spacing: 0.1 em and
  line-height: 2em to match the old book look.
* Styled the img tags with a double lined border, and a sepia filter to make
  them look rather old. Since most of the images are centered by the designer's
  original purpose, I did not play with position to create in-line effects,
  because that would defy the semantic meaning of classes of the images' parent
  div.
* Made the images' caption class to use an italic font style.
* Styled the a tags, specifically links, with a transparent background color,
  set the text in a tags to be brown and bold. And for visited links, changed
  the text colour to rosybrown.
* Positioned pre tags by margin-left: 10% to create a consistent style over
  these three html files.
* Styled table tags by setting the table to use font-family: "Palatino Linotype",
  "Book Antiqua", Palatino, serif; and centered.
  And for td tags,   height: 2em and vertical-align: middle were set.
  table and td tags were mainly used for content tables.
