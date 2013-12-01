Guess The Number - An Introduction HTML and Javascript
======================================================

Getting Started
---------------

### Locate the `index.html` file and open with a text editor

- Raspberry Pi - Use the File Manager to find the `GuessTheNumber` folder within the `Projects` folder. Right click `index.html` and open with Geany.

- Computer - Go to https://github.com/cjdell and find the "projects-web-01-guess-the-number" repository. Open the index.html file and copy and paste the source code to a new file using a text editor (i.e. Notepad) on your computer.

Also double click the `index.html` file to open it in your web browser.

### Play with the game

Observe the behaviour of the game and look at how the code works. If you're feeling adventurous, modify and/or break the code to see what happens...

TIP: To see your changes to the code take effect, save the file, then press F5 in your web browser.

Improve the game
----------------

### Use CSS to make the game more attractive
```css
h1 {
    font-family: Arial;
    color: red;
}
```

Try adding the above code to the `style` tag.

Think you can do better? Try styling other elements such as the `p` and `button` tags.

### Make hints more helpful
Modify the code in the `giveHint` function so that the provided hints are more useful.

```javascript
else if (difference < 0 && difference > -10) {
    // Player is only 10 away, let them know that they are warm
    hint.innerHTML = "Nearly there, try bigger";
}
```

The above code can be added to the if statement, can you figure out where?

What else needs to be added so that the same can be done for guesses that are too big?

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

Try repeating the above but for the "too small" hint.

Help
----

If you get stuck don't be afraid to ask someone for help. :-)