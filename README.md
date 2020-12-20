# Card Print CSS

Print standard size cards that fit [the standard size sleeves](https://boardgamegeek.com/wiki/page/Card_Sleeve_Reference#toc1).

Add the CSS file into your project and every `<img>` will print out the correct size (when printing to A4 size paper).

## Notes

The styles are only applied when printing (with `@media print` query) and they are spiced with `!important` to make it easier to splash in to an existing page that might have other styles applied.
