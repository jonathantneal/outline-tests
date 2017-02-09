# Headings test

This is a test to see how differing heading techniques are interpretted by browsers, accessibility tools, and possibly even search engines.

---

The [h.html] file uses the `<h>` element for headings. It relies on sectioning containers like `<section>` to give headings contextual meaning. This is done by using the [hfill] polyfill to assign `<h>` elements a role and aria-level based on their position within the document outline.

The [h1.html] file uses the `<h1>` element for headings. It relies sectioning containers like `<section>` to give headings contextual meaning. This is done by expecting the browser to interpret the outline algorithm.

The [hn.html] file uses `<h1>` through `<h6>` elements for headings. It relies on tag names to give headings contextual meaning. This is done by explicitly giving headings a tag name corresponding to their position within the document outline.

---

Learn more about [Outline Tests].

[h.html]: https://jonathantneal.github.io/outline-tests/tests/headings/h.html
[h1.html]: https://jonathantneal.github.io/outline-tests/tests/headings/h1.html
[hn.html]: https://jonathantneal.github.io/outline-tests/tests/headings/hn.html
[Outline Tests]: https://github.com/jonathantneal/outline-tests
