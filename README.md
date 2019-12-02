WebExtensions search overrides [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-top-result/) for going directly to the top DuckDuckGo search result using:

```json
"search_url": "https://duckduckgo.com/html/",
"search_url_post_params": "q=\\{searchTerms}",
```