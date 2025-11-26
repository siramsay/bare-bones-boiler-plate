# Barebones Boilerplate 

This is available from https://github.com/siramsay/bare-bones-boiler-plate

## HTML
### Elements Included
1. I have included a header and a main element. 
2. The main element has 2 elements; an article and aside. 

**Main**

The main element has `display: flex;` set on it, and the flex items centred with `justify-content: center;` and 
`align-items: center;`.
That is all that is included since the main purpose of this boilerplate is CSS experimentation and drawing, which I generally want to be centred on the page.

If you want to use this for other work, you could remove the above rule for the main element and the markup of the main element, that is the `<article>Content</article>` and `<aside>Aside</aside>`. You could also delete the `<header>Header</header>` element.

## CSS
### Reset CSS
I don't use a reset as such and prefer the idea of making base CSS style consistent. For that reason the boilerplate uses normalize.css. It's included in the header and delivered via a CDN. If you prefer to download it, you can
visit https://github.com/necolas/normalize.css/

### Root and body color
I have added one custom property to override the body color this is for demonstration purposes and please change to 
a color. 

### Font 
There is no font set in the initial commit, so the font is the default serif font.

### Box-sizing
We have set box-sizing to border-box using the most accepted method that supports both content-box and padding-box
when needed.

## JavaScript
I have included a blank action.js file. 


