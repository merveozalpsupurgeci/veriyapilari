# veriyapilariProje 1 -  Insertion Sort


	      22        27	16	2	18	  6  

Öncelikle dizideki en küçük eleman seçilerek ilk eleman ile yer değiştirilerek başlanır

	      2        27	16	22	18	 6 

İlk sırada en küçük olan olduğundan listenin sıralanmamış kısmında işleme devam ediyoruz en küçük elemanını bulup ilk sıradaki ile yer değiştiriyoruz.

		2	 6 	16	 22     18	  27

Listenin sıralanmamış olan kısmından devam ederek en küçük elemanı bulduğumuzda ilk sırada olduğunu görüyoruz ve işlem yapmıyoruz

		 2	  6	16      22	 18	  27 

Listenin sıralanmamış olan kısmından devam ederek en küçük elemanı en başa alarak devam ediyoruz

		 2	  6	16	18        22      27 

Listenin sıralanmamış olan kısmından devam ederek en küçük elemanı bulduğumuzda ilk sırada olduğunu görüyoruz ve işlem yapmıyoruz ve sıralamayı bitiriyoruz

*İnsertion sort Big-O gösterimi O(n²) dir. 

 ## Time Complexity

	 2	   6	  16	  18	  22	  27 

Listenin sırlanmış son halinde aranana değer olan 18 ortada olduğundan average case kapsamına girer.

## Selection Sort

```
7	3	5	8	2	9	4	15	6
```


1. adım```             2	3	5	8	7	9	4	15	6 ```

1. adım ```            2	3       5	8	7	9	4	15	6 ```

1. adım ```            2	3	4       8	7	9	5	15	6 ```

1. adım ```            2	3	4	5	7       9	8	15	6 ```

