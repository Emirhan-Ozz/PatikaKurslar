# Proje 1 
## Insertion Sort
[22,27,16,2,18,6] -> Insertion Sort 
[22,27][16,2,18,6] 
[16,22,27][2,18,6]
[2,16,22,27][18,6]
[2,16,18,22,27][6]
[2,6,16,18,22,27]

## BigO Hesabı
[27,22,18,16,6,2]  1 control (22<27)
[22,27][18,16,6,2] 2 controls (18<27) and (18<22)
[18,22,27][16,6,2] 3 controls (16<27), (16<22) and (16<18)
[16,18,22,27,][6,2] 4 controls (6<27), (6<22), (6<18) and (6<16)
[6,16,18,22,27][2] 5 controls (2<27), (2<22), (2<18), (2<16) and (2<6)
[2,6,16,18,22,27] (Worst Case) [(n^2-n)/2] = 15 controls 

O(n^2) Worst Case grafiği benzeyeceği için

## Time Complexity (18)
Ortada olduğu için Average Case'e girer çünkü sadece 3 karşılaştırma (27,22 ve 18) yaparız. (n/2)

# Selection Sort
[7,3,5,8,2,9,4,15,6]
[2][7,3,5,8,9,4,15,6] 8 control
[2,3][7,5,8,9,4,15,6] 7 control
[2,3,4][7,5,8,9,15,6] 6 control
[2,3,4,5][7,8,9,15,6] 5 control

