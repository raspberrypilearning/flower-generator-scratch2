## Make a custom block to draw flowers

What if you want to draw lots of flowers? Instead of making lots of copies of the code, you will create your own block in Scratch and use it every time you want to draw a flower.  

--- task ---

Click on **More Blocks** and then on **Make a block** to create your own block called 'draw flower'.

![screenshot](images/flower-make-block.png)

--- /task ---

--- task ---

There is now a new block called `draw flower`{:class="blockmoreblocks"} in the **More blocks** section, and a new definition block on the Stage.

```blocks
draw flower :: custom

define draw flower
```

--- /task ---

--- task ---

Move your code for drawing the flower from the `when green flag clicked`{:class="blockevents"} block to the new `draw flower`{:class="blockmoreblocks"} definition block. 

Your code should look like this:

![flower sprite](images/flower-sprite.png)

```blocks
define draw flower
repeat (6) 
  stamp
  turn cw (60) degrees
end

when green flag clicked
``` 

--- /task ---

--- task ---

Add the following code to clear the Stage and to use your new `draw flower`{:class="blockmoreblocks"} block when the green flag is clicked:

![flower sprite](images/flower-sprite.png)

```blocks
when green flag clicked
clear
draw flower :: custom
```
 
--- /task ---

--- task ---

Click the green flag to test your code and check whether you see a flower. 

--- /task ---

--- task ---

Now change your code to move the sprite and then draw another flower:

![flower sprite](images/flower-sprite.png)

```blocks
when green flag clicked
clear
go to x: (75) y: (75)
draw flower :: custom
go to x: (-75) y: (-75)
draw flower :: custom 
```

--- /task ---

--- task ---

Test your code to check that you now see two flowers.

![screenshot](images/flower-two.png)  
 
--- /task ---
