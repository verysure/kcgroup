KC Group Website
================


This is a website for KC group. Please contact KC for maintain.


Maintaining Website
-------------------
This website uses jekyll as a static website generator. Jekyll will render the markdown posts in `_posts/` folder. Some important things to notice:

- Posts filename should be `YEAR-MO-DA-TITLE.md`
- In the beginning of each file you should add the following block:
    
    ---
    title: Title
    secid: secitonid
    order: somenumber
    ---
    
  `title` is for the text that show in navbar, doesn't need to be the same with post title. `secid` is for the webpage to target the posistion to scroll to, needs a unique name but not important. `order` is for how you order the posts in the webite.
  





Markdown simple guide
---------------------
Markdown is an intuitive and fast way for content editing. The following is a simple guide. There is also a more complete guide [here][4].

**Headers**

The website supports two different headers.

    Section Header
    ==============
    
    Subsection Header
    -----------------

You may also use # for headers.

    # Section Header
    
    ## Subsection Header

Note that markdown supports up to six different headers with #. However, for header 2~6 #s are the same in this website style.




    
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

    \ ` * _ {} [] () # + - . !






Licence and Credit
------------------

Data in `img/` and `_post/` are copyrighted by KC group. All other code are Code released under the Apache 2.0 license. Styling uses [Bootstrap][1] ([Agency][2]) and [Font Awesome][3].


[1]: http://getbootstrap.com/
[2]: http://startbootstrap.com/template-overviews/agency/
[3]: http://fortawesome.github.io/Font-Awesome/
[4]: http://daringfireball.net/projects/markdown/