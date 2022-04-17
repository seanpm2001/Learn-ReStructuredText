
***

![/RST.png](/RST.png)

### Learning ReStructuredText

I am not too experienced with ReStructuredText at the moment. This document will go over my knowledge of the ReStructuredText language so far.

This document uses the revision 8407 version of the ReStructuredText markup language.

#### Comments in ReStructuredText

I don't have comments down in ReStructuredText yet. I believe they are formatted like this:

```ReStructuredText
	..
	This is a comment
	..
	..
	From what I know, comments need to be indented, and single line comments don't exist
	..
```

#### Break keyword in ReStructuredText

ReStructuredText does not support the break statement/keyword.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Headings in ReStructuredText

Headings in RST work like so:

```ReStructuredText
=====
Document Heading (Heading 1)
=====

Heading 2
=====

Subheading (Heading 3)
-----

```

_/!\ This example has not been tested yet, and may not work_

#### Lists in ReStructuredText

Lists can be formed in ReStructuredText in multiple ways. The following examples showcase bullet lists, and numbered lists.

##### Bullet list

```ReStructuredText
* Bullet list entry 1
* ReStructuredText
* Python 3
* Python 2
* Python 1
```

##### Numbered list

```ReStructuredText
1. Entry 1
2. Entry 2
3. Python 3
4. Python 4?
5. HTML5
```

#### Bold in ReStructuredText

Text can be bolded in RST by doing the following:

```ReStructuredText
This text is not bold

**This text is bold**
```

#### Italics in ReStructuredText

Text can be italicized in RST by doing the following:

```ReStructuredText
This text is not italicized

*This text is italicized*
```

#### Code blocks in ReStructuredText

A code block can be formed in RST by doing the following:

```ReStructuredText
Some Python program

``print("Hello World")``
```



##### Images in ReStructuredText

Referencing an image in ReStructuredText is very easy, and is done like so:

```ReStructuredText
.. image:: Sample.svg
    :alt: Image

![Image](Sample.svg "icon")
```

The image is first referenced. The `:alt:` line is for displaying text for when the image doesn't look (most commonly, when it isn't found) then the image is referenced on the last line, and it prints it out in the document.

#### Horizontal Lines in ReStructuredText

Horizontal Lines/divider lines are supported in ReStructuredText. They can be defined like so:

```ReStructuredText

***

Lined section

***

	..
	The lines look the same with asterisks or hyphens
	..

---

Lined section 2

---

```

#### Hyperlinks in ReStructuredText

Hyperlinks are supported in ReStructuredText. They can be defined like so:

```ReStructuredText

Link1_.

.. _Link1: #footer

Footer
====

```

#### Source

The majority of my ReStructuredText knowledge comes from [the official Wikipedia page](https://en.wikipedia.org/wiki/ReStructuredText/) it also comes from self experimentation, notably with this repository:

[ReStructuredText Sandbox](https://github.com/seanpm2001/ReStructuredText_Sandbox/)

#### Other knowledge of ReStructuredText

1. ReStructuredText is not a curly bracket language, and also does not use semicolons at the end of each line

2. ReStructuredText is a lighweight markup language

3. ReStructuredText is most widely used in the Python programming community for documentation.

4. ReStructuredText uses the `.rst` file extension

5. ReStructuredText is a language recognized by GitHub, but you have to use a `.gitattributes` file to recognize it in the GitHub Linguist

6. ReStructuredText is a markup language

7. ReStructuredText can be shortened to either RST or ReST.

8. No other knowledge of ReStructuredText at the moment.

***

**File version:** `1 (2022, Saturday, April 16th at 5:40 pm PST)`

***
