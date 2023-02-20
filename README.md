# Patika Projeler
## Selection Sort Projesi
### [22,27,16,2,18,6] -> Insertion Sort
~~~
Adım 1: [22, 27, 16, 2, 18, 6]
Adım 2: [22, 27, 16, 2, 18, 6] -> 27'yi doğru konumuna yerleştirin [22, 27, 16, 2, 18, 6]
Adım 3: [16, 22, 27, 2, 18, 6] -> 16'yı doğru konumuna yerleştirin [16, 22, 27, 2, 18, 6]
Adım 4: [2, 16, 22, 27, 18, 6] -> 2'yi doğru konumuna yerleştirin [2, 16, 22, 27, 18, 6]
Adım 5: [2, 16, 18, 22, 27, 6] -> 18'i doğru konumuna yerleştirin [2, 16, 18, 22, 27, 6]
Adım 6: [2, 6, 16, 18, 22, 27] -> 6'yı doğru konumuna yerleştirin [2, 6, 16, 18, 22, 27]

Güncellenen dizi: [2, 6, 16, 18, 22, 27]
~~~

#### Big-O Notation
O(n^2)

#### Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
Tam ortada, o yüzden average case.

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
~~~
Adım 1: [2, 3, 5, 8, 7, 9, 4, 15, 6] -> En küçük eleman olan 2'yi seçin ve ilk elemanla değiştirin.
Adım 2: [2, 3, 5, 8, 7, 9, 4, 15, 6] -> Sıralanmamış kısımdan en küçük elemanı yani 3'ü seçin ve ikinci eleman ile değiştirin.
Adım 3: [2, 3, 4, 8, 7, 9, 5, 15, 6] -> Sıralanmamış kısımdan en küçük eleman olan 4'ü seçin ve üçüncü elemanla değiştirin.
Adım 4: [2, 3, 4, 5, 7, 9, 8, 15, 6] -> Sıralanmamış kısımdan en küçük öğe olan 5'i seçin ve dördüncü öğeyle değiştirin.
~~~

## Merge Sort Projesi
### [16,21,11,8,12,22] -> Merge Sort
~~~
Verilen diziyi Merge Sort kullanarak sıralamak için şu adımları izleyeceğiz:

Adım 1: Diziyi, tek elemanlar elde edene kadar ikiye bölün.
[16,21,11] [8,12,22]

Adım 2: Bölünen her diziyi aynı adımları uygulayarak tekrarlı olarak sıralayın.
[16,21,11] -> [16] [21,11] -> [16] [11,21] -> [11,16,21]
[8,12,22] -> [8] [12,22] -> [12] [22] -> [8,12,22]

Adım 3: Sıralanan dizileri tekrar birleştirin.
[11,16,21] [8,12,22] -> [8,11,12,16,21,22]

Merge Sort kullanılarak sıralanan dizi [8,11,12,16,21,22] şeklindedir.
~~~
#### Big-O Notation
O(nlogn)

##Binary Search Tree Projesi
### [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
~~~
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
~~~
