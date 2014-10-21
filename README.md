BookSearch-Backend
==================

This is the backend configuration of BookSearch project found at https://github.com/ararog/BookSearch

The configuration backend is divided into two components, the search engine and the crawler.

## Search engine

The search engine used by this project is Elasticsearch, the documents to be indexed are provided 
by Apache Nutch, which performs a filesystem crawl, please take a look on file elasticsearch/config/index.settings.txt,
this file contains all commands to be executed to create the elasticsearch document collection and how to upload
its indexing and search settings (analysers and filters).

## Crawler

This project uses Apache Nutch to perform filesystem crawl, this configuration includes connection
settings to elasticsearch and a minor change on crawl script in order to make it work properly with
elasticsearch indexer.

## Tags

Search Elasticsearch Apache Nutch Perl Catalyst

