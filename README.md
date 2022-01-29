Readme Syntax Guide
===================

```
Note: This is Raw Syntax
```
Note: And this is actual Syntax

Headings
--------
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------
```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------

Line Segement
-------------
```
_____________________
```
_____________________

Line Breaks
-----------
My basic recommendation for learning how line breaks work is to experiment and discover -- hit <Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.

Here are some things to try out:
```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
```
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.

Basic Operations on Text
------------------------
```
**Bold** or Select Text and press ctrl+b

_Italic_ or *Italic* or Select Text and press ctrl+i

***Bold and Italic***

**Bold and _nested italic_**

_Italic and **nested bold**_

Strikethough: ~~Scratch This~~
```
**Bold** or Select Text and press ctrl+b

_Italic_ or *Italic* or Select Text and press ctrl+i

***Bold and Italic***

**Bold and _nested italic_**

_Italic and **nested bold**_

Strikethough: ~~Scratch This~~


List
----
```
#### Ordered List
1. Element 1
2. Element 2
3. Element 3

#### Unordered list can use asterisks
- Or minuses
+ Or pluses

#### Nested List
1. First list item
   - First nested list item
     - Second nested list item
2. Second list item
```
#### Ordered List
1. Element 1
2. Element 2
3. Element 3

#### Unordered list can use asterisks
- Or minuses
+ Or pluses

#### Nested List
1. First list item
   - First nested list item
     - Second nested list item
2. Second list item

Checkbox
--------
```
- [ ] Unchecked Box
- [x] Checked Box
```
- [ ] Unchecked Box
- [x] Checked Box

Images
------
```
Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
```

Here's our logo (hover to see the title text):

Inline-style: 
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style: 
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"

Links
-----
```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com
```
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

Code
----
Note: Raw syntax is not availabe, see raw text file instead of GitHub Preview 
#### Javascript
```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
#### python
```python
s = "Python syntax highlighting"
print s
```
#### No Language
```
No language indicated, so no syntax highlighting. 
But let's throw in a <b>tag</b>.
```

Highlighting 
------------
```
Following Text will be Highlighted

`Sample Text Highlighted`
```
Following Text will be Highlighted

`Sample Text Highlighted`

Tables
------
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
```
Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

YouTube Videos(Incompleted)
---------------------------
They can't be added directly but you can add an image with a link to the video like this:
```
<a href="http://www.youtube.com/watch?v=yzeVMecydCE&t=2147s
" target="_blank"><img src="http://img.youtube.com/vi/watch?v=yzeVMecydCE&t=2147s/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
```
<a href="http://www.youtube.com/watch?v=yzeVMecydCE&t=2147s
" target="_blank"><img src="http://img.youtube.com/vi/watch?v=yzeVMecydCE&t=2147s/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
