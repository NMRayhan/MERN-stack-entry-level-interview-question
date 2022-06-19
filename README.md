# MERN-stack-entry-level-interview-question
## HTML Question
### 1.What are the differences between html4 and html5? 
**Ans:** Different between HTML4 & HTML5.
| **HTML4** | **HTML5** |
| ------ | ------ |
| Html 4 is not a mobile friendly | Html5 is mobile friendly |
| Html4 is older version of html | Html5 is modern version of html |
| It is not supported any audio or video without flash player | It is supported to audio and video using audio and video tag and it’s control |
| Document declaration is to complicated and log statement | Document declaration is vary easy and to short |
| It’s not possible to drag and drop | It’s possible to use drag and drop |
| User Geolocation access not possible this version | Easy to access user Geolocation |
| Not allow to run javascript in browser | Allow to run javascript in browser |

### 2. What are semantic tags in html? Give me some examples?
**Ans:** Semantic Tag and its examples:
Semantic tag means syntax refers to a very easy to understand tag. What is the meaning of this tag? And it is very clearly understandable to machines and humans.
Some Semantic Tag Examples:
- Nav tag
- Aside tag
- Mark tag
- Section tag
- Summary tag
- Article tag
- Footer tag
- Header tag
- Figure tag, etc.

### 3. What is the purpose of Article, div, section, nav, aside?
**Section:** Section sounds like a div, it’s used for wrapping different content in one section like, img, header, paragraph, anchor, etc. 
**Div:** div tag is used for styling purposes of HTML documents and we use div for a division of a HTML Document.
**Article:** The article element represents a section of content that forms an independent part of a document or site; for example, a magazine or newspaper article, or a blog entry.
**Nav:** nav tag use for website navigation bar where some anchor tag group place for link to one page to another page
**Aside:** some of the web site aside use for left or right content in main content, also aside represent left bar or right bar or side box in website

### 4. Why will you use Meta tag?
**Ans:** First of all say meta tag has no closing tag, meta tag carries author name, expiry date, a list of keywords, document author etc.
we can add one or more meta tags in html documents, we can use our Key words, descriptions, etc.

### 5. What is the difference between inline, inline-block, and block?
**Ans:** block level elements are forced line break, inline elements are not to force line break; it uses her own content, inline-block elements left and right padding and margin support. Block level elements have no top and bottom padding or margin.


### 6. Difference between strong, b, em, i?
**Ans:** strong tag use for any content is specific for important in this document, b is without important text content is represent bold, ```<em>```for tag semantically emphasises on the important word or section of words while ```<i>``` tag is just offset text conventionally styled in italic to show alternative mood or voice.

### 7. What are properties and attributes in HTML?
**Ans:** Attributes define HTML code and properties are created while html code rendering browser and its create DOM(Document object Model) tree and create nodes in elements it’s properties.
Attributes defined by HTML and properties defined by DOM, attribute main role is initialise the properties, if properties initialise done then attribute main role is complete, attribute value is no change but properties value is changable.

### 8. What is a Viewport?
**Ans:** Viewport is a HTML Viewing area in Device Screen, it’s mobile, desktop, laptop, tab screen, etc. viewport is make sure a whole html document is showing the user display.

### 9. Have you used Audio and Video tags? How do they work?
**Ans:** Yes, we use this Audio and video tag in our html file. Audio and video tag has an ending tag present. Audio and video tag has nested with source tag if we provide any multimedia link with source then audio and video play this source multimedia in browser.

### 10. What is hyperlink in html? What tag and attribute will you use for hyperlink?
**Ans:** Hyperlink in html is href. Its use for anchor tag ```<a href=”Link”>content</a>```. Hyperlink use for any kind of linking, linked navigation, reference, etc.

### 11. What is the difference between HTML elements and tags?
**Ans:** technically HTML Element is a collection of HTML tag first part, on the other hand html tag is single element, tag starting with <(angle bracket) and then uppercase letter of meaningful tag. Maximum tag has ending tag, html tag is case insensative.

### 12. What is charset in html? Why will you use it?
**Ans:** charset is called HTML Characterset or HTML encoding. It’s use for page content showing properly in HTML document

### 13. What is the Use of Comments in HTML?
**Ans:** Comments are used in an HTML document to make important notes and help developers mention any modification to be incorporated afterward. They are not displayed in the browser when the code is executed. A comment is always written in between the ‘—‘ symbol at the beginning and end of the angular brackets.

### 14. How do you create links to different sections within the same HTML web page?
**Ans:** We use the ```<a>``` tag, along with referencing through the use of the # symbol, to create several links to different sections within the same web page.

## CSS Question

