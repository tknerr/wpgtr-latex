

ToDo:
 
  * integrate sidebars!
  * changelog entry in README and prologue
  * quality check - pdf-diff text contents vs. original

Minted Issues:

  * various overflows, e.g. on pages 30, 51(!), 65 (!!!), 104, 136 (!)
  * ranges not correctly highlighted yet, see https://bitbucket.org/birkenfeld/pygments-main/issue/1031/ruby-ranges-not-highlighted-correctly

Improvements:

  * remove blank pages before toc?
  * add boxes / frames around rubycode environments?
  * keep syntax highlighting in tables on p206?
  * .mobi version

Changes:

  * replaced listings with minted package for pygmentized code highlighting
    - using minted 2.0-alpha-3 and pygments 2.0pre@5b117d51abe0
    - highlight irb sessions and console output separately
    - use consistent fontsize for all code examples
    - worked around minor highlighting bugs
    - set \widowpenalty to prevent widows
  * corrected few occurrences of inconsistently indented code examples
  * cleaned up chapter breaks (ensure blank pages before chapter breaks) 
  * adapted papersize to 8.125 x 10.250 (and fontsize to 12pt)
