# -Insertion-sort-Projesi [22,27,16,2,18,6]
-2.elemana bakılır (27) soldaki değerle kıyaslama yapılır. Eğer sayı soldaki değerinden büyükse olduğu yerde kalır fakat soldaki sayıdan daha küçükse soldaki sayı ile yer değiştirir.
- 27 sayısı 22 den büyük o yüzden yerinde kalır, sağındaki değere bakılır. 16 sayısı 27 den küçük yer değiştirilir -> [22,16,27,2,18,6]
- [16,22,27,2,18,6]
- [16,22,2,27,18,6]
- [16,2,22,27,18,6]
- [2,16,22,27,18,6]
- [2,16,22,27,6,18]
- [2,16,22,6,27,18]
- [2,16,6,22,27,18]
- [2,6,16,22,27,18]
- [2,6,16,22,18,27]
- [2,6,16,18,22,27]
-Burada bakış açısı önemli.  Verilen diziyi eşit miktarda 2 ye ayırdığımız zaman solda 2,6,16 sayıları kalıyor. Sağda ise 18,22,27 kalıyor. Sağdaki dizinin ilk sayısı 18 oldugu için Best Case diyebiliriz. 

# [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
-[3,7,5,8,2,9,4,15,6]
-[3,5,7,8,2,9,4,15,6]
-[3,5,7,2,8,9,4,15,6]
-[3,5,2,7,8,9,4,15,6]

