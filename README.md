# Trie
## Description
Implement a Trie in Python.

## Functions
### Create an Empty tree
```
root = Trie('*')
```
### Insert 'word' into the trie
```
insert(root, 'word')
```
### Delete 'word' from the trie
```
delete(root, 'word')
```

### Lookup 'word' if it exists in the trie, or find its longest prefix
```
look_up(root, 'word')   # return exist_or_not(bool), nodes_that_walk_through(list)
```

### Print the trie (w/o root node '*')
```
print_trie(root)
```

## References
- [Trie Structure](http://pisces.ck.tp.edu.tw/~peng/index.php?action=showfile&file=f743c2923f8170798f62a585257fdd8436cd73b6d)
- [Implementing a trie in Python](https://towardsdatascience.com/implementing-a-trie-data-structure-in-python-in-less-than-100-lines-of-code-a877ea23c1a1)
