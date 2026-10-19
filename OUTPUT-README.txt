All books and languages - topics copied from existing reference.book metadata

Folder layout: book/language-book/NNN.json (example: bukhari/urd-bukhari/001.json).
Each topic file retains complete original metadata and unmodified raw hadith records.
Topic IDs, titles, grades, references, numbering, punctuation, escapes and empty text remain unchanged.
Empty topics are included as empty arrays. Section 0 stays section 0, including blank names.
Records are never assigned using inferred numeric ranges or translated topic names.
Different record counts in different languages are preserved exactly as supplied.

Each edition has index.json with topic paths, titles, counts, sizes, hashes and original record positions.
The reconstruction data in each index can restore the exact original bytes, including outer formatting.
catalog.json lists all unique editions and the five byte-identical root-level Abu Dawud aliases.
Aliases point to their canonical chunks; their records are not lost or merged with other languages.
source-inventory.json accounts for every input file except .git repository internals.
Other input files (including metadata/*.json and README.md) are copied unchanged at their original paths.
verification.json records byte-for-byte reconstruction and complete input coverage checks.

Upload the folder to your CDN and request the topic JSON needed by the reader.
Application integration and CDN deployment are separate from this file conversion.
