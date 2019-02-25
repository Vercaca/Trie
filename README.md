# Implement a Trie in Python.
## Description of Trie (小筆記)
Trie為字典樹/單詞搜尋樹，快速依字母插入、尋找字串，其結構如下圖：

![Figure 1. Trie Data Structure](https://4.bp.blogspot.com/-GNWc5KUMGYc/WAskP-EHFKI/AAAAAAAAEz4/8yikxc2niYgyqH0FWFafq5UTp_kUK6O5ACLcB/s1600/TrieDataStructureImpl.png)

Figure 1. Trie Data Structure (Java2Blog - Trie data structure in java)

#### Property：
- 以每個字的共同前綴(Common Prefix)當儲存依據，並以此來節省儲存空間及加速搜尋時間。
- 一個Node是一個字母（Root除外）
- 每棵Trie的高度為最長字串長度+1 (因為還有root)


## Functions
#### Create an Empty tree
```
root = Trie('*')
```
#### Insert 'word' into the trie
```
insert(root, 'word')
```
#### Delete 'word' from the trie
```
delete(root, 'word')
```

#### Lookup 'word' if it exists in the trie, or find its longest prefix
```
look_up(root, 'word')   # return exist_or_not(bool), nodes_that_walk_through(list)
```

#### Print the trie (w/o root node '*')
```
print_trie(root)
```

## References
- [Trie Structure](http://pisces.ck.tp.edu.tw/~peng/index.php?action=showfile&file=f743c2923f8170798f62a585257fdd8436cd73b6d)
- [Implementing a trie in Python](https://towardsdatascience.com/implementing-a-trie-data-structure-in-python-in-less-than-100-lines-of-code-a877ea23c1a1)
- [Java2blog - Trie data structure in java](https://java2blog.com/trie-data-structure-in-java/)
