KC Group Website
================


This is a website for KC group. Please contact KC for maintain.


Maintaining Website
-------------------





Markdown simple guide
---------------------
The website uses jekyll as a static website generator. Jekyll uses markdown syntax for creating the content. The following is a simple guide for markdown.


**Headers**

The website supports two different headers.

    Section Header
    ==============
    
    Subsection Header
    -----------------

You may also use # for headers.

    # Section Header
    
    ## Subsection Header

Note that markdown supports up to six different headers with #. However, for 2~6 # are the same style in this website.




    
**Emphasis**

There are two text styling supported: **bold** and *italic*.

    **bold** or __bold__
    *italic* or _italic_


**Lists**

There are unordered list and ordered list, both very simple with markdown.

*Unordered List*

    * This is an example
    * of unordered list
    * you may use *, + and -.
    
*Ordered List*

    1. This is
    2. an example
    3. of ordered list.
    



**Linebreaks**

A single return in markdown is not considered a new paragraph. Remember to use more than two returns for separate paragraph.



**Links**

There are two ways for creating links, inline or reference.

*Inline-style*

    This is an [inline link](http://example.com).
    This is an [inline link](http://example.com "Optional Title").
    
*Reference-style*

    This is a [reference link][1].
    [1]: http://example.com "Optional Title"



**Images**

Images are a little less natural in markdown. However, it can still be done as follow.

*Inline-style*

    ![Alt text](img/image.jpg "Optional Title")
    
*Reference-style*
    
    ![Alt text][1]
    
    [1]: img/image.jpg "Optional Title"



**Escaping**

As you can see, a lot of symbols have functionality in markdown. To show them as what they are, you may use \\ to escape the symbols. Symbols that needs escaping are: 

    \, `, *, _, {}, [], (), #, +, -, ., !






Licence
-------

Data in img/ and _post/ are copyright by KC group. Other are under open source licence.
