# Proje3


[patika.dev](https://app.patika.dev/sahinistambul)


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


1. İlk olarak [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] listesinden bir pivot seçilir. Daha sonra bu pivot en başa yazıldıktan sonra sırayla her sayı belli bir kurala göre yerleştirilir.

Diyelimki pivotumuzu 7 olarak aldık. 7 den sonraki her sayı 7' ye birleşik bir şekilde (yani boğum olarak) bağlanacaktır.
1. Eğer bir sonraki sayı 7 den büyük ise 7' nin sağına bağlanır.
2. Eğer bir sonraki sayı 7 den küçük ise 7' nin soluna bağlanır.

şema proje3.png olarak atılmıştır.


Eğer iyi dağılmışsa her seferinde n/2 karşılaşma yaptığından Time Complexity O(log(n)) adımda olur.
Eğer kötü dağılmışsa her seferinde n/2 karşılaşma yapamadığından Time Complexity O(n.log(n)) adımda olur.

