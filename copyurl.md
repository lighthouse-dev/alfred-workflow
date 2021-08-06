# copyurl

[fallroot/copy-url-for-alfred: You can copy browser's URL and title with various formats like markdown, anchor tag and your own.](https://github.com/fallroot/copy-url-for-alfred)

```txt
vim ~/Library/Application\ Support/Alfred/Workflow\ Data/com.fallroot.copyurl/config.json
```

```json
[
  {"format":"${url}","title":"URL"},
  {"format":"${title}\n${url}","title":"TITLE + URL"},
  {"format":"[${title}](${url})","title":"Markdown"}
]
```
