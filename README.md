# Merge-Sort
patika.dev
Proje 2
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

---

[16,21,11,8,12,22]

#### Divide
[22,27,16]  [2,18,6] 

#### Divide Left
[22,27] [16]  [2,18,6]

#### Sort Left
[16, , ]   [2,18,6]
[22,27] []  

[16,22,27]  [2,18,6]

#### Divide Right
[16,22,27]  [2,18] [6]

#### Sort Right
[16,22,27]  [2, , ]
[16,22,27]  [ ,18] [6]

[16,22,27]  [2,6,18]

#### Combine
[ , , , , , ]
[16,22,27]  [2,6,18]

[2, , , , , ]
[16,22,27]  [ ,6,18]

[2,6, , , , ]
[16,22,27]  [ , ,18]

[2,6,16, , , ]
[ ,22,27]  [ , ,18]

[2,6,16,18, , ]
[ ,22,27]  [ , , ]

[2,6,16,18,22,27]

---

Big-O Notation = n(logn
