# Reading 1

## Let's make a website

I will be describing the steps to create a very basic HTML page. In your text editor of choice (Atom, VS Code, Sublime) create a new file called *index.html*. Now with this blank slate we can create anything we want! Let's put the html boilerplate in:

        <!DOCTYPE html>
        <html>
        <head>
        <meta charset="utf-8">
            <title></title>
        </head>    
        <body>
        
        </body>
        </html>

Now that we have that lets talk a little about what that means. In HTML we use tags to tell the browser how to display our content. A tag is made up of a "__<__" then the type of tag it is: div, p, h1, and so on. Lastly we need a "__>__", then generally we add our content after the opening tag. then we finish that with a closing tag which will include a "__<__" then "__/__" and the characters with put in the opening tag, then "__>__". 

         <!DOCTYPE html>

This tag tells the browser we will be using HTML5, the latest and greatest version of the language.

        <html>
        </html>

These are our html tags, they tell the browser to treat everything between them as HTML.

        <head>
        <meta charset="utf-8">
            <title></title>
        </head> 

The head tags usually hold information for the browser, that meta tag tells the browser that we will be using UTF-8 encoding which could be its own post to explain. HTML5 by default using UTF-8 so it's not exactly necessary to include but it is common in boilerplate code. The next tag is the title, it is the text that we will see in the tab or the top of the browser.

        <body>
        
        </body>

Now the body tags, think of these as the part that the user will see, or the browser window. All of our content will be between these tags.

### Now for some content

In your boilerplate give your site a title. Mine will be "My Site". Now in the body  of the document (between the bodty tags) lets add a heading. Headings come in 6 flavors h1-h6, h1 is the largest h6 the smallest. Next we need our content in the form of a paragraph.

        <body>
        <h1>Hello World!</h1>
        <p>This is where I will put my content</p>
        <p>To make things <b>Bold</b> us an inline tag.</p>
        </body>

In html their are 2 types of elements: **Block-level** and **Inline**. block level elements will make their own line or block to render. In our example the h1 with be ontop of the p element. Inline elements will as it says render inline for example if you want something to be bold it would be between "**b**" tags.

### Now for layout

In HTML5 you can group your content with layout elements. These are fairly straight forward. Your header will be in the header tags, sections of like content should be in article tags. so lets add a few to clean up our code for anyone who is looking at it.

        <body>
        <header>
            <h1>Hello World!</h1>
        </header>
            <div id="content">
                <article class="firstArticle">
                    <p>This is where I will put my content</p>
                </article>
                <article class="secondArticle">
                    <p>To make things <b>Bold</b> us an inline tag.</p>
                </article>
            </div>        
        </body>

Now it looks like alot was added, however nothing that the user will see actually changed. Separating your content into layout elements will save you when you look back at the code, or someone else is looking at your code. I also added an id and class. These are exapmples of attributes, they provide further context to our elements. Id's can only be used once so you can't have more that one of each specific id. Classes will be used to identify our elements later to style them with CSS. We now have a very basic website. 

### Design

Designing a website is tricky. Design your sites so that your grandmother could navigate them easily. That sounds wierd however it is very easy to build a very cluttered, or complicated user interface and that should be avoided. 

### JavaScript

JavaScript is the language we use to make our sites interactive to our users. The book broke script into simple steps of how our browser interacts with the code. Your computer will only do exactly what you tell it to do, meaning you have to give it every step of the task you want it to complete. In your site JS will see the the document and generate a map of sorts for that. From that map it looks to see what it must do to show you that map. in your html you can add script tags to call specific JS actions as they appear in out site.