

ToDo:
 
  * changelog entry in README and prologue
  * quality check - pdf-diff text contents vs. original
  * page 203: overflow
  * check: consistency of blue formatted methods (e.g. `format`, `gsub`, ...) across the book

Improvements:

  * check \consoleinline in later chapters - many of them are \rubyinline?
  * .mobi version


Changes:

  * integrated sidebars based on Alex Niesnevich's work
    - sidebars are now at the outer edges of the pages
    - using blue background color like in the original
    - relayouted them so they always start on top of the page
    - rearranged them so the (cont'd) sidebars follow right upon each other
    - made size of sidebar adjustable (e.g. for the tambourine sidebar)
  * added missing dr. cham knocking on castle drawing in chapter 4
  * added missing quils drawings at the end of chapter 6
  * replaced listings with minted package for pygmentized code highlighting
    - using minted 2.0-alpha-3 and pygments 2.0pre@e3c10ca6897f
    - highlight irb sessions and console output separately
    - use consistent fontsize for all code examples
    - worked around minor highlighting bugs
    - set \widowpenalty to prevent widows
  * corrected few occurrences of inconsistently indented code examples
  * cleaned up chapter breaks (ensure blank pages before chapter breaks) 
  * adapted papersize to 8.125 x 10.250 (and fontsize to 12pt)
