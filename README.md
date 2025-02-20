# [XML Toolkit](https://github.com/do-/node-xml-toolkit)
XML parser, marshaller, pretty printer, SOAP adapter

# [`doix`](https://github.com/do-/node-doix) framework
yet another minimalistic general purpose middleware platform featuring:
* Relational [DB](https://github.com/do-/node-doix-db) backends for [PostgreSQL](https://github.com/do-/node-doix-db-postgresql), [ClickHouse](https://github.com/do-/node-doix-db-clickhouse);
* [HTTP](https://github.com/do-/node-doix-http) binding with [JWT](https://github.com/do-/node-doix-http-cookie-jwt), [Redis](https://github.com/do-/node-doix-http-cookie-redis) authentication plugins;
* plugins for [DevExtreme](https://github.com/do-/node-doix-devextreme), [w2ui](https://github.com/do-/node-doix-w2ui) Web UI libraries.

## Some related modules to be used with or without `doix`:
### File System
* [dir-list](https://github.com/do-/node-dir-list) Iterating over file paths in a given set of directories, lambda filters
* [file-path-maker](https://github.com/do-/node-file-path-maker) organize incoming files in a predictably growing hierarchy

### Logging
* [events-to-winston](https://github.com/do-/node-events-to-winston) Observing an EventEmitter, logging to winston

### Security
* [pwd-shaker](https://github.com/do-/node-pwd-shaker) password hashing with salt, pepper

# String manipulation
Some hand made finite atomata, replacing trivial RegExps for the sake of performance:
* [string-escape-map](https://github.com/do-/node-string-escape-map) Escape a given map of special characters
* [string-is-uuid](https://github.com/do-/node-string-is-uuid) RegExp free UUID validator
* [string-normalize-space](https://github.com/do-/node-string-normalize-space) XPath 1.0 normalize-space analog
* [string-replace-balanced](https://github.com/do-/node-string-replace-balanced) Replace simple custom tags

# Other, by file format
## CSV
* [csv-events](https://github.com/do-/node-csv-events) An event based CSV parser
* [untar-csv](https://github.com/do-/node-untar-csv) Read a tar of multiple csv files as a stream of objects

## DBF
* [dbf-reuse](https://github.com/do-/dbf-reuse) Using old .dbf files as templates for new ones

## XLSX
* [xlsxtream](https://github.com/do-/xlsxtream) Reading XLSX spreadsheets in streaming mode with limited memory 

<!--
**do-/do-** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- ⚡ Fun fact: ...
-->
