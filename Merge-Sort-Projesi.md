**Proje 2**
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

**Çözüm**
        [16,21,11,8,12,22]

[16,21,11]             [8,12,22]

[16,21]  [11]        [8,12]   [22]

[16]  [21]  [11]   [8]  [12]  [22]

[16,21]  [11]       [8,12]   [22]

[11,16,21]           [8,12,22]

[8,11,12,16,21,22]

Big-O gösterimi: O(nlogn)
n=6 => O(6.log6)
