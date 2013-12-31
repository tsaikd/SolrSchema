SolrSchema
==========

主要是在 cjk 的部分，加上簡轉繁，這樣簡繁體都能檢索到。

```
<charFilter class="solr.MappingCharFilterFactory" mapping="mapping-zh-s2t.txt"/>
```

