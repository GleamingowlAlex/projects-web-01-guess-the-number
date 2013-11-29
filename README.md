Guess The Number - An Introduction HTML and Javascript
======================================================

Getting Started
---------------

### Locate the `index.html` file and open with a text editor

On the Raspberry Pi, use the File Manager to find the `GuessTheNumber` folder within the `Projects` folder. Right click `index.html` and open with Geany.

Also double click the `index.html` file to open it in your web browser.

### Play with the game

Observe the behaviour of the game and look at how the code works. If you're feeling adventurous, modify and/or break the code to see what happens...

TIP: To see your changes to the code take effect, save the file, then press F5 in your web browser.

Improve the game
----------------

### Make hints more helpful
Modify the code so that the provided hints are more useful.

### Make hints different colours
Use CSS classes to make the hints different colours i.e. Red for too big and Blue for too small.

#### In the `style` tag, make elements with class `too-big` turn red
```css
.too-big {
    color: red;
}
```

#### In the `script` tag, add this line to the `showHint` function
```javascript
hint.className = 'too-big';
```

Try repeating the above for the "too small" hint.

Help
----

