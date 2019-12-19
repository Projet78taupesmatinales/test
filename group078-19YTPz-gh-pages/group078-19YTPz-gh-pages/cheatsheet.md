## Cheat Sheet: Resources
This section shows how to embed resources (images, videos, pdf files) in your pages.

### Image from the web
```
![](https://i.ibb.co/mGKNtTT/logo.jpg)
```
![](https://i.ibb.co/mGKNtTT/logo.jpg)

### Image from `assets/images/` folder
```
![](assets/images/cover.jpg)
```
![](assets/images/cover.jpg)


### Image size
```
![](assets/images/logo.jpg){:width="20%"}
```
![](assets/images/logo.jpg){:width="20%"}


## Embed video (from YouTube)
Copy the code below to whatever page you want your video in, then replace `[video_id]` with your own YouTube video's id (the bit after `watch?v=` in the video's link)
```
<div class="aspect-ratio video">
  <iframe src="https://www.youtube.com/embed/[video_id]" frameborder="0" allowfullscreen="True"></iframe>
</div>
```
<div class="aspect-ratio video">
  <iframe src="https://www.youtube.com/embed/uWSxzjyMNpU" frameborder="0" allowfullscreen="True"></iframe>
</div>

## Embed PDF

In the code bellow, change `assets/pdf/a4.pdf` in front of `data` and `href` attributes to the address of your PDF file. If you have uplaoded your PDF files in `assets/pdf` folder then simply change `a4` to the name of your PDF file.
```
<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/a4.pdf">here</a> to download the file</p>
  </object>
</div>
```
<div class="aspect-ratio document">
  <object data="assets/pdf/a4.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/a4.pdf">here</a> to download the file</p>
  </object>
</div>

You can also save and upload your PowerPoints as PDF.
```
<div class="aspect-ratio document">
  <object data="assets/pdf/powerpoint.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/powerpoint.pdf">here</a> to download the file</p>
  </object>
</div>
```
<div class="aspect-ratio document">
  <object data="assets/pdf/powerpoint.pdf" type="application/pdf">
    <p>This browser does not support PDF! Click <a href="assets/pdf/powerpoint.pdf">here</a> to download the file</p>
  </object>
</div>


# Cheat Sheet: Styling with Markdown
Markdown is a way to **style** text on the web. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. Mostly, Markdown is just regular text with a few non-alphabetic characters thrown in, like `#` or `*`.

You can use Markdown in your repository files with the `.md` or `.markdown` extension. For more info see  [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

## Examples of all the markdowns you'll need!

Writing what you see in each box will style your text as what follows the box.

### Here's headers
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
```
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5

### Here's paragraphs
```
## This is a header
This is a normal paragraph following a header.
This is **not** another paragraph.

But this is.

There should be whitespace (an empty line) between paragraphs.
```

## This is a header
This is a normal paragraph following a header.
This is **not** another paragraph.

But this is.

There should be whitespace (an empty line) between paragraphs.


### Here's text styles
```
Text can be **bold**, _italic_, or ~~strikethrough~~.
```
Text can be **bold**, _italic_, or ~~strikethrough~~.

```
[Link to one of your pages](resources.md).
[Link to external webpage](http://www.sciencespo.fr).
```
[Link to one of your pages](resources.md).
[Link to external webpage](http://www.sciencespo.fr).

```
> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.
```
> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Here's a horizontal rule
```
* * *
```
* * *

### Here's an unordered list:
```
*  A level 1 item in an unordered list.
*  A level 1 item.
*  A level 1 item.
  *  A level 2 item.
  *  A level 2 item.
*  A level 1 item.
  *  A level 2 item.
    *  A level 3 item.
```
*  A level 1 item in an unordered list.
*  A level 1 item.
*  A level 1 item.
  *  A level 2 item.
  *  A level 2 item.
*  A level 1 item.
  *  A level 2 item.
    *  A level 3 item.

### Here's an ordered list:
```
1.  A level 1 item in an unordered list.
1.  A level 1 item.
1.  A level 1 item.
  1.  A level 2 item.
  1.  A level 2 item.
1.  A level 1 item.
  *  A level 2 item.
  *  A level 2 item.
```
1.  A level 1 item in an unordered list.
1.  A level 1 item.
1.  A level 1 item.
  1.  A level 2 item.
  1.  A level 2 item.
1.  A level 1 item.
  *  A level 2 item.
  *  A level 2 item.


### Here's a table

```
| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |
```

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### Here's a box
```
The final element.
```
