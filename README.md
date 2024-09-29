# insertion_sort
[22,27,16,2,18,6] -> Insertion Sort

i)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

-[2,27,16,22,18,6] (1)
-[2,6,16,22,18,27] (2)
-[2,6,16,22,18,27] (3)
-[2,6,16,18,22,27] (4)
-[2,6,16,18,22,27] (5)
-[2,6,16,18,22,27] (6)

ii)Big-O gösterimini yazınız.

(1) n
(2) n-1
...
(n) 1

total sum= n*(n-1)/2 --> O(n^2)

iii)Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

18 ortada olduğundan dolayı: Average case

[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

-[2,3,5,8,7,9,4,15,6]
-[2,3,5,8,7,9,4,15,6]
-[2,3,4,8,7,9,5,15,6]
-[2,3,4,5,7,9,8,15,6]
