# Binary Search Tree Projesi
## Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

## CEVAP

root 7
- 5 < 7 olduğundan 7 nin sol tarafına gelir
- 1 < 7 olduğundan 7 nin sol tarafına gelir, 1 < 5 olduğundan 5 in sol tarafına gelir
- 8 > 7 olduğundan 7 nin sağ tarafına gelir
- 3 < 7 olduğundan 7 nin sol tarafına gelir, 3 < 5 olduğundan 5 in sol tarafına gelir, 3 > 1 olduğundan 1 in sağ tarafına gelir
- 6 < 7 olduğundan 7 nin sol tarafına gelir, 6 > 5 olduğundan 5 in sağ tarafına gelir
- 0 < 7 olduğundan 7 nin sol tarafına gelir, 0 < 5 olduğundan 5 in sol tarafına gelir, 0 < 3 olduğundan 3 ün sol tarafına gelir, 0 < 1 olduğundan 1 in sol tarafına gelir
- 9 > 7 olduğundan 7 nin sağ tarafına gelir, 9 > 8 olduğundan 8 in sağ tarafına gelir
- 4 < 7 olduğundan 7 nin sol tarafına gelir, 4 < 6 olduğundan 6 nın sol tarafına gelir, 4 < 5 olduğundan 5 in sol tarafına gelir, 4 > 3 olduğundan 3 ün sağ tarafına gelir
- 2 < 7 olduğundan 7 nin sol tarafına gelir, 2 < 6 olduğundan 6 nın sol tarafına gelir, 2 < 5 olduğundan 5 in sol tarafına gelir, 2 < 4 olduğundan 4 ün sol tarafına gelir, 2 < 3 olduğundan 3 ün sol tarafına gelir, 2 > 1 olduğundan 1 in sağ tarafına gelir

![BinarySearchTree](https://github.com/fatihkutukcu/BinaryProje/blob/main/BinarySearchTree.png)

[patika.dev adresim](https://app.patika.dev/fatihkutukcu)
