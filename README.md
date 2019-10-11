OpenSearch XML for a [Firefox add-on](https://addons.mozilla.org/en-US/firefox/addon/duckduckgo-top-result/) to go directly to the top DuckDuckGo search result using:

```xml
<Url type="text/html" method="post" template="https://duckduckgo.com/html/">
  <Param name="q" value="\{searchTerms}"/>
</Url>
```

---
I recommend using ```q``` for the search engine keyword!