# Markdown Tutorial

This is a basic tutorial for creating markdown ( .md ) files for the _post / _projects directories. Once you have created the .md file add it to the relevent directory (either /_posts/ or /_projects/), also any images should go in the relevant directory (either /img/posts/ or /img/projects/). 

## File Name

The name of the file must follow a specific format for the paginator. The format is:
- YYYY-MM-DD-title-of-post.md

## Post / Project Header

Every post / project must begin with a header. This must include a layout, title and date. It may also optionally include a subtitle, author, and background. The following is an example header.

        ---
        layout: post
        title: "A Deeper Look at CC4D"
        subtitle: "A deep dive into our history, founders, achievements and the challenges we face."
        author: Mathew Lubari
        date: 2023-03-21
        background: '/img/posts/repair-culture.jpg'
        ---

Some notes:
1. The layout has the following options: post, project (if you are making a blog post use 'layout: post', if you are making a project post use 'layout: project')
2. The date is: YYYY-MM-DD
3. Place images in the appropriate directories (/img/posts/ or /img/projects/)

## Markdown Basics

I will only touch on the basics, a more thorough introduction can be found [here](https://www.markdownguide.org/basic-syntax/).

#### Headings
A heading can be created using the # symbol. You can alter the size of the heading by increasing the number of #'s (# through ######). Example:

        # Heading 1
        ### Heading 3
        ###### Heading 6 

# Heading 1
### Heading 3
###### Heading 6 

### Paragraphs
Paragraphs are just typed inline with no symbol required (this is a paragraph).

### Bold Text
Bold text is created by surrounding a word or sentence with two sets of **..

        **This is a bold sentence.**  
        You can also **bold** specific words by surrounding them with **.

**This is a bold sentence.**  
You can also **bold** specific words by surrounding them with **.

### Italicized Text 
Italicized text is created by surrounding a word or sentence with two sets of *..

        *This is an italicized sentence.*  
        You can also *italicize* a specific words by surrounding them with *.

*This is an italicized sentence.*  
You can also *italicize* a specific words by surrounding them with *.

### Bold and Italicized Text
Bold and italicized text is created by surrounding a word or sentence with two sets of ***

        ***This is a bold and italicized sentence.***  
        You can also ***bold and italicize*** specific words by surrounding them with ***.

***This is a bold and italicized sentence.***  
You can also ***bold and italicize*** specific words by surrounding them with ***.

### Hyperlinks

Hyperlinks have two parts, the text part is created by enclosing the text in square brackets [CC4D] and the link immediatedly follows it inside parentheses (https://cc4d.tech/).

        So a hyperlink to the CC4D site would look like this [Community Creativity for Development](https://cc4d.tech/).

That exact link would look like this: [Community Creativity for Development](https://cc4d.tech/)

### Images

Images have two parts, the alt text is create by an exclamation mark followed by the alt text enclosed in square brackets ![The CC4D logo] and the path or URL immediately follws it inside parentheses (/img/cc4d-logo.jpg)

        So an image link for the CC4D logo would look like this ![The CC4D logo](/img/cc4d-logo.jpg)

![The CC4D logo](/img/cc4d-logo.jpg)