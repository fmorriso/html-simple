# html-simple
A simple example of using HTML and CSS
# Location of code
[HTML Simple](https://github.com/fmorriso/html-simple)
# Steps
## Getting Started - create shell/starter files
1.  create a new, empty directory, for example:
```
c:\projects\html\html-simple\
```
2.  use notepad or similar to create a plain text file named ```index.html```. **Be very careful** to not accidentally save it as ```index.html.txt``` which is the default action in Windows Notepad. 
3.  enter the text you see inside __**starter04.txt**__
4. open your ```index.html``` in a browser.  This can usually be done by locating the file in Windows Explorer, right-click, choose ```open with ...``` and pick one of the browsers offered.
If you are having trouble opening `index.html` from File Explorer, try opening a browser and change the address bar to the following, subsituting your directory name for the one shown below:
```html
file:///C:/projects/HTML/simple/index.html
```
2. Use Notepad to create a new file named ```styles.css``` __in the same directory as__ ```index.html```.  Add the following line to ```styles.css```:
   ```HTML
   /* future styles go in here */
   ```
   Save the file.
3. Open up ```index.html``` and add the following line just below the ```<title>``` line:
   ```HTML
   <link href="styles-final.css" rel="stylesheet">
   ```
4. Open ```index.html``` and add the following line between ```<body>``` and ```</body>```:
   
   ```
   Hello, world!
   ```
   Save the file.
5. Refresh the browser that you previously opened to see the change.

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
   <link href="styles-final.css" rel="stylesheet">
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
* [CSS Grid Layout: The fr Unit](https://www.digitalocean.com/community/tutorials/css-css-grid-layout-fr-unit)
* [CSS Grid Layout - Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
* [Learn CSS Grid the easy way video](https://www.youtube.com/watch?v=rg7Fvvl3taU)
* [Learn CSS GitHub repo](https://github.com/kevin-powell/learn-grid-the-easy-way)
* [Getting started with CSS Grid - video series](https://www.youtube.com/playlist?list=PL4-IK0AVhVjM41-Ezm5tmESVchNEi7aZU)

## Deploying to free Firebase host

1. if you have not already done so, install `nodejs` from `nodjs.org`.
1. install ```firebase-tools``` using ```npm``` 
1. establish firebase login credentials via ```firebase login```.  This only needs to happen once.
1. initialize firebase via ```firebase init``` making sure you use a unique prefix, such as ```fpm-``` when it asks for a unique website name.

## Example web site
https://fpm-html-simple.web.app/
