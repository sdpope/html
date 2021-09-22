# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [false] `<div><span>hello</div></span>`

b) [false]

```html
<ul>
<li>one</li>
</ol>
```

c) [false] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
A screenreader is a type of assistive technology that parses a web page semantically, for someone with a visual impairment or other disability. It is important that web pages are legible to screenreaders and comprehensible for their users because of best practices, ethics, and regulatory compliance.
## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
`div` `p` `img`
b) You want to create a website that lists all the art gallery websites in your city and links to their website.
`<ul> <li> <a>`
c) You want to sell designer hats. You need to receive orders from the user.
`<form> <input> <img>`

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
No. A `button` can't have a clickable child tag, and it is a clickable tag itself. 

## Q5 - What is the most generic tag you can use?
`div` is essentially a bare block element that has no particular significance until added through attributes and styling.

## Q6 - What do the following achronyms stand for?

a) `a`
Anchor
b) `ol`
Ordered list.
c) `ul`
Unordered list.
d) `li`
List item.
e) `tr`
Table row.
f) `th`
Table header
g) `td`
Table data
## Q7 - Usually, `td` elements are children of what kind of elements?
The `tr` table row element.
## Q8 - What is the difference between td and th?
`th` is the table header: it should be at the top of the column and is a label for the data rather than a piece of data itself.
## Q9 - Which tag makes the text appear bigger: h1 or h3?
`h1`
## Q10 - In which situation can you use self closing tags?
When the tag does not have any children, e.g. when using an `img` tag.
## Q11 - What is autofilling and why is it important?
Autofilling is a browser feature that fills out forms automatically from saved user data, baced on tag attributes. An `input` tag that doesn't belong to a `form` tag will not be autofilled.
## Q12 - Which attributes are always present in an img element?
The `img` tag requires a `src` attribute with the URL of the image to be displayed, and it should always have an `alt` attribute for screenreaders/accessibility.

## Q13 - Which attribute is always present for an anchor tag?

The `href` attribute defines where the link actually leads.