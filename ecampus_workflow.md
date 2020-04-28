# Ecampus Markdown Workflow

My name is Eric Ianni and I would like to welcome you to my webinar on using Markdown to make course development easier on both you and Ecampus. This is the approach I developed to help me during my first course development assignment.

##  Webinar Learning Objectives (WLOs)

At the end of this webinar, attendees will be able to...

1. **Describe** how Markdown can be used to generate Canvas content
2. **Demonstrate** simple Markdown commands

# What is Markdown?

_Markdown_ is actually a mark**UP** language (think HTML and LaTeX). It was introduced in 2004 as a way to let people _easily_ write human readable content that could be easily converted into HTML. To demonstrate this readability let's look at a small example:

Content as shown in the browser:
#### Top Reasons to Develop a Course
1. You are **told**
2. You are experiencing a sense of _ennui_
3. ~~You don't have enough to do~~
___
The HTML used by the browser:

```HTML
<h4>Top Reasons to Develop a Course</h4>
<ol>
	<li>You are <strong>told</strong></li>
	<li>You are experiencing a sense of <em>ennui</em></li>
	<li><del>You don't have enough to do</del></li>
</ol>

```
___
Markdown used to produce the HTML:

```markdown
#### Top Reasons to Develop a Course
1. You are **told**
2. You are experiencing a sense of _ennui_
3. ~~You don't have enough to do~~

```

When reading raw HTML, a person needs to mentally discard all the tags. Markdown's "tags" are much more understated, thus not disrupting reading as much. Also, Markdown's syntax also is much more condensed, making it easier to write.

## Why use Markdown?

So what can Markdown do for us as course developers? Why would we want to use it instead of using Canvas directly or another word processor like Word?

### Rich Text Editors are the Worst

How many times have you wanted to include something as simple as a code snippet in your content only to be thwarted by the _Rich Text Editor_?

![Let's change this to code!](./images/rich_text1.png)  
Suppose you want to make "mystery_func" in the following example into a code snippet. We highlight it and select preformatted.

![Curses!](./images/rich_text2.png)  
Clearly this didn't work as we expected! The only solution Canvas offers is to use the _HTML Editor_, which is tedious and not the easiest if you are unfamiliar with HTML.

* Can include HTML right in markdown, like Replits

## Common Markdown
* Headers
* text emphasis

## Writing Markdown
### The Correct Way - Emacs
### VS Code

# Enter GitHub
## GitHub Markdown
## GitHub Pages

# What about Ecampus?

## Trello

* Columns
* Labels
* Checklists
* URLs in the comments

## Be Kind to your ID

* Identify the name of your images next to your images
* Upload images directly to Canvas

## Things your ID can do to help

* Collapsable elements
* Importing into Canvas
* Make it look nice



