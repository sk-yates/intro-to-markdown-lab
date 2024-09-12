# How to write an HTML Boiletplate

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

    // To contain your various divs, buttons and other HTML elements.

</body>
</html>
```

## Doc type and language
At the very top of our boiler plate we find the doc type and language tags. 

 - `<!DOCTYPE html> </html>` This tells the browser that our document is the most current version of **HTML** and contains the rest of the **HTML** content.
 - `<html lang="en">` This tag tells the browser what language we will be writing our code in. In this case 'English'.


## The document **`<head>`**

In the example above, we have The **head** tag: `<head>  </head>`   

The head section contains *meta-information* about the webpage, such as:  
- **The page's title** 
- **character encoding**
- **viewport settings** 

>**Note:** This content isn’t displayed directly on the webpage or to the user.

### The character encoding
---

`<meta charset="UTF-8">` 

The specifies the character encoding, which ensures that the page displays special characters correctly. 
> **UTF-8** is a standard encoding that supports most characters from different languages.

### The viewport Settings
---

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`: 

This ensures the page is responsive by setting the correct width for mobile and desktop devices. 

>**Note**: This is essential for mobile-friendly pages.

### The page title
---

`<title>Document</title>` 

This sets the title of the page that appears in the browser tab.


## The Viewport Settings
`<body> </body>`

This is where the actual content of the webpage goes. 

> Anything inside the <body> tag will be shown on the page itself.