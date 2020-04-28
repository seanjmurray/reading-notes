# Reading 2

 
 ### Text and CSS

When using html you have a few options by default to style your text. For headings you can use H1-h6. These will change the size of your headings each tag will display a different size , with h1 being the largest and h6 the smallest. These will cover your headings and subheadings. For longer sections of text you should use p tags. These are for paragraphs. Within your text you can style it with inline tags like: b, strong, em, and i. To bold text use b or strong tags, both of these will render the text within **bold**. To emphasize or italicize you would use i or em tags.

    <h1>Hello World.</h1>
    <h2>Hello World.</h2>
    <h3>Hello World.</h3>
    <h4>Hello World.</h4>
    <h5>Hello World.</h5>
    <h6>Hello World.</h6>
    <p>Lorem ipsum dolor sit amet, <i>consectetur adipiscing</i> elit, sed do eiusmod tempor <b>incididunt</b> ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud <em>exercitation</em> ullamco laboris nisi ut aliquip ex ea commodo <strong>consequat</strong>. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
    </p>

### This code will render this:

<h1>Hello World.</h1>
<h2>Hello World.</h2>
<h3>Hello World.</h3>
<h4>Hello World.</h4>
<h5>Hello World.</h5>
<h6>Hello World.</h6>
<p>Lorem ipsum dolor sit amet, <i>consectetur adipiscing</i> elit, sed deiusmod tempor <b>incididunt</b> ut labore et dolore magna aliqua. Ut enim aminim veniam, quis nostrud <em>exercitation</em> ullamco laboris nisi ualiquip ex ea commodo <strong>consequat</strong>. Duis aute irure dolor ireprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>


To further specify what text you are using you can use the following tags. For quoting text the blockquote and q tags. Blockquote is used for large multi line quotes, it generally will indent all the lines withing the tags. The q tag in most browsers will put quotes around the text. For acronyms and abbreviations use the abbr tag to show a tooltip on hover. To quickly show edits to text the ins and del tags will cross and underline the encased text. The s tag will also stikethrough your text.

### CSS
CSS is used to style our pages, it follows a few basic rules. The selector that is last or most specific will be applied to the object. When styling you should use an external stylesheet and link to it in the head of your html file.

    <link href="css/styles.css" type="text/style" rel="stylesheet">

This is where you will put your css code to style all pages that link to it. You can select items by type, ID, class and a few more. to select by type you just use the tag you want to select. for ID use #theId, and class .className to select them.

    // type selector
    p {
      color: #ff6600;
    }
    // id selector
    #titleH1{
      background-color: #222222;
    }
    // class selector
    .thisIsMyClass {
      text-align: center;
    }

 ### Basic Instructions and Decisions and Loops

    // defining variables
    var stringType = "Hello World";
    var numType = 42
    var booleanType = true;

variables can be of 3 types strings, booleans, or numbers. Strings are a letters or numbers in quotes. Booleans represent true or false. Lastly numeric data.

When naming things in javascript you should use camelCase. The first letter should be lowercase and the next word shouldn't have a space but the first letter capitalized like userName or firstName. With js you can do basic math like adding, subtracting, multiplying, and dividing. You also can add one with ++ or subtract one with --, using % will divide but give you just the remainder as an output. When compairing things you can use == to get equal to, != for not equal, === for strictly equal to, and !== for strictly not equal. Also less than and greater than can be done using <, >, >=, <=. When working with js you often have to see if something met a condition, this is where if and switch statements come in.

    if(something == something){
      do something
    } else { 
      do something else
    }

### Or

    switch (someVar) {
      case 1:
      do something;
      break;
      case 2:
      do something else;
      break;
      default:
      do this;
      break;
    }

