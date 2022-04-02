# Proje 3

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız

### Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1. Ilk elemeni root olarak aliriz.
   1. Root: 7

```text
    -------------------------------------------------     2.      5 -> root'un solunda bulunur
    -------------------------------------------------     3.      1 -> root'un ve 5'in solunda bulunur 
    -----------------------(7)-----------------------     4.      8 -> root'un saginda bulunur
    -------------------(5)-----(8)-------------------     5.      3 -> root'un ve 5'in solunda, 1'in saginda bulunur
    ---------------(1)----(6)------(9)---------------     6.      6 -> root'un solunda, 5'in saginda bulunur
    -----------(0)----(3)----------------------------     7.      0 -> root'un, 5'in ve 1'in solunda bulunur
    ---------------(2)---(4)-------------------------     8.      9 -> root'un ve 8'in saginda bulunur
    -------------------------------------------------     9.      4 -> root'un ve 5'in solunda, 1'in ve 3'un saginda bulunur
    -------------------------------------------------     10.     2 -> root'un, 5'in ve 1'in solunda, 0'in saginda bulunur    
```
