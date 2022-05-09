# patikaalgoritmaprojeleri
www.patika.dev  platformu için hazırlanan Veri Yapıları ve Algoritmalar dersi proje ödevleri

İLK PROJE

Proje 1 

Proje 1
[22,27,16,2,18,6] -> Insertion Sort

1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

2.Big-O gösterimini yazınız.

O(n^2)

3.Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
 Best case: Aradığımız sayının dizinin en başında olması.

4.Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case: Aradığımız sayının ortada olması.

5.[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
[2,3,4,5,6,7,8,15,9]![image](https://user-images.githubusercontent.com/65098878/167393262-aa590498-8253-4056-bbe2-0dc61917716c.png)


İKİNCİ PROJE

Proje 2
[16,21,11,8,12,22] -> Merge Sort

1.Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16,21,11,8,12,22]

[16,21,11] --- [8,12,22]

[16],[21,11] --- [8,12],[22]

[11,16,21] --- [8,12,22]

[8,11,12,16,21,22]




Big-O gösterimini yazınız.

O(nlogn)
![image](https://user-images.githubusercontent.com/65098878/167393297-910dd319-052f-4ee6-8b05-a814f4efa333.png)


ÜÇÜNCÜ PROJE 

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Root 7 dir

5 : root 7 olup 7 den küçük olduğu için solunda bulunur 
1: root 7 olup    7 ve 5 ten küçük olduğu için her ikisinin solunda bulunur
8:     root 7 olup 7 den büyük olduğu için sağında bulunur
3: root 7 olup 7 den küçük olduğundan 7 ve 5 ten küçük olduğu için solunda 1 den büyük olduğu için sağında bulunur
6.root 7 olup 7 den küçük olduğundan solunda ve 5,3,1 den büyük olduğu için sağında bulunur
0:root 7 olup 7,5,3,1 den küçük olduğu için solunda bulunur
9:root 7 olup 7 ve 8 den büyük olduğu için sağında bulunur
4:root 7 olup 7 ve 5 in solunda 3 ve 1 den büyük olduğu için sağında bulunur
2.root 7 7,5,4,3 ün solunda ve 0 ile 1 den büyük olduğu için sağında bulunur


![image](https://user-images.githubusercontent.com/65098878/167393359-df1d2752-f566-44d2-831a-2182a502e4a0.png)
