# 刪除索引


1. 複製索引至新索引

```
POST /_reindex
{
  "source": {
    "index": "old_index"
  },
  "dest": {
    "index": "new_index"
  }
}
```

2. 刪除舊索引

```
DELETE /old_index
```

## 參考資料
* [elasticsearch - how to rename an index in a cluster? - Stack Overflow](https://stackoverflow.com/questions/28626803/how-to-rename-an-index-in-a-cluster)
