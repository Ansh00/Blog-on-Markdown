# What is Markdown?
Markdown is a way to style text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like # or *.

You can use Markdown most places around GitHub:

Gists
Comments in Issues and Pull Requests
Files with the .md or .markdown extension.



# Basics of Markdown

Markdown is the most popular markup language that can be used to format documents. It can be used to create *websites*,*ebooks*,*email*,*chats in discussions forums*.

## Topics
1. Paragraphs 

    MD expects a full line space to show texts in a different line else it joins text in the same line.

2.  Text decorations

    MD can write **bold** texts, ~~italiic~~ *italic*  texts
3. Headings
    No of #'s represent the type of heading. Github will automatically add id's to headings, so the text will be automatically linked. 
    ## This is h2
    ### This is h3
4. Links

   [My Github](https://github.com/Ansh00 "all repos") account.[Anshul] github repo.

5. Images
    Images can be used just like links. ![Alt txt](img url)

    !["Dog Img"](https://images.unsplash.com/photo-1517849845537-4d257902454a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=375&q=80)

    Thumbnails images can also be used which links to larger image 
    [<img src="http://www.weforanimals.com/thumbnails/thumbnailsindex_files/8_small.jpg">](http://www.weforanimals.com/thumbnails/thumbnailsindex_files/8_small.jpg)

6. Ordered and Unordered Lists

    Coding Best Practices:

    * Keep code DRY
    * Writing Unit Test cases
    * Checking cross-browser support

    Steps to merge branch:

    1. Create a branch from feature
    1. commit your changes
    1. push your changes
    1. raise a pull request

7. Code Blocks

    This is super helpful when posting any code snippet


    ```js
    const fn = () => alert("some fn");
    ```




    ```css
    .hide {
        display:none
    }
    ```


    Also can show code difference


    ```diff
    var x = 10;
    - const counter = 0;
    + let counter = 0
    ```



8. Tables 

    Tables can be generated with headings and text alignment option

    |Stocks|Price|
    |:-----:|------:|
    |APPLE|4000|
    |REALME|500|

9. Blockquotes

    As Kanye West said:

> We're living the future so
> the present is our past.

10. Inline code

    I think you should use an
`<addr>` element here instead.

11. Task Lists

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


Cool Tips 

 * [ScreenTOGif](https://www.screentogif.com/) to record videos in GIF format
 * Upload GIF's to [giphy](https://giphy.com/) to embed them into blog posts.
 

# Extras:-
