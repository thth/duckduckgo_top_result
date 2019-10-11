OpenSearch XML for a Firefox add-on to go directly to the top DuckDuckGo search result using:

```
<Url type="text/html" method="post" template="https://duckduckgo.com/html/">
  <Param name="q" value="\{searchTerms}"/>
</Url>
```