# EE16B-Notes

This repo contains my notes for EE 16B.

I compile the .tex files using pdftex, and embed graphics as .pdf.

The graphics are generated using IPE (http://ipe.otfried.org/), and the generated pdfs can be opened directly using IPE if you need to make any changes. _DO NOT_ open / edit them in anything else, as that deletes the metadata that IPE needs to preserve layers and stuff.

There's also a gigantic header at the top of each file, but most of it can be safely removed. The commands that should be preserved are:
 - The \d? and \diff commands, as I use them to avoid typing \mathrm when writing derivatives
 - The \mat and \cat commands (sorry), as I use them to avoid writing \begin{bmatrix} \end{bmatrix} all the time
 - The \eqn and \thus commands, as I use them to make my equations look more aligned
 - The \eps command, as I think \varepsilon is too long to type
 
 Hopefully these notes can be of some use!
