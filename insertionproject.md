# Insertion-Sort-Project

[22,27,16,2,18,6]-> Insertion Sort

Soru 1 - Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Soru 1 Cevapları :

a- Selection Sort :  	[22,27,16,2,18,6]-> n
				
				[2,27,16,22,18,6]-> n-1

				[2,6,16,22,18,27]-> n-2

				[2,6,16,18,22,27]-> 1

Big-O notation ---> n + (n-1) + (n-2) + 1 ---> (n.(n+1)) / 2 ---> (n^2 + n) / 2

			  Sonuç olarak Big-O Notation  --->  O(n^2).	
----------------------------------------------------------------------------------------------------------------

b- Merge Sort :		[22,27,16,2,18,6]

			[22,27,16]				[2,18,6]

			[22]	[27,16]			[2,18]	[6]
		
			[22]	[27]	[16]			[2]	[18]	[6]
		
			[22]	[16,27]			[2]	[6,18]

			[16,22,27]				[2,6,18]

					[2,6,16,18,22,27]

Big-O notation --->   O(nlogn).	

---------------------------------------------------------------------------------------------------------------

c- Quick Sort :		[22,27,16,2,18,6]---> 18 Pivot olarak belirlendi.

				[16,2,6]   		[18]			[22,27]

   <-----6 Pivot.	[2]	[6]	[16]		[18]		[22]		[27] ---> 22 Pivot.
---------------------------------------------------------------------------------------------------------------

Soru 2 - Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer ? Yazınız.

1 - Average case	: Aradığımız sayının ortada olması,
2 - Worst case	: Aradığımız sayının sonda olması,
3 - Best case	: Aradığımız sayının dizinin en başında olması.

Soru 2 Cevapları : Average Case kapsamında değerlendirilir.

		[2,6,16,18,22,27]

-----------------------------------------------------------------------------------------------------------------


Soru 3		 	[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Soru 3 Cevapları : 	[7,3,5,8,2,9,4,15,6]

				[2,3,5,8,7,9,4,15,6] ---> 1. Aşama

				[2,3,4,8,7,9,5,15,6] ---> 2. Aşama

				[2,3,4,5,7,9,8,15,6] ---> 3. Aşama

				[2,3,4,5,6,9,8,15,7] ---> 4. Aşama
