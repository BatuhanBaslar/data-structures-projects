# data-structures-projects
# Merge Sort

```
[16,21,11,8,12,22]
```
Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
```
Answer

Adım 1:               [16,21,11]                             [8,12,22]
                    /           \                         /           \
Adım 2:          [16,21]    -    [11]                  [8,12]    -    [22]
                /        \             \               /      \            \
Adım 3:      [16]    -    [21]    -    [11]        [8]     -    [12]    -    [22]   
                \       /              /             \         /            /
Adım 4:          [16,21]    -    [11]                  [8,12]    -    [22]
                     \            /                        \           /
Adım 5:                [11,16,21]                            [8,12,22]
                                  
Adım 6:                               [8,11,12,16,21,22]
```

Big-O gösterimini yazınız.

```
O(nlogn)
```
