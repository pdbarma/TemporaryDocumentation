# Beginners Web Dev

  
### Resources :  
- developer.mozilla.org : [MDN](https://developer.mozilla.org/en-US/)  
 

<h2>Progress :</h2>  
<details><summary>Introduction: </summary>  
<p>   

  
**In a webpage there exists**  
Front end | Back end
(Html,CSS,JS)

- Front end : Front end development is programming which focuses on the visual elements of a website or app that a user will interact with (the client side).  
  
- Back end : Meanwhile, back end development focuses on the side of a website users can’t see (the server side).   

  
- languages used in webdev :
  - **Html**: nouns(what)  
  
  - **CSS**:adjectives(describes html element's things on the page)  
  
  - **js**: verbs(how things are done(eg-maths))  
  
  
Some basic commands :
```
<p> </p>: For a single paragraph.
<b> </b>: Making elements bold.
<h1> </h1>: header 1.
```  
  
## Library :  
  
- MDN HTML ELEMENT REF.: [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
  
  

- **SIMPLE HTML SYNTAX** :
```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
  

- Listing Elements

using :  
  
```html
// for bullet points unlisted in short  
<ul>  
  <li> List No. 1</li>
  <li> List No. 2</li>
  <li> List No. 3</li>
  
</ul>

```  
  
```

// for numbered points ordered list in short
<ol>  
  <li> List No. 1</li>
  <li> List No. 2</li>
  <li> List No. 3</li>
  
</ol>  
  
```  


```
//for making sub list elements inside another list :

<ul> // for bullet points unlisted in short
  <li> List No. 1</li>
          <ol>
            //for bullet points of sub list section in unlisted form
            <li> sub list 1</li>
            <li> sub list 2</li>
            <li> sub list 3</li>
          </ol>
  <li> List No. 2</li>
  <li> List No. 3</li>
  
</ul>
```

- Link Input
```
<a href="link">name of the link</a>

<a></a> is a anchor tag
href= hyper text reference in short href
```

- Image Input
```
<img alt="name" src="link">name of the link</a>

alt=The alt attribute specifies an alternate text for an area, if the image cannot be displayed.
The alt attribute provides alternative information for an image if a user for some reason cannot view it
(because of slow connection, an error in the src attribute, or if the user uses a screen reader).
```  
  
- Comments  
  
```
<!-- comments are meant to be written here -->

```
  
</details>
</p>

---  
  
<details><summary>HTML Next Steps & Semantics:</summary>  
<p>   

### HTML 5 :

- new version of html
- The term HTML5 is essentially a buzzword that refers to a set of modern web technologies.
This includes the HTML Living Standard, along with JavaScript APIs to enhance storage, multimedia, and hardware access.
- [HTML Standards](https://html.spec.whatwg.org/#toc-introduction)

### BLOCK VS INFINITE LINE:DIV & SPAN :

- Divs``` <div></div> ```are generic containers to group elements together.
- span ``` <span></span>```are another generic container but it is an inline element.
- It is a block level element.
  - **What is a block element?**
    - HTML (Hypertext Markup Language) elements historically were categorized as either "block-level" elements or "inline-level" elements. Since this is a presentational characteristic it is nowadays specified by CSS in the Flow Layout. A Block-level element occupies the entire horizontal space of its parent element (container), and vertical space equal to the height of its contents, thereby creating a "block".

 #### Block-level vs. inline
There are a couple of key differences between block-level elements and inline elements:

- Content model
Generally, block-level elements may contain inline elements and (sometimes) other block-level elements. Inherent in this structural distinction is the idea that block elements create "larger" structures than inline elements.

- Default formatting
By default, block-level elements begin on new lines, but inline elements can start anywhere in a line.

- [Block-level elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Block-level_elements)-HTML | MDN



</details>
</p>

---

- [ ] course completed
