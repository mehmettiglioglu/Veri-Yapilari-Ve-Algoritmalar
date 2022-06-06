# Insertion Sort Örneği 
[22,27,16,2,18,6] = Sayı Dizisi

Insertion Sort algoritmasında ilk olarak dizinin ikinci verisini anahtar veri olarak seçiyoruz ve ondan önceki sayılarla kıyaslıyoruz. Eğer küçükse yer değiştiriyoruz ve diğer sayıları sağa kaydırıyoruz. 

1.Adım = [22,27,16,2,18,6] 
(27 sayısı solundaki sayıdan daha büyük olduğu için yeri değişmeyecek çünkü küçükten büyüğe sıralıyoruz.)

2.Adım = [16,22,27,2,18,6]
(16 sayısı 22 ve 27'den daha küçük olduğu için diğer sayıları sağa kaydırarak yer değiştirdi.)
3.Adım = [2,16,22,27,18,6]
(2 sayısı solundaki tüm sayılardan daha küçük olduğu için en başa geçti ve diğer sayıları sağa kaydırdı.)

4.Adım = [2,16,18,22,27,6]
(16 sayısı solundaki sayılarla karşılaştırıldı ve araya sokuldu)

5.Adım = [2,6,16,18,22,27]
(6 sayısı solundaki tüm sayılarla karşılaştırıldı ve araya sokuldu.)

# Big-O 
O(n^2)

# Time Complexity

Worst Case = n²
Average Case = n²
Best Case = n 

En iyi durumda dizinin sıralı gelmesi veya istediğimiz bir sayıyı ilk denemede bulmamız best casedir ve time complexitysi n'dir.

# [7,3,5,8,2,9,4,15,6 ] dizisinin Insertion Sort'a göre adımları

1.Adım = [3,7,5,8,2,9,4,15,6]
2.Adım = [3,5,7,8,2,9,4,15,6]
3.Adım = [3,5,7,8,2,9,4,15,6]
4.Adım = [2,3,5,7,8,9,4,15,6]
5.Adım = [2,3,5,7,8,9,4,15,6]
6.Adım = [2,3,4,5,7,8,9,15,6]
7.Adım = [2,3,4,5,6,7,8,9,15]

