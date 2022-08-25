# Selection Sort Project

## Project 1
[22,27,16,2,18,6]->Selection Sort

1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
4. [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre adımlarını yazınız.

**Time Complexity:** 
- **Average case:** Aradığımız sayının ortada olması,
- **Worst case:** Aradığımız sayının sonda olması, 
- **Best case:** Aradığımız sayının dizinin en başında olması.

## Answer 1:

- Dizinin ilk hali --> [22,27,16,2,18,6]
- 2 ile 22 yer değiştirir --> [2,27,16,22,18,6]
- 6 ile 27 yer değiştirir --> [2,6,16,22,18,27]
- 16 zaten yerinde. Bu yüzden değişiklik olmayacak. --> [2,6,16,22,18,27]
- 18 ile 22 yer değiştirir. --> [2,6,16,18,22,27]
- 22 zaten yerinde --> [2,6,16,18,22,27]
- 27 zaten yerinde --> [2,6,16,18,22,27]

## Answer 2: 
O(n²)

## Answer 3:
Average Case

## Answer 4:

- Dizinin ilk hali --> [7,3,5,8,2,9,4,15,6]
- 2 ile 7 yer değiştirir. --> [2,3,5,8,7,9,4,15,6]
- 4 ile 5 yer değiştirir. --> [2,3,4,8,7,9,5,15,6]
- 5 ile 8 yer değiştirir. --> [2,3,4,5,7,9,8,15,6]
- 6 ile 7 yer değiştirir. --> [2,3,4,5,6,9,8,15,7]
- 7 ile 9 yer değiştirir. --> [2,3,4,5,6,7,8,15,9]
- 9 ile 15 yer değiştirir --> [2,3,4,5,6,7,8,9,15]
