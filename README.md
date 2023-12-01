# Tribute-Html
My tribute page with HTML only.
# HTML lesson & Project
HTML - First of all it is not a programming language. It is a markup language which stands for HyperText Markup Language. We need HTML for structure of our webpage.

I HTML: we have Tags, Element and attribute
Tag Tpes: Pair tag -> pair tag or container tag or non-replaced(h1-6,p,ul,li,em,strong,) and sometimes optional closing tag.
          empty tag or replaced or void tags-> single tag (br,hr,img,input,meta)
The Element contains the Opening and closing tag(<h1></h1>). the character set (charset="utf-8") attribute in meta tag defines the encoding type of the html document.
Attributes are used to give additional information about the element and only appear in the opening tag.

## HTML document structure
<!DOCTYPE html> this tells the browser to use a standard mode of document otherwise it will use the quirks mode.
<html></html> with the laguage type (lang="en-us") that is if you want the browser to translate in english US version.

## Lists, Links, Pages, Frames(iframe), Media

## Tables and Forms
 Using HTML APIs in forms

## Web Accessibility
 Making websites supportive for dissabled people (screen reader) and search engines friendly

 how to check the accessibility ( inspect -> lighthouse -> accessibility)

 Always try to use more of semantic(meaningful) tags in your HTML non-semantic tags.

 semanic structure of HTML 
 Nav -> Header -> Main (you can have only one main tag in a page) and you can have many sections inside your main tag (about me, education, skills, contact sections) and the last one is the footer tag.

 when using the image tag, make sure to use the alt(alternative name) atribute. 
 Also, if you create a link make it describeable example <a href="#">Visit my web page</a> instead of just saying "visit".
 when you use a form, make sure you use a label and always bind it together 

 ## role in HTML is to make a none semantic tag accessible.
 <div role="button">Click me</div> here the div Click me servs the 'role' of button.

 aria-label is used to give more information to the user and it improves accessibility
 
