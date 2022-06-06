# www.patika.dev Veri yapıları ve Algoritmalar eğitimi kapsamında hazırlamış olduğum ödev

# A-1) Insertion Sort
## [22,27,16,2,18,6] -> start
## [2,27,16,22,18,6] -> step 1
## [2,6,16,22,18,27] -> step 2
## [2,6,16,18,22,27] -> step 3 End

# A-2) Big O gösterimi 
## (n-1)+(n-2)+(n-3)+...+1 = (n(n-1))/2 =O(n^2) 
# A-3) 
## Worst Case   : O(n^2)
## Average Case : O(n^2)
## Best Case    : O(n)

# A-4) Dizi sıralandıktan sonra 18 sayısı ortada olduğu için Average case kapsamına girer.


# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

## Answer = 
[2,3,5,8,7,9,4,15,6] (7-...2)(2-...7)
[2,3,4,8,7,9,5,15,6] (5-...4)(4-...5)
[2,3,4,5,7,9,8,15,6] (8-...5)(5-...8)
[2,3,4,5,6,9,8,15,7] (7-...6)(6-...7)