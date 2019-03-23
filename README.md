# HTML 101

## Before we begin

**Text Editor** vs. **IDE**: This is a question you may have when thinking about if your new to programming and having to download many diffent environements to devolop. First, what is an environment? An *Environment* is a place to write to computer software. You can chose to write commands (code) in a basic pre-installed application on your computer to open simple files. Some pre-installed text editors are Nodepad (windows) and TextEdit (mac). An *IDE* is a larger progam that can compile code from human readable code (a programming language) to machine code (binary). A *text editor* is very lightweight and a quick place to edit programs. The good news is that VSCode is a textEditor that can compile code that is very lightweight. It's like a hybrid application from Microsoft and free to use. 

Here is the link: 
> https://code.visualstudio.com/

After you download and install the application, open it up.
<img width="700" alt="Screen Shot 2019-03-23 at 9 35 30 AM" src="https://user-images.githubusercontent.com/25112069/54868925-144f3080-4d4f-11e9-99f7-240f4a41ac58.png">


**NOTE:** I am working on a Macintosh.

navigate to *file/save as/ [hit enter]* and save this page as `hello.html`

Now, the file should look like this:

<img width="700" alt="Screen Shot 2019-03-23 at 9 39 47 AM" src="https://user-images.githubusercontent.com/25112069/54868981-b8d17280-4d4f-11e9-8f59-62717a7b09e6.png">

How that the file is saved as an `.html` file it will be read as a web page and opened with your browser if you click directly on the the file where you saved it.

Lets try that out.

Navigate to where you saved your document, mine is saved on my desktop.

<img width="127" alt="Screen Shot 2019-03-23 at 9 45 20 AM" src="https://user-images.githubusercontent.com/25112069/54869042-78262900-4d50-11e9-8c61-60aceac87be6.png">

<img width="700" alt="Screen Shot 2019-03-23 at 9 45 48 AM" src="https://user-images.githubusercontent.com/25112069/54869043-78262900-4d50-11e9-83a3-bef6d0390d5b.png">

It's not very exciting yet is it? We have made an HTML page that doesnt have code or mark up (HTML is not computer code, it's considered a mark up language). The browser takes our mark up and changes it to what want. If we want some text to be in **bold** then we would type `<strong> bold </strong>`. Also, if we wanted our text to be in *italics* we would type `<em> italics </em>` "em" stands for emphasis. These are called "html tags". They represent what we want on the page. Lets make our first HTML document do something.

We will add the code:
```html
<!DOCTYPE html>
<html>
    
</html>
```
At the top, we begin by saying what type of document this is going to be. then we have our `<html>` tags that say everything in here is going to be my html.

between those `html` tags, we will add a `head` and `body` tag to represent the brains of the document, and the body (the main page) of the document. how it should look something like this. 

```html
<!DOCTYPE html>
<html>
      <head>
      </head>
      
      <body>
            <h1> Hello, World! </h1>  
      </body>
</html>
```

If you tried to run this in the browser would you see anything? No.

Now in the `body` tag, lets add our first tag that will do something. Lets add an `<h1> Hello, World! </h1>`

lets look at our VSCode, it should look like this:

<img width="700" alt="Screen Shot 2019-03-23 at 10 07 10 AM" src="https://user-images.githubusercontent.com/25112069/54869280-7447d600-4d53-11e9-8831-91adab61c2d6.png">


Save it, and run this in a browser by double clicking on the file. you should see this. 

<img width="700" alt="Screen Shot 2019-03-23 at 10 08 26 AM" src="https://user-images.githubusercontent.com/25112069/54869290-a6593800-4d53-11e9-8b44-e2ce47aa4a32.png">

Congratulations, you have made your very first webpage!
