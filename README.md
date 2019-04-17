Closure breaking Sortable.js with `SIMPLE` optimizations.

`demo.html` behaves normally and items are animated when sorting via drag/drop.

`demo-closure.html` does the same thing only the `Sortable.js` was minified by

```
npx google-closure-compiler --js=Sortable.js --js_output_file=Sortable.closure.js
```

Things are still sortable but don't animate anymore.