# DomainX
An experimental html application providing variable paintbrush sizes to draw. This is my first attempt at understanding how MSPaint's Pencil or Snipping Tool's Pen works.

This application can be run directly on a Windows OS using *DomainX.hta* file, or directly on a Web Browser using *Data.htm* file.
* **Usage and Basic Info :**
  * Run the application in either of the two ways stated above.
  * Top left corner depicts cursor coordinates.
  * Pointer itself is a custom DIV.
  * The application works better in a browser.
  * This application makes use of svg.
* **Shortcut Keys :** *(Single Click types)*
  * **z/Z Key -**
    - Changes Pointer size and makes it bigger.
    - This indicates the activation of cursor as *penmode*.
    - Press Left Mouse button and drag on the screen in any curvy manner, that design will get printed on screen on leaving the mouse button.
    - Multiple lines can be made on screen.
  * **+/- Key -**
    - There are five Pointer sizes. 
    - **+** key can increase Pointer size.
    - **-** key can reduce Pointer size.
    - The Pointer Size will also determine the thickness of design in *penmode*.
  * **i/I Key -**
    - Due to some fault, works only in Web Browser.
    - It can make all the designs on screen disappear or reappear.
  * **e/E Key -**
    - Due to some known fault, this doesn't work yet.
    - It is supposed to activate 'Eraser' mode to rub the designs.
  * **Right Mouse Button -**
    - Erases all designs from screen.
    - This is more like a 'RESET' button.
