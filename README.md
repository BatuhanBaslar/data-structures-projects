# data-structures-projects
#Selection Sort

**Soru 1)**
```
[22,27,16,2,18,6]
```
 Yukarı verilen dizinin insertion sort türüne göre aşamalarını yazınız.
 ```
 Answer

   Step 1: [22,27,16,2,18,6] //Since 22 is already lesser than 27 no sorting was done.
   Step 2: [22,16,27,2,18,6] // 27 to 16 places changed.
   Step 3: [16,22,27,2,18,6] // 22 to 16 places changed.
   Step 4: [16,22,2,27,18,6] // 27 to 2 places changed.
   Step 5: [16,2,22,27,18,6] // 22 to 2 places changed.
   Step 6: [2,16,22,27,18,6] // 16 to 2 places changed.
   Step 7: [2,16,22,18,27,6] // 27 to 18 places changed.
   Step 8: [2,16,18,22,27,6] // 22 to 18 places changed.
   Step 9: [2,16,18,22,6,27] // 27 to 6 places changed.
   Step 10: [2,16,18,6,22,27] // 22 to 6 places changed.
   Step 11: [2,16,6,18,22,27]  // 18 to 6 places changed.
   Step 12: [2,6,16,18,22,27]  // 16 to 6 places changed.
 ```

Big-O gösterimini yazınız.
```
    Step 1: 1
    Step 2: 2
    Step 3: 3
    .
    .
    Last Step: n

    Sum: (n*(n+1)/2) --> O(n^2)
```

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız.
```

Worst Case: Aranan sayının sonda olması

```


