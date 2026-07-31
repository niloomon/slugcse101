Course homepage
https://niloomon.github.io/slugcse101/

This is a template. Everything written in CAPITALS in index.md is a placeholder
to fill in or delete.


How to edit the page
--------------------

Edit index.md.  That is the only file with content in it; everything else is
machinery.  The notes at the bottom of the file show how to write tables,
lists and links.

Two rules that are easy to trip over:

  - Keep each paragraph on one long line.  A line break in the middle of a
    paragraph becomes a line break on the page.

  - Do not start a line with spaces or a tab unless you mean it to be a
    bullet.  Indented lines are turned into bullet points.

The title and subtitle at the very top of index.md must stay inside quotes,
because a title with a colon in it is not valid YAML without them.


How to preview it
-----------------

   ./show

This converts index.md to index.html and opens it in Safari.  Nothing is
published yet, so preview as often as you like.


How to publish it
-----------------

   ./update

This converts index.md to index.html and pushes everything to GitHub, which
publishes it at https://niloomon.github.io/slugcse101/ within a minute.

To use your own commit message:  ./update "Add week 3 slides"


Folders
-------

   lectures/    the lecture slides; link them from the Slides column of the
                schedule tables, like this:  [slides](lectures/L1.pdf)
   images/      pictures used in the page, such as a banner at the top

The rest of the files are machinery: md2html does the markdown to html
conversion, template.html is the page skeleton it fills in, and styling.css
and styling.js give the page its look.


Setup on a new machine
----------------------

The scripts need pandoc.  On macOS:

   brew install pandoc

If brew is not installed, get it from https://brew.sh first.

If the scripts do not run, make them executable once:

   chmod +x md2html show update


GitHub Pages
------------

Unlike a personal site, a project repository like this one does not become a
web page on its own.  Someone with admin rights on the repository has to turn
it on once, under

   Settings -> Pages -> Build and deployment
   Source: Deploy from a branch
   Branch: main    Folder: / (root)

After that every ./update publishes automatically.
