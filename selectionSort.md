# Selection Sort

## [22,27,16,2,18,6] -> Insertion Sort

```
1. [2,27,16,22,18,6] -> n işlem
2. [2,6,16,22,18,27] -> n-1 işlem
3. [2,6,16,22,18,27] -> n-2 işlem
4. [2,6,16,18,22,27] -> 1
```

Big-O gösterimi O(n<sup>2</sup>) dir.

> **Average Case:** [2, 6, 16, 18, 22, 27] --> dizi siralandiktan sonra 18 sayisi dizinin ortasında kaldigi icin average case kapsamina girer.

> **Worst Case:** Aradığımız sayının sonda olmasıdır.

> **Best Case:** Aradığımız sayının dizinin en başında olmasıdır.

----------

## [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

```
1. [2,3,5,8,7,9,4,15,6]
2. [2,3,5,8,7,9,4,15,6]
3. [2,3,4,8,7,9,5,15,6]
4. [2,3,4,5,6,9,8,15,7]
```