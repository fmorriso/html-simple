# html-simple
A simple example of using HTML and CSS
# Location of code
[HTML Simple](https://github.com/fmorriso/html-simple)
# Steps
## Getting Started - create shell/starter files
1.  create a new, empty directory
1.  use notepad or similar to create a plain text file named ```index.html```. **Be very careful** to not accidentally save it as ```index.html.txt``` which is the default action in Windows Notepad. 
1.  enter the text you see inside __**starter04.txt**__
1. open your ```index.html``` in a browser.  This can usually be done by locating the file in Windows Explorer, right-click, choose ```open with ...``` and pick one of the browsers offered.
1. Use Notepad to create a new file named ```styles.css``` __in the same directory as__ ```index.html```.  Add the following line to ```styles.css```:
   ```HTML
   /* future styles go in here */
   ```
   Save the file.
1. Open up ```index.html``` and add the following line just below the ```<title>``` line:
   ```HTML
   <link href="styles.css" rel="stylesheet">
   ```
1. Open ```index.html``` and add the following line between ```<body>``` and ```</body>```:
   
   ```
   Hello, world!
   ```
   Save the file.
1. Refresh the browser that you previously opened to see the change.

## Adding styles for the first time
1. Open up `styles.css`
1. Add the following lines:
   ```css
   .text-bold {
    font-weight: bold;
   }

   .text-italics {
       font-style: italic;
   }
   ```
1. open up `index.html` and verify the following line appears within the `<head>` area:
   ```html
   <link href="styles.css" rel="stylesheet">
   ```
1. Change the following line from this:
   ```html
   <span>This is going to be bold and italics</span>
   ```
   to this:
   ```html
   <span class="text-bold text-italics">This is going to be bold and italics</span>
   ```
1. Open up `index.html` in a browser and verify that the new styles have been applied.

## Grid Styles

* [CSS Grid Layout Module](https://www.w3schools.com/css/css_grid.asp)
* [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
## Deploying to free Firebase host

1. if you have not already done so, install `nodejs` from `nodjs.org`.
1. install ```firebase-tools``` using ```npm``` 
1. establish firebase login credentials via ```firebase login```.  This only needs to happen once.
1. initialize firebase via ```firebase init``` making sure you use a unique prefix, such as ```fpm-``` when it asks for a unique website name.

## Example web site
https://fpm-html-simple.web.app/
