# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [True ] `<div><span>hello</div></span>`

b) [ ]

```html
<ul>
<li>one</li>
</ol>
```

c) [ ] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

A “screen reader” is a software application that converts the text displayed on a computer screen into synthesized speech. Text-to-speech capabilities are a vital component of AI assistants such as Apple’s Siri and Amazon’s Alexa, which “talk” with users by converting their replies into digital speech. Screen readers are a specific use case of text-to-speech technology that improve accessibility for people with visual disabilities.

These days the market offers many options for screen readers. Some are intended for use with different operating systems and applications; some are free and open source; others are commercial software. A few of the most popular screen readers are JAWS, NVDA, ZoomText for Windows and  VoiceOver for Apple products.

why should we care about them?
 because By accommodating screen readers, we will go a long way in making our website more accessible to millions of people with a visual disability.

As a web developer you want to attract more viewer and make the experience pleasant for everyone.

<!--
_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_'https://www.boia.org/blog/why-screen-readers-are-essential-for-website-accessibility'-->

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
<img src="xxx.jpg” alt=”image of xxx”></img>


b) You want to create a website that lists all the art gallery websites in your city and links to their website.

to list all the art gallery 
<ul>	Defines an unordered list
<ol>	Defines an ordered list
<li>	Defines a list item
<a href="https://www.google.com/">Visit Google.com</a>


c) You want to sell designer hats. You need to receive orders from the user.

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning


Buttons can contain child elements in forms. Buttons inside of a <form> do something by default: they submit the form! They can also reset it, like their input counterparts

## Q5 - What is the most generic tag you can use?

<link>
<div>
<spam>
<head>

## Q6 - What do the following achronyms stand for?

a) `a`  defines a hyperlink, which is used to link from one page to another.

b) `ol` Defines an ordered list

c) `ul`  Defines an unordered list

d) `li`  Defines a list item   

e) `tr` Defines a row in a table

f) `th` Defines a header cell in a table

g) `td`  Defines a cell in a table

## Q7 - Usually, `td` elements are children of what kind of elements?

table is parent then <tr>

## Q8 - What is the difference between td and th?

TH is used for table header cells while TD is used for table data cells.

## Q9 - Which tag makes the text appear bigger: h1 or h3?

H1

## Q10 - In which situation can you use self closing tags?
if i am adding img tag or line break <br> we dont need self closing tags other then that for every beginning there is ending tags


## Q11 - What is autofilling and why is it important?
The autocomplete attribute allows the browser to do a pattern match against a list of values locally stored with the browser, and supplies the appropriate corresponding value when the input is programmatically tagged. 

This is a User setting that can be turned on or off, or modified by the end user. This reduces typing and reliance on memory because it uses stored values to fill in the fields which save time as well.

## Q12 - Which attributes are always present in an img element?
The src attribute is required always 
alt attribute holds a text description of the image, which isn't mandatory 

## Q13 - Which attribute is always present for an anchor tag?
href attribute
