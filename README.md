# InsertionSort
Insertion Sort ödevi
[Patika.dev](https://app.patika.dev/)

 # [22,27,16,2,18,6] -> Insertion Sort
# 1.Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
```
1- Bu sayı dizisinin en küçük elemanı hangisi ise onu buluyoruz. (2)
2- Bulduğumuz en küçük sayıyı en başa yazıyoruz.
3- En başta olan sayıyla yerlerini değiştiriyoruz.
4-Aynı işlemi kalan her eleman için yapıyoruz.
Bu durumda aşamalar;
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

```
# 2.Big-O gösterimini yazınız.
```
Best Case -> O(n)
Average Case -> O(n^2)
Worst Case -> O(n^2)

```
# 3. Time Complexity -> Average case: Aradığımız sayının ortada olması, Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

```
Worst Case -> [27,22,18,16,6,2]
Average Case -> [6,16,22,2,18,27]
Best Case -> [2,16,18,22,27]

```
# 4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

```
[2,6,16,18,22,27] -> Sıralamada ortada olduğu için Average Case kapsamına girer.

```
# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

```
1-[2,3,5,8,7,9,4,15,6]
2-[2,3,4,8,7,9,5,15,6]
3-[2,3,4,5,7,9,8,15,6]
4-[2,3,4,5,6,9,8,15,7]


