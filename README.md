#Boiler Plate 

##HTML
### Elements Included
1. We have included a header and a main element. 
2. The main element has 2 elements an article and aside. 

**Main**

The main element has `display: flex;` set on it and the flex items as centred with `justify-content: center;` and 
`align-items: center;`.
That is all that is included since the main purpose of this boiler plate is CSS experimentation and drawing.

##CSS
### Reset CSS
We don't use a reset as such and prefer the idea of making base CSS style consistent. For that reason the biler
plate uses normalize.css. It's included in the header and delivered via a CDN If you prefer to download it you can
visit https://github.com/necolas/normalize.css/

### Box-sizing
We have set box-sizing to border-box using the most accept method that supports both content-box and padding-box
when needed.