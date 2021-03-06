ke_search
---------

ke_search is a search engine for the TYPO3 content management system. It is offers fulltext search and
faceting possibilities. Faceting means you can narrow down your search results by selecting certain categories,
called facets or filter options.

It is very flexible: By writing your own indexer you can put any content you want into the index.

It uses fluid templates (since version 2.0).

ke_search does not use frontend crawling but fetches content elements and data records directly from the database.
For each content type an indexer is needed (eg. pages, news).
For the most used content types indexers are provided within the extension itself, including pages, news and tt_news.
That means there may not be an indexer
already available for the content type you want to index. On the other hand, it's quite easy for a programmer
to write it's own indexer for custom data records.

There is a quickstart manual in the /doc directory.

See http://kesearch.kennziffer.com/en/documentation/introduction.html for further documentation.

If you find bugs or want to ask for a feature, please use http://forge.typo3.org/projects/extension-ke_search/issues
