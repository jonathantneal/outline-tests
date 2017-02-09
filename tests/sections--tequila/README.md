# Sections “Tequila” test

This is a test to see how differing heading techniques are interpretted by browsers, accessibility tools, and possibly even search engines.

---

The [h.html] file uses `<h>` elements for headings. It relies on sectioning (`<section>`) elements to give headings their contextual meaning. This is accomplished with the [hfill library], which assigns `<h>` elements a `role` and `aria-level` based on their position within the document outline.

The [h1.html] file uses `<h1>` elements for headings. It relies on sectioning (`<section>`) elements to give headings their contextual meaning. This is accomplished with the browser, which we expect to interpret the document outline.

The [hn.html] file uses `<h1>` through `<h6>` elements for headings. It relies on explicit tag names to give headings their contextual meaning. This is accomplished by using exact `<h1>` through `<h6>` elements corresponding to their position within the document outline.

---

Learn more about [Outline Tests].

[hfill library]: https://github.com/jonathantneal/hfill
[h.html]: https://jonathantneal.github.io/outline-tests/tests/sections--tequila/h.html
[h1.html]: https://jonathantneal.github.io/outline-tests/tests/sections--tequila/h1.html
[hn.html]: https://jonathantneal.github.io/outline-tests/tests/sections--tequila/hn.html
[Outline Tests]: https://github.com/jonathantneal/outline-tests
