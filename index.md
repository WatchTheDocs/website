# WatchTheDocs

Create video tutorials from Markdown scripts.


| Markdown script   | -> |  Slideshow       | ->  | Video               |
|-------------------|----|------------------|-----|---------------------|


* **Script.** This is where creating a video
  usually starts. With WatchTheDocs, it's also
  where the most tricky part ends! Markdown
  is used for both slides content and voice-over.
* **Slideshow.** Generated automatically from
  the markdown script, along with a decent voice-over.
  Even if you plan to record your own voice,
  the automatic one is usually a good start.
* **Video.** The slideshow can be converted
  to a traditional video format, to watch
  separately, upload on YouTube
  or share on social networks.

## Example

Script:

```markdown
    # The Title

    Paragraphs directly following the main title
    used for the description.

    They don't end up in the slideshow or voice-over.

    ## First slide starts here

    A header starts a new slide.
    It will be used as the slide title.

    Paragraphs following the header form voice-over for that slide.

    ## Second Slide Title

    Here is a slide with an image:

    ![The Image](images/pic1.png)

    A paragraph immediately preceeding the image
    and all the following paragraphs end up in
    the voice-over.

    It can be really verbose...

    But here it breaks, and a new slide starts!
    That's because the current paragraph
    is followed by another image:

    ![Another Image](images/pic2.png)

    ## Tables and Blocks

    | Col 1     | Col 2     |
    |-----------|-----------|
    | Row with  | two cells |

    Similarly to the images,
    each table and code block goes to a separate slide.
    Above is an example of a table.

    And here is a code block:

        function hello() {
            alert('Hello, World!');
        }

    If you want to render text on a slide, simply
    make a blockquote:

    > Yay! I can put some text on my slide!

    ## Lists

    Lists work a bit differently:

    * They appear on slides.
      But only the first sentence
      of each list item is rendered.
    * They also generate voice-over. 
      And it can be quite verbose.
    * They can be numbered or ordered.

    Just like with images and blocks, a single paragraph
    that preceeds the list and a sequence of paragraph
    that follows it form voice-over for the slide.
    
```

Slideshow:

TODO!

Video:

TODO!
