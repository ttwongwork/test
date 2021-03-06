An h1 header
============

[!VIDEO /ExcelVideomp4.mp4]
 

![what a cutie.jpg](what%20a%20cutie.jpg)

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look like:

  * this one
  * that one
  * the other one

Note that --- not considering the asterisk --- the actual text
content starts at 4-columns in.

> Block quotes are
> written like so.
>
> They can span multiple paragraphs,
> if you like.
Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all
in chapters 12--14"). Three dots ... will be converted to an ellipsis.
Unicode is supported. ☺

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
| <ul><li>item1</li><li>item2</li></ul>| See the list | from the first column|

```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```
| Fun                  | With                 | Tables          |
| :------------------- | -------------------: |:---------------:|
| left-aligned column  | right-aligned column | centered column |
| $100                 | $100                 | $100            |
| $10                  | $10                  | $10             |
| $1                   | $1                   | $1              |

|                  |Header 1 |Header 2|
|------------------|---------|--------|
|**First column A**|Cell 1A  |Cell 2A |
|**First column B**|Cell 1B  |Cell 2B |


![NOTE] ABC

> [!NOTE]
> If your app isn't listed in the Azure portal, you can target it with a policy by selecting the **more apps** option, and providing the package name in the text box.

An h2 header
------------

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it:

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print(i)
~~~



### An h3 header ###

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a link to [a website](http://foo.bar), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Some footnote text.

Tables can look like this:

Name           Size  Material      Color
------------- -----  ------------  ------------
All Business      9  leather       brown
Roundabout       10  hemp canvas   natural
Cinderella       11  glass         transparent

Table: Shoes sizes, materials, and colors.

(The above is the caption for the table.) Pandoc also supports
multi-line tables:

--------  -----------------------
Keyword   Text
--------  -----------------------
red       Sunsets, apples, and
          other red or reddish
          things.

green     Leaves, grass, frogs
          and other things it's
          not easy being.
--------  -----------------------

A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.

oranges
  : Citrus!

tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term and  its definition to spread things out more.)

Here's a "line block" (note how whitespace is honored):

| Line one
|   Line too
| Line tree

and images can be specified like so:

DOESN'T PROCESS
![gray-and-white-cat-asleep-with-whiskers-out](https://user-images.githubusercontent.com/71405968/93397513-9c23d700-f82e-11ea-8ecd-7dab041e877e.jpg)

DOESN'T PROCESS
![](https://github.com/ttwongwork/test/blob/master/gray-and-white-cat-asleep-with-whiskers-out.jpg)

DOESN'T PROCESS
![](https://github.com/ttwongwork/test/blob/master/cat-sleeping-e1562875994725.jpg)

ATTEMPT
![cat-sleeping-e1562875994725.jpg](https://github.com/ttwongwork/test/blob/master/cat-sleeping-e1562875994725.jpg)



Inline math equation: $\omega = d\phi / dt$. Display
math should get its own line like so:

$$I = \int \rho R^{2} dV$$

And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.

Local reference as image reference? PROCESS OK
![gray-and-white-cat-asleep-with-whiskers-out.jpg](gray-and-white-cat-asleep-with-whiskers-out.jpg)

Local reference as link. 
[cat-sleeping-e1562875994725.jpg](cat-sleeping-e1562875994725.jpg)


From third party link- DOESN'T PROCESS
![https://blog.entirelypets.com/wp-content/uploads/2017/04/14718789_ML.jpg](https://blog.entirelypets.com/wp-content/uploads/2017/04/14718789_ML.jpg)

Local reference as image reference?

![what a cutie](https://github.com/ttwongwork/test/blob/master/what%20a%20cutie.jpg?raw=true)
 


