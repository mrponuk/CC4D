# HTML Tutorial

This is a basic tutorial for creating html ( .html ) files for the _blog / _projects directories. Once you have created the .html file add it to the relevent directory (either /_blog/ or /_projects/), also any images should go in the relevant directory (either /img/blog/ or /img/projects/).

## File Name

The name of the file must follow a specific format for the paginator. The format is:
title-of-post.html

## Blog / Project Header

Every blog / project must begin with a header. This must include a layout, title and date. It may also optionally include a subtitle, author, and background. The following is an example header.

    ---
    layout: blog
    title: "A Deeper Look at CC4D"
    subtitle: "A deep dive into our history, founders, achievements and the challenges we face."
    author: Mathew Lubari
    date: 2023-03-21
    background: '/img/blog/repair-culture.jpg'
    ---

Some notes:
1. The layout has the following options: blog, project (if you are making a blog post use 'layout: blog', if you are making a project post use 'layout: project')
2. The date is: YYYY-MM-DD
3. Place images in the appropriate directories (/img/blog/ or /img/projects/)

## HTML Basics

I will only touch on the basics, a more thorough introduction can be found [here](https://www.markdownguide.org/basic-syntax/).

#### Headings
A heading can be created by putting the header text inbetween &lt;h1> &lt;/h1> tags. You can alter the size of the heading by changing the number after the h (&lt;h1> through &lt;h6>). Example:

    <h1> Heading 1 </h1>
    <h3> Heading 3 </h3>
    <h6> Heading 6 </h6>

<h1> Heading 1 </h1>
<h3> Heading 3 </h3>
<h6> Heading 6 </h6>

### Paragraphs
A paragraph can be created by putting the paragraph inbetween &lt;p> &lt;/p> tags.


### Line Breaks 
To add a new line to a paragraph end the line with &lt;br>

    <p> 
    This is a paragraph with a line break. <br>
    The line break adds a new line inbetween the sentences.
    <p>

<p> 
This is a paragraph with a line break. <br>
The line break adds a new line inbetween the sentences.
<p>

### Bold Text

Bold text is created by surrounding a word or sentence with the &lt;strong> &lt;/strong> tags.

    <strong>This is a bold sentence.</strong> <br>
    You can also <strong>bold</strong> specific words by surrounding them with <strong> </strong>.

<strong>This is a bold sentence.</strong> <br>
You can also <strong>bold</strong> specific words by surrounding them with &lt;strong> &lt;/strong>.

### Italicized Text 
Italicized text is created by surrounding a word or sentence with &lt;i> &lt;/i>.

    <i>This is an italicized sentence.</i> <br>
    You can also <i>italicize</i> a specific words by surrounding them with <i> </i>.

<i>This is an italicized sentence.</i> <br>
You can also <i>italicize</i> a specific words by surrounding them with &lt;i> &lt;/i>.

### Bold and Italicized Text
Bold and italicized text is created by surrounding a word or sentence with two sets of ***

    <i><strong>This is a bold and italicized sentence.</strong></i> <br>
    You can also <i><strong>bold and italicize</strong></i> specific words by surrounding them with <i><strong> </strong></i>.

<i><strong>This is a bold and italicized sentence.</strong></i> <br>
You can also <i><strong>bold and italicize</strong></i> specific words by surrounding them with &lt;i>&lt;strong> &lt;/strong>&lt;/i>.

### Hyperlinks

Hyperlinks use the &lt;a> &lt;/a> tag, the link text itself goes inbetween the tags. Inside the inital &lt;a> tag there are a few elements that should be included:

    class="text-decoration-none text-primary" 
This  is just for formatting the link text so that it matches the rest of the site, this makes the link text light green and dark green on hover.

    href="site_to_link_to.com" 
The href is where you want to point the link text to.

    target="_blank" 
This just opens the link in a new tab instead of the the tab you are currently viewing the page in.

    rel="noopener noreferrer"
This is a safety feature. It is mostly redundant but there are still some browsers that are vulnerable. If you want to learn more about it check out this [OWASP post about Reverse Tabnapping](https://owasp.org/www-community/attacks/Reverse_Tabnabbing).

    So a hyperlink to the CC4D site would look like this:

    <a class="text-decoration-none text-primary" href="https://cc4d.tech/" target="_blank" rel="noopener noreferrer">Community Creativity for Development</a>

So a hyperlink to the CC4D site would look like this:

<a class="text-decoration-none text-primary" href="https://cc4d.tech/" target="_blank" rel="noopener noreferrer">Community Creativity for Development</a>
