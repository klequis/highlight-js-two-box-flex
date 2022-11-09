# highlight-js-two-box-flex

I recently had to create side-by-side, before & after code examples. Highlighting was done via highlightjs and the code needed to scroll when the page was two narrow.

Unfortunately, highlightjs interferes with having the code scroll and there are a number of solutions on Stackoverflow that didn't work for me.

My solution was to put each `<pre><code>` in a `div` and use `overflow-x: auto` on the `div` and not the `pre` or `code`. However, they can be there if needed for other reasons.
