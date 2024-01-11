*starting html coding on 07 Jan 2024, Sunday.*
-   Today I have completed **CSS**, So thought to revise html quickly before jumping to javaScript.

# **Review**
-   Global attributes
    - Go through documentation
-   

## Documentation
**Reading from documentation makes you a better developer**
- [MDN: developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/HTML).
- [Google: Developer.google.com](https://developers.google.com/apps-script/guides/html).

## Things to remember:
-   Only one ```<h1>``` heading per page is best practice.
-   

## Alternatives of HTML languages
- *markdown*, *latex* etc... are also mark up languages which can be used as an alternative of HTML but html is the most supported language in the browser, so we use html in general.

### Attributes:
-   There are compulsory attributes and non-compulsory attributes.
    - for example, In "<a>" tag "href" is compulsory attribute whereas "target" is non-compulsory attribute.

- If any attribute doesn't affect the basic functionality of the tag then it is non-compulsory attribute, as the browser will consider any default value on behalf of it.

- If any attribute affect the basic functionality of the tag i.e., "href" attribute in <a> tag, it affects the working so it is the compulsory attribute.
### **Global Attributes**

-   Documentation link:
    - [MDN: Global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)

-   **List of global attributes**
    -   accesskey:
    -   autocapatilize
    -   autofocus
    -   class
    -   data

### Comments
-  ```<!-- For single and multiline comments, this is the way -->```

### ```<hr>```
- This tag display a horizontal line

### ```<br />```
- This tag gives line brake and shift text to next line.
- The better way to write this tag is ```"<br />"``` because in react it will show error if written ```"<br />"```.

### ```<pre></pre>```
- This tag is used to solve to peom problem, it can print star or any other patern.
    - Any spaces that given inside the ```"<pre>"``` tag are displayed as it is by browser.
    - This tag is also used for writting codes of other languages to display in browser screen. for example: -
        - ```<pre>console.log("hello world");</pre>```

### comments
-   comments are not display in the browser screen but they can be seen using view source code feature of browser.

### ```<html>```
- used to write lang attribute ```<html lang="en">```.

### Paragraph tag: ```<p></p>```
- Used to write paragraph
    - This is block element.

### unorder list tag: ```<ul><li></li></ul>```
-   *emitt shortcut*
    -   **ul>li*4 this will give 4 li tag between ul tags.**

### b tag: ```<b></b>```
- This tag is used to write text in bold color.
    - Now it's not used because to make latters bold we use css instead of this tag.

### strong tag: ```<strong></strong>```
- This tag is used to emphasis that the information is very important.
    - We use ```<strong>``` tag often instead of ```<b>``` to show important information.
- Use the ```<strong>``` element to mark text that has greater importance than surrounding text.

## ```<b>``` VS ```<strong>```
-   The ```<strong>``` element is for content that is of greater importance.
-   While the ```<b>``` element is used to draw attention to text without indicating that it's more important.

### Italicized type using i tag: ```<i></i>```
-   This tag is used to italicize the normal text.
-   This element represents a range of text that is set off from the normal text for some reason, such as idiomatic text, technical terms, taxonomical designations, among others.

### Emphasis: ```<em></em>```
-   **element marks text that has stress emphasis.** The ```<em>``` element can be nested, with each level of nesting indicating a greater degree of emphasis.
- Typically this element is displayed in italic type.
- A screen reader will pronounce the words in ```<em>``` with an emphasis, using verbal stress.
- **it should not be used to apply italic styling;** use the CSS font-style property for that purpose.

## ```<i>``` VS ```<em>```
-   The visual result is same but the semantic meaning is different.
-   The <em> element represents stress emphasis of its contents, while the <i> element represents text that is set off from the normal prose, such as a foreign word, frictional character etc.
-   **A text in betweem ```<em>``` tag, when a person or software reads the text would pronounce the words in italics with an emphasis, using verbal stress.** whereas a text between ```<i>``` tag there is no added emphasis or importance on the word, that results in different meaning.

### Quotes tag(""): ```<q></q>```
-   This tag is used to write quotations ("").
    -   for ex: - ```<q>``` Hey this is a quatation. ```</q>```
        -   output: - "Hey this is a quatation."

### extended quotation: ```<blockquote cite"https://url.com"></blockquote>```
-   The ```<blockquote>``` HTML element indicates that the enclosed text is an extended quotation.
-   The blockquote element represents a section that is quoted from another source. Content inside a blockquote must be quoted from another source, whose address, if it has one, may be cited in the cite attribute. If the cite attribute is present, it must be a valid URL potentially surrounded by spaces.
-   A URL for the source of the quotation may be given using the cite attribute.
    -   while a text representation of the source can be given using the ```<cite>``` element.

### cite tag: ```<cite></cite>```
-    It is used to mark up the title of a cited creative work.
    -   A creative work that might be cited could be, for example: a book, research paper, scientist name, song, peom, film etc...

### small tag: ```<small></small>```
-   The ```<small>``` HTML element represents side-comments and small print, like copyright and legal text, independent of its styled presentation.
-   By default, it renders text within it one font-size smaller, such as from small to x-small.

### sub and sup tag: ```<sub></sub>``` and ```<sup></sup>```

### ins and del tag: ```<ins cite="url.com" datetime="2018-05"></ins>``` and ```<del></del>```

### mark tag: 

## style attribute:





