# MergeSort
Merge Sort for www.patika.dev

[16,21,11,8,12,22] Dizisinin Merge Sort'a göre sıralanması:

1-	  16	21	11	 |	 8	12	22	

2-  16	21	|	11	 | 	 8	|	12	22

3- 16	|	21	|	11	 |   8	|	12	|	22

Dizinin sıralanmış halini birleştirip yeniden yazıyoruz

4-16	21	|	11	 | 	8	|	12	22

5-	11	16	21	 | 	8	12	22	

6-    8	11	12	16	21	22	

6 adımda yapıldığından Big-O=O(6*(log6))
