When creating a web page, you add tags (known as markup) to the contents of the page. These tags provide extra meaningand allow browsers to show users the appropriate structure for the page.

Structural markup: the elements that you can use to
describe both headings and paragraphs.

Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.

<h1> element is the largest, and the contents of an <h6> element is the smallest،The exact size at which each browser shows the headings can vary slightly. Users can also adjust the size of text in their
browser.

For Paragraph we will use the tag <p></P>
The  browser will show each paragraph on a new line.
<b> or <strong>   the text will appear bold 
<i> or  <em> the text will appear italic
The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like
raising a number to a power such as 22.

The <sub> element is used tocontain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20

white space collapsing the browser will read one space only even if you put more than one , the developers use this spaces just to make the code easier to read
<br /> this will show the text on new line .
emty elements :elements doesnt have any words between the opening and the closing tags ,An empty element usually has only one tag,Before the closing angled bracket of an empty element there will often be a space and a forward slash character.
<hr /> horizontal rule between sections .
The <blockquote> element is used for longer quotes that take up an entire paragraph. Note how the <p> element is still used inside the <blockquote> element.

The <q> element is used for shorter quotes that sit within a paragraph.

<abbr> If you use an abbreviation or an acronym, then the <abbr>
element can be used. A title attribute on the opening tag is used to specify the full term.

<cite> you can use it to indicate where the citation is from, such as the books .

<dfn>  used to indicate the defining instance of a new term
The <audio> element  is to add audio to your code and there is multiple  attributes to control your audio 
1-src :you will use it for the path
2-controls : This attribute indicates whether the player should display controls
3-autoplay :if the audio should start playing automatically 
4-preload : if not  autoplay then preloas.
5-loop: to start the audio again  once it has finished.

<source> you will use it for multiple audio 

Block level elements look like they start on a new line.
Examples include the <h1>-<h6>, <p> and <div> elements.

Inline elements flow within the text and do not start on a new line. Examples include <b>, <i>,<img>, <em> and <span>

CSS will allow you to design your website 

A CSS rule contains two parts: a selector and a declaration. 

 

The selector indicates which element the rule applies to (with commas you can apply the rules to more than on selector) 

 

Deceleration: what stylings we will use, its split into two parts (a property and a value), and are separated by a colon, you can specify several properties in one declaration, each separated by a semi-colon. 

 

Using external CSS  

<link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page you will put this tag inside the head tag. 

The attribute for the link tag : 

Href :will define the path for the css file  

Type: This attribute specifies the type of document being linked to. The value should be text/css 

rel :This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file. 

 

Using external CSS 

CSS rules within an HTML page by placing them inside a <style> inside the head tag . 

We will use on attribute for now here which is the TYPE :text/css . 

When building a site with more than one page, you should use an external CSS style sheet. This: 

 ● Allows all pages to use the same style rules (rather than repeating them in each page). 

 ● Keeps the content separate from how the page looks.  

● Means you can change the styles used across all pages by altering just one file (rather than each individual page). 


 JavaScript:
JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML 

like css files javascript can be in a seperate file , and it's the best way to add the javascript code into your code , and the extesion for this file should be (file.js)
<script > is used to  load the javascript file 

A script is a series of instructions that a computer can follow one-by-one.

Each individual instruction or step is known as a statement. Statements should end with a semicolon.
commets will make your code easier to read and understand. 

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

Rules for naming variables:
The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.
You cannot use keywords or reserved words. 
All variables are case sensitive.
Use a name that describes the kind of information that the variable stores.

An array is a special type of variable. It doesn'tjust store one value; it stores a list of value.

Functions allow you to group a set of related statements together that represent a single task, the fuction wil take parameters and may return value 
In an object, variables are known as properties of the object; functions are known as methods of the object. 

Comparison Operators:
== : equal to (same value).
!= : not equal to.
=== : strict equal (same data type and value).
!== : strict not equal to.
> : greater than.
< : less than.
>= : Greater than or equal to.
<= : less than or equal to.
Logical Operators:
&& : logical and.
|| : logical or.
! : logical not

If statmet : whe the certain condition is met please ru the code otherwise please ru the else code .

For example 

if (score >50)
document.write('ypu passed');}
else { documet.write('try again');}

Commit  message :
A good commit message guideline will: give context about the “what” and most importantly the “why” of your commits. make working with your commit history easier and more systematic