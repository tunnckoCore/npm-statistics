# npm-statistics

![NPM Stats](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2FDavidWells%2Fnpm-statistics%2Fmaster%2Fstats.json)

NPM Download Statistics for DavidWells Open Source Projects. Updated Daily.

## Downloads

<!-- Please do not modify this auto generated content -->
<!-- AUTO-GENERATED-CONTENT:START (PACKAGES) -->
| Name                                             | Downloads                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| ------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [message](https://www.npmjs.com/package/message) | feign.codec.DecodeException: Error while extracting response for type [class de.vorb.npmstat.clients.authors.SearchResultJson] and content type [application/json]; nested exception is org.springframework.http.converter.HttpMessageNotReadableException: JSON parse error: Unexpected end-of-input in VALUE_STRING; nested exception is com.fasterxml.jackson.databind.JsonMappingException: Unexpected end-of-input in VALUE_STRING
 at [Source: (PushbackInputStream); line: 1, column: 244415] (through reference chain: de.vorb.npmstat.clients.authors.SearchResultJson["objects"]->java.util.ArrayList[234]->de.vorb.npmstat.clients.authors.SearchResultRowJson["package"])     |
| **Sum**                                          | **feign.codec.DecodeException: Error while extracting response for type [class de.vorb.npmstat.clients.authors.SearchResultJson] and content type [application/json]; nested exception is org.springframework.http.converter.HttpMessageNotReadableException: JSON parse error: Unexpected end-of-input in VALUE_STRING; nested exception is com.fasterxml.jackson.databind.JsonMappingException: Unexpected end-of-input in VALUE_STRING
 at [Source: (PushbackInputStream); line: 1, column: 244415] (through reference chain: de.vorb.npmstat.clients.authors.SearchResultJson["objects"]->java.util.ArrayList[234]->de.vorb.npmstat.clients.authors.SearchResultRowJson["package"])** |
<!-- AUTO-GENERATED-CONTENT:END -->

### Wanna use `npm-statistics`?

1. `Fork` this repository.
2. Add your npm username/author or list of packages in `package.json` as `npm-stats` key.
   for author

```js
{
  "npm-stats": "DavidWells"
}
```

or for packages

```js
{
  "npm-stats": [
    "markdown-magic",
    "analytics"
  ]
}
```

3. Run `npm i` and then `npm start` to generate the Downloads.
4. The repo comes with a daily CRON job that updates the Downloads.
5. For updating the badge replace `DavidWells` in badge endpoint to your github username/orgname.
   https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2F`username`%2Fnpm-statistics%2Fmaster%2Fstats.json
6. Enable `GitHub Actions` for your forked repo, as it is enabled by default for forks.

## Ref

- [npmtotal](https://github.com/maddhruv/npmtotal) - Find you npm download statistics
- [Props to ClearTax for this awesome action](https://github.com/ClearTax/npm-statistics)