### 15. What Flex layout? Difference Flex and grid layout?
**Ans:** Flex is a one dimensional Layout system. So many items simultaneously stand 
after one by one in row wise or column wise Flex layout.
Different between Flex and grid layout system:</br>
**Grid:**
- Grid Layout is Two Dimensional Layout
- Grid Layout is at the same time Row and column using
- Grid Layout use for Large scale application development.

**Flex:**</br>
- Flex is one dimensional Layout
- Flex Layout is use one Row wise otherwise column wise
- Flex Layout is Suitable for small Application

### 16. Explain CSS position property? What are some differences between absolute position and relative position?
**Ans:** CSS Position property defines HTML Element in position of a document, it’s over left, right, top, bottom, middle and anywhere in the document.

**absolute vs relative:** 
- Relative position element taking space but absolute position not taking space
- Relative position not changing parent layout but absolute position changing parent layput
- Relative position no need to any parent element but absolute position need to be any element in relative parent.


### 17. What is a box model? And what are the different elements of a box model?
**Ans:** Box model is box sizing any content, it’s overall element padding, margin, border, width and content mixing.
Every box is composed of four parts (or areas), defined by their respective edges: the content edge, padding edge, border edge, and margin edge

### 18. What is a Hover effect? What is the purpose of the active class?
**Ans:** Hover effect is pseudo class, it is used for if we mouse over any element then we customisable change showing this element and its call hover effect.
Some of the web site we saw that which page we stay if we see navbar and then show the active navbar it's happened because of active class pseudo class.

### 19 What is pseudo-class? 
**Ans:** CSS pseudo-class is a selector, only when the selector meets a certain condition. It’s starting colon(:) after adding pseudo classes.

### 20. What are the different types of Selectors in CSS? 
**Ans:** there are some different type of selector in CSS
- Simple selector(select by element, id, class)
- Combinators selector(base on element)
  - Descendant selector(space)
  - Child selector(>)
  - Adjacent siblings selector(+)
  - General siblings selector(~)
- Pseudo-element selector
- Pseudo-classes selector
- Attributed base selector

### 21. Differences between Class selector from ID selector?
**Ans:** different between Class selector and ID selector 
Id is only used when only one id is for the document and style, the other hand class is used for many elements.
- Id style sheet using style for starting hash(#) and then style element but class style sheet using style for starting dot(.) and then name and given style
- Then only different is **ID** is unique whole document is only one but **Class** is multiple whole document is same class multiple element use

### 22. What is CSS Specificity?
**Ans:** Specificity is the algorithm used by browsers to determine the CSS declaration that is the most relevant to an element, which in turn, determines the property value to apply to the element.

### 23. What is a CSS Preprocessor? What are some benefits of Sass?
**Ans:** A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax. A browser can only understand CSS, which at times may not be enough to write clean and reusable rules

Some benefit of Sass
- Easier to maintain code
- It will make css dry
- It will make css more organise
- It will save our time and so faster

### 24. What is a Pseudo element? Give an example of pseudo element
**Ans:** pseudo elements are given to specific styles of specific parts of an element.
Some pseudo element example:
- ::after
- ::before
- ::first-line
- ::first-letter
- ::marker

### 25. How will you use media queries to make a website responsive?
**Ans:** media queries to make the website responsive. We show different device to screen size for example if we develop a website for desktop version its any section 300px card row wise three card showing but if we change the device screen size like mobile this time 300px three card not showing in same row and it’s time arrive media Queries

### 26. How will you make font size responsive?
**Ans:** given media queries reset font size to responsive another way to make font size responsive to view high or viewWidth on this font size.
Basically the second one is more effective. It changes the font size and the screen size.

### 27. What are some CSS Measuring units? Which one will you use?
**Ans:** we can use css measuring units most like px(pixel), cm(centimeter), mm(millimeter), pt(picas) and pt(point), etc. to use absolute measurement. 
Another measurement unit use for relative length like em(Relative to the font-size of the element), rem(relative to font-size of root element), vw(Relative to 1% of the width of the viewport), vh(Relative to 1% of the height of the viewport) and %(related to parent element)

### 28. Difference between transition and transform?
**Ans:** difference between CSS Transform and CSS Transition? The Transform property in CSS moves or modifies the appearance of an element, whereas the Transition property seamlessly and gently transitions the element from one state to another.

### 29. How will you horizontally and vertically center a div inside a div?
**Ans:** So many options we can use horizontally and vertically center a div inside a div but most of the time using flex display in parent element within justify-content center and align-items center create center a div inside a div.

### 30. What does * { box-sizing: border-box; } do? What are its advantages?
**Ans:** It makes every element in the document include the padding and border in the element’s inner dimension for the height and width computation.

### 31. What is the universal selector in CSS?
Ans: The universal selector matches the name of any of the element types instead of selecting elements of a specific type.
```<style>    
* {    
   color: green;    
   font-size: 20px;    
}     
</style>```
