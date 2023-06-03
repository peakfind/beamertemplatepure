# beamertemplatepure
A simple beamer template

This beamer template is based on [The University of Memphis Beamer Template](https://www.overleaf.com/latex/templates/the-university-of-memphis-beamer-template/mpdmwqhzmhdr). It is also a good material to learn how to write beamer template.

## Usage
You should place the `beamerthemepure.tex` with your main file together. Then add
``
\usetheme{pure}
``
in your preamble.

## Figures
### Cover
![cover](https://user-images.githubusercontent.com/37588487/234061905-57f9ca66-55ac-46e2-83b8-2c722ec7ed0a.png)
### A block
![block](https://user-images.githubusercontent.com/37588487/224881551-0d8f0080-12e3-4ad3-9e21-b7ccdd1352f7.png)
### Different blocks
![blocks](https://user-images.githubusercontent.com/37588487/234062275-f7beeade-90d0-4bb0-a558-8b9343bd7d1f.png)
### Items
![items](https://user-images.githubusercontent.com/37588487/234062467-9604fab7-a791-4bc8-8ce3-1db834c18007.png)

## Misc
It is a very simple template. You can use it as you like.

## Plan
1. We need two modes: presentation and handout. (Let beamerthemebasic be the handout mode)
2. Add an option for different backgroundcanvas: default color is white, add another color:
   ```
   \setbeamercolor{background canvas}{bg=gray!10!white}
   ```
3. Change the style of the footline: let first block show 
   - title for the titlepage
   - Outline for the tableofcontents
   - sectiontitle for other pages
   - nothing in the last page (Thankyou or Q&A)
