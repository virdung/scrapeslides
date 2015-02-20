Scrape slides
=============

A simple Node.js screen scraper that puts the results into a slide interface

Bugs
----
- Usually doesn't work on first load/timeouts
- One non-responsive source should not crash entire app

Backlog/Ideas
----
- First page could be some sort of overview page with quick links to results
- Open up loading of source data
- Threading
- Style transformation for every source
- Sort order
- Load/parse/convert PDF (docx? pdf2json?) instead of just <object>
- A pretty background image
- Add fields to sources: coordinates, homepages, other metadata...
- Sort by/highlight suggestions depending on keywords

Done
----
- ~~Caching~~
- ~~Add regex link support for PDF files~~
- ~~Add support for locating link if it's not the same ~~
- ~~Make app generic/load source data from json~~
- ~~Templating~~
- ~~Maybe a simple navigation with one result per slide instead of a more complex column-based presentation (Reveal.js?)~~