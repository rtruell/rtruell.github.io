---
layout: post
title: "A test post"
date: 2014-06-11 12:58:03 -0600
comments: true
categories:
---
This is **bold using 2 asterisks** and this is __bold using 2 underscores__.

This is *italics using 1 asterisk* and this is _italics using 1 underscore_.

You can even combine both in order to **bold a part containing a *word* in italics**, using any combination of the above.

>This should be a block quote.  It's used to quote things that
>other people have said, possibly things that you heard or
>possibly things you've read in a paper, magazine or on-line.

>Or, create a block quote with just one long line, like this one.  This should be a block quote.  It's used to quote things that other people have said, possibly things that you heard or possibly things you've read in a paper, magazine or on-line.

# This is heading one (1)
## This is heading two (2)
### This is heading three (3)
#### This is heading four (4)
##### This is heading five (5)
###### This is heading six (6)

* unordered list item one using asterisk
* unordered list item two using asterisk
* unordered list item three using asterisk




1. ordered list item one
2. ordered list item two
3. ordered list item three




This is a link to [my web page](http://rtruell.ca/).

    Code blocks can be created by
    indenting with 4 spaces.  A
    blank line before and after
    the block is required.

All of the above are Markdown basics.  The following are all GFM or GitHub Flavored Markdown.

Although the underscore is normally used for italics, it is ignored when there are multiple ones in a word, such as do_this_and_do_that_and_another_thing.

If all that's needed is a clickable URL without text, then just enter it, such as http://rtruell.ca/.

Surrounding a word/phrase with two tildes (~) causes strikethrough text, as in the quick brown ~~cat~~ fox jumped over the lazy dog.  However, there is no Markdown way to underline words, so you have to use HTML, as in the quick brown <u>fox</u> jumped over the lazy dog.  Similarly, in order to do superscripts, you have to use E=MC<sup>2</sup> and for subscripts, H<sub>2</sub>O.

In GFM, you can use fences (3 tildes), instead of indenting 4 spaces, to create a code block, like this:

```
function test() {
  console.log("notice the blank line before this function?");
}

Note that a blank line before and after the fenced block isn't required, but makes the raw Markdown easier to read.
```
You can do syntax highlighting in a code block by adding a language identifier, like this:

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

Tables can be created using a dash to underline the first row and a pipe between columns.  Pipes at the start and end of each row can be used for aesthetic purposes, but aren't needed.  The number of dashes used to underline the first row don't have to match the length of the header text.

With pipes:





| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |





Without pipes:





 Third Header  | Fourth Header
 ------------- | -------------
 Content Cell  | Content Cell
 Content Cell  | Content Cell





You can also include inline Markdown such as links, bold, italics, or strikethrough:





| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a **window**     |





Finally, by including colons : within the header row, you can define text to be left-aligned, right-aligned, or center-aligned:





|  Left-Aligned   |  Center Aligned   |  Right Aligned  |
|  :-----------   |  :------------:   |  ------------:  |
|  col 3 is       |  some wordy text  |  $1600          |
|  col 2 is       |  centered         |  $12            |
|  zebra stripes  |  are neat         |  $1             |





`test test test`

1. item one
2. item two
3. item three


   This Is The First Header  |   This Is The Second Header  |   This Is The Third Header  
-----------------------------|------------------------------|-----------------------------
   Row1 Cell1                |   Row1 Cell2                 |   Row1 Cell3                
   Row2 Cell1                |   Row2 Cell2                 |   Row2 Cell3                
