#SelectionSortProjesi

1)

[22,27,16,2,18,6] dizisinin insertionsorta göre aşamaları:
[2,22,27,16,18,6] -> [2,6,22,27,16,18] -> [2,6,16,22,27,18] -> [2,6,16,18,22,27] 

Dizide n tane eleman varsa n sayısı kadar işlem yapılır ve en küçük sayı bulunur. Sonra bu işlem tekrar n-1 sayı kadar için yapılır. Bu böyle böyle devam eder.
Elimizde n+(n-1)+(n-2)+.....+1 tane işlem eder. ((n^2 + n)/2). n^2 dominant olduğu için bu Sort algoritmasının BigO'su = O(n^2)dir.

2)

18 sayısı average casedir.

3)

[7,3,5,8,2,9,4,15,6] dizisinin sortlanmasının ilk dört aşaması:

[2,7,3,5,8,9,4,15,6] -> [2,3,7,5,8,9,4,15,6] -> [2,3,4,7,5,8,9,15,6] -> [2,3,4,5,7,8,9,15,6]
