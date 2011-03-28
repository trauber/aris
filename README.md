
# aris


Poor [Ares][] reserve processor's [RIS][] to [AutoHotkey][] converter
in javascript with help from [mustache.js][].


The AutoHotkey template is customized for my workplace.


Aris produces two types of AutoHotkey for RIS with type BOOK or JOUR.
BOOK is for Ares's mongraph template and JOUR for the serial.


## Installation
1. Go to the home page for [Aris][] (https://github.com/trauber/aris).
2. Click the `Downloads` icon over on the right side of the page.
3. Download the `.zip` archive.
4. Right mouse click on the `.zip` archive.
5. Extract all files.  The folder can go anywhere convenient for you,
   but I suggest the desktop.

## Usage
1. Click the `aris.html` icon so it opens in your web browser. (Your
   browser should have javascript enabled.)
2. "Export" (download) an RIS file from a database.  (Configure your
   browser to open `.ris` files in notepad.)
3. Use `Ctrl-a` and `Ctrl-x` to copy the RIS to the clipboard and remove it from notepad.
4. Paste the record into aris's textarea with `Ctrl-v`.
5. Click aris's `convert RIS to AutoHotkey` button.
6. Use `Ctrl-a` and `Ctrl-x` to copy the AutoHotkey script to the clipboard and clear aris.
7. In notepad use `Ctrl-v` to place the AutoHotkey script in notepad.
8. In notepad save the file with a `.ahk` extension. (Again, your
    desktop is the best place.)
9. Open the add item button in Ares, select your template.
10. Double click the `.ahk` icon to export the bib info into Ares.


[Ares]: http://www.atlas-sys.com/products/ares/
[Aris]: https://github.com/trauber/aris
[AutoHotkey]: http://www.autohotkey.com
[mustache.js]: https://github.com/janl/mustache.js
[RIS]: http://en.wikipedia.org/wiki/RIS_(file_format)
