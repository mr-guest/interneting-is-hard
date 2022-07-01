# Introduction
HTML and CSS are hard. (but it doesn't have to be)
This guide provide how to make and design webpages.
We also provide how to select the tools of trade to web& development. More on that later

Make sure to input every _psuedo code_ or _snippet code_.
Not just copy and paste.

I know its annoying and in the future we will talk about how to automate redundant stuff.
But learning from scratch or the author say it as **Fundamental** rather than the frameworks helps a lot.

Its like learning how to make a cake from scratch,sure time and ingredient to make are much different than the instant-cake but you **know exactly the ingredients and what happens during the cake making from scratch**.
Does that means instant-cake are dumb? not at all! Is good for what it is and helps a lot to save time and money.

Point is **Learn from Fundamentals not Framework.**

# Relationship between HTML , CSS and JavaScript
Three of it runs the web , they are very closely related but it does own very specific task to tackle.
> Understanding how they interact will help you towards becoming web-developer

- HTML are for adding meaning/input/data to raw content by marking it up
- CSS are for formatting that marked up content
- JavaScript are for making that content and formating interactive page to use because JavaScript can manipulate both HTML and CSS

Is like the bone muscle and skins.
Bone as HTML = Structural
CSS as Skins = Cosmetic but necessary
JavaScript as Muscle = How they interact to other.

Kinda misleading because what's important first are the HTML and CSS.
> Every websites determined by HTML and CSS for their appearance

Code Example
HTML
'<p = id'some-paragraph'> This is paragraph. </p>'
CSS
'p {
  font-size: 20px;
  color: yellow;
  }'
JavaScript
'var p = document.getElementById('some-paragraph') ;
p.addEventListener('click', function(event) {
  p.innerHTML = 'You clicked it!';
  })'

HTML = You want to mark some text as a paragarph
CSS = You want to set the size and color of that paragraph
JavaScript = You want to do fancy stuff by rewrite paragraph to other text went the user clicks the paragraph

# Languages and Web Development , The Relationship

Becoming profesional web developer are not easy task because mastering HTML, CSS and JavaScript are _prerequisite_ . So is not enough? Yea

There are many practical skills are needed such as
- Organizing HTML into reusable templates
- Standing up a web server (Backend?)
- Moving files from your local computer to web server (ssh and basic Command line)
- Reverting to a previous version when you do something stupid (Learning git)
- Pointing a domain name at your server (knowing on Domain)

Because of it there also many guides on that so i'll look up for it.
The only thing i know are [MDN](https://developer.mozilla.org/en-US/docs/Learn/Front-end_web_developer) , [Practical guide on Youtube](https://www.youtube.com/watch?v=EqzUcMzfV1w) and [Roadmap frontend](https://roadmap.sh/frontend)

But dont be intimated or overwhelmed. _Gaining fluency in both HTML and CSS are first steps on web developer_.

## But why?

First of Web Developer wants to present content to others.
Is like printing industry back then.
They use an original printing press (the metal ones) by arranging the needed characters. dipping it and pressing them on piece of paper.

They concerned on _conveying content in meaningful ways_.

Same like web-developer , We need to deal same presentational issues , selecting the correct font for the content , selecting the size of headings and determining the space between lines of text.

(So is like presenting on PowerPoint? is a bit of streching but yea)

In ways printer used to print a bunch of pages and bind them together into a book. Nowadays a bunch of HTML files and link them together will create website.

> Learning HTML and CSS is a matter of understanding the available HTML markup and CSS rules to make a browser render those files exactly how they’re supposed to.

#### in hindsight i should learn on grammar and Markdown template next time
