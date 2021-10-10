# Kandinsky-Numworks
This module depend to [Pygame](https://fr.wikibooks.org/wiki/Pygame/Introduction_%C3%A0_Pygame) module. To install it, click [here](https://github.com/ZetaMap/Kandinsky-Numworks/blob/main/FAQ.md#how-to-install-pygame) and follow steps. <br>
A small module allowing to link the kandinsky module, from the Numworks, to a Windows window. 
Useful if you want to test your program without putting it on the calculator. <br><br>
**/!\\WARNING:** Windows works differently in window management. <br>
If you want to keep the window open, you will have to call the  function ``display()`` at the end of your program, but it will block your program. If you do not call this function, the window will appear at the beginning of your program and will close at the end of it. **/!\\**

### More
I also recreated the ion module of the Numworks, check it out here: [Ion module of Numworks](https://github.com/ZetaMap/Ion-numworks)<br>
If you have a question, check out the [FAQ](https://github.com/ZetaMap/Kandinsky-Numworks/blob/main/FAQ.md). And if you want to make a suggestion or your question is not answered, open an [Issue](https://github.com/ZetaMap/Kandinsky-Numworks/issues/new).

### Usable content
**get_pixel**:
* Parameters: ``x``, ``y``
* Description: Return pixel (x, y) color

**set_pixel**
* Parameters: ``x``, ``y``, ``color``
* Description: Color pixel (x, y)

**color**
* Parameters: ``r``, ``g``, ``b``
* Description: Define a rgb color

**draw_string**
* Parameters: ``text``, ``x``, ``y``, ``color`` **[default : (0,0,0)]**, ``background`` **[default : (255,255,255)]**
* Description: Display a text from pixel (x, y)

**fill_rect**
* Parameters: ``x``, ``y``, ``width``, ``height``, ``color``
* Description: Fill a rectangle at pixel (x, y)

**display**
* Parameters:
* Description: Run an infinite loop (a little modified) allowing to keep the window open
