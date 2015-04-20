A:
0000000000400624 T _Z7averagePdRd (average(double * n1, double & n2)


000000000040064c T _Z7averageif  (average(int n1, float n2))

B:
output:
1 8
4 8
4 8
8 8

第一行的數字表示各個type所佔用的記憶體空間，
char,int,float和double各佔1bytes,4bytes,4bytes,8bytes. 
因為指標裝的是記憶體位址，所以第二行的數字都顯示8，
(因為大小都會一樣，才能定位所有位址。)
顯示8是因為是64bit(8bytes)的電腦上運行,
若是在32bit的作業環境下執行，位址會是4。
