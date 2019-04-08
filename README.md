# Making a "starter script" for IT 102

## Before we begin

**Text Editor** vs. **IDE**: This is a question you may have when thinking about if your new to programming and having to download many diffent environements to devolop. First, what is an environment? An *Environment* is a place to write to computer software. You can chose to write commands (code) in a basic pre-installed application on your computer to open simple files. Some pre-installed text editors are Nodepad (windows) and TextEdit (mac). An *IDE* is a larger progam that can compile code from human readable code (a programming language) to machine code (binary) that a computer can read. an *IDE* also offers debugging features, code completion, and other features. A *text editor* is very lightweight and a quick place to edit programs. The good news is that VSCode is a textEditor that can compile code, debug, complete code, and is very lightweight. Best part, it's free from Microsoft.

**NOTE** You can use any text editor for creating simple HTML, CSS, and JavaScript for websites. I prefer VSCode, but for this class its advised to use Notepad or Notepad++. If you want to download VSCode on your personal computer for use, link is below.

> https://code.visualstudio.com/

Open up the text editor. If using VSCode it will look like this, you get an untitled paged named `Untitled-1` that we'll change in the next step.

<img width="700" alt="Screen Shot 2019-03-23 at 9 35 30 AM" src="https://user-images.githubusercontent.com/25112069/54868925-144f3080-4d4f-11e9-99f7-240f4a41ac58.png">


**NOTE:** I am working on a Macintosh so it might look a little diffent if you're using a windows machine.

navigate to *file/save as/ [hit enter/or click]* and save this page as `starter-script.html`

**name=** `starter-script`<br/>
**file type=** `html` (hyper-text markup language)<br/>
<br/>
 then, **save it to your desktop**.

Now, the file should look like this:

<img width="700" alt="Screen Shot 2019-03-23 at 10 18 48 AM" src="https://user-images.githubusercontent.com/25112069/54869466-d9043000-4d55-11e9-8428-31f736efe4b4.png">

The file is saved as an `.html` file, which means it will be read as a web page and opened with your browser when you click it directly.

Lets try that out.

Navigate to your desktop (where the file is saved) and *double click*.

<img width="145" alt="Screen Shot 2019-03-23 at 10 35 31 AM" src="https://user-images.githubusercontent.com/25112069/54869549-71e77b00-4d57-11e9-9e22-27db0fdca447.png">

<img width="700" alt="Screen Shot 2019-03-23 at 10 35 43 AM" src="https://user-images.githubusercontent.com/25112069/54869547-70b64e00-4d57-11e9-9aa7-5ae09aa174de.png">

It's not very exciting yet is it? We have made an HTML page that doesnt have code or markup (HTML is not computer code, it's considered a markup language). The browser takes our markup and changes it to what want to be displayed. If we want some text to be in **bold** then we would type `<strong> bold </strong>`. Also, if we wanted our text to be *italicized* we would type `<em> italicized </em>` "em" stands for emphasis. These are called "html tags". They represent what we want on the page. Lets make our first HTML document do something.

<br/>

**NOTE:** In order to view an `.html` file you will need to wright click the file and open it in a text editor. By Default it will open in a browser.
<br/><br/>

...Lets add some markup!

```html
<!DOCTYPE html>
<html>
    
</html>
```

## What does this mean?

At the top (`<!DOCTYPE html>`), tells the browser that this document will be in HTML.  Then, we write and opening `<html>` tag says "hey here is where my html is going to start and we want it to end when we write `</html>`. Notice the `/`, this is the beginning of a closing tag.  Most tags have open and closing tags, which mean everything in here is going to belong to that type of thing.

Lets add some more.

```html
<!DOCTYPE html>
<html>
      <head>
      </head>
      
      <body>
      </body>
</html>
```

Inside our `<html>` tags we want to add a `head` and `body` tag. This will make more sense as we go, but the head tag represents information about the page, and wont show up on the website. The body tag, will show all the tags on the webpage. Again, this will make more sense as you progress.

Now in the `body` tag, lets add our first tag that will do something in HTML. By adding a `h1` tag, it will make a header size 1 (the largest) be displayed on the screen. Add `<h1> Hello, World! </h1>` between the body tags.

lets look at our text editor, and it should look like this:

<img width="700" alt="Screen Shot 2019-03-23 at 10 51 48 AM" src="https://user-images.githubusercontent.com/25112069/54869698-b5db7f80-4d59-11e9-9d23-f34f235c1ad4.png">

**Save the file**, and run this in a browser by double clicking on the file saved to your desktop. You should see this this. 

<img width="700" alt="Screen Shot 2019-03-23 at 10 51 54 AM" src="https://user-images.githubusercontent.com/25112069/54869699-b5db7f80-4d59-11e9-8215-555d7b96c393.png">

Congratulations, you have made your very first webpage! :tada:

---

## Lets add the JavaScript template you'll be using for the class.

This course you will be learning JavaScript. Unlike HTML, JavaScript is not markup, it's code. Since it's code, we can make it do some cool stuff!

Since, a webpage uses markup well need to add a tag that says "hey, I want to put some javascript on the page." We do that by adding the javascript tag in the body.

```html
<script language="JavaScript" type="text/JavaScript">
<!--//

//-->
</script>
```

In your text editor, your `starter-script.html` should look like this.

<img width="700" alt="Screen Shot 2019-03-24 at 7 00 18 AM" src="https://user-images.githubusercontent.com/25112069/54880563-1377d680-4e03-11e9-9937-e4372b533814.png">

between your opening `<script language="JavaScript" type="text/JavaScript">` tag, and your closing `</script>` tag, is where you will write your JavaScript.

**NOTE:** The `<h1>` and the `<script>` tag are both in the body and sitting below each other at the same level. In other words, they are "inside" the body tag, and the body tag is "inside" the html tag.

Lets delete the `<h1>` tag from before and write something in JavaScript instead.

Again when writing JavaScript, we will write it inside the `<script>` tag.

add the following,

```JavaScript
document.write("JavaScript is fun!")
```

If you run this, you will see:

<img width="700" alt="Screen Shot 2019-03-24 at 7 16 25 AM" src="https://user-images.githubusercontent.com/25112069/54880694-ca288680-4e04-11e9-86dc-40d73aaf8326.png">

The JavaScript line you added reads, "On the document(webpage), lets write "JavaScript is fun!" That's basically what "document.write("some text")" means.  Anyways, lets get a clean starter-script for the class so you have a nice file to work from. 

remove `document.write("JavaScript is fun!")`

Lastly, in the `<head>` tag, add:

```html
<meta charset="utf-8">
```

doing those last step, the file should look like this.

<img width="700" alt="Screen Shot 2019-03-24 at 7 25 25 AM" src="https://user-images.githubusercontent.com/25112069/54880772-07d9df00-4e06-11e9-8ccd-2ec930a1d1e4.png">

```html
<!DOCTYPE html>
<html>
      <head>
            <meta charset="utf-8">
      </head>
      <body>
            <script language="JavaScript" type="text/JavaScript">
            <!--//
                  
            //-->
            </script>
      </body>
</html>
```

If you're curious, you can read more about the `<meta>` tag at https://www.w3schools.com/tags/att_meta_charset.asp but its out of the scope for this class.