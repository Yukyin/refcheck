# RefCheck

Check every entry in a BibTeX file against DBLP, Crossref and OpenAlex. Anything that cannot be confirmed is flagged for manual review.

<a href="https://yukyin.github.io/refcheck/"><img src="open-button.svg" alt="Open RefCheck" width="180"></a>

## Results

| Result | Meaning |
|---|---|
| Verified | Matches a database record. |
| Mismatch | The paper exists, but some details differ. The database record is shown. |
| Uncertain | A close but not exact title match, or the entry lacks a field. |
| Not found | No matching record. Books, web pages and some workshop papers are often not indexed. |
| Lookup failed | A database did not respond for this entry. Retry. |

Each entry also links to a Google Scholar search for manual checking.

## Scope

RefCheck verifies that a reference exists and that its metadata is correct. It does not judge whether a citation supports the claim it is attached to.

## License

MIT
