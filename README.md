# Proje3


[patika.dev](https://app.patika.dev/sahinistambul)


[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


1. İlk olarak [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] listesinden bir pivot seçilir. Daha sonra bu pivot en başa yazıldıktan sonra sırayla her sayı belli bir kurala göre yerleştirilir.

Diyelimki pivotumuzu 7 olarak aldık. 7 den sonraki her sayı 7' ye birleşik bir şekilde (yani boğum olarak) bağlanacaktır.
1. 7' nin sağındakiler [8,9] ve  7' nin solundakiler [0,1,2,3,4,5,6]
2. 5'in sağındakiler [6] ve 5'in solundakiler  [0,1]
3. 1'in sağındakiler [3,4] ve 1'in solundakiler [0]
4. 3' ün sağındakiler [4] ve 3' ün solundakiler [2]

şema proje3.png olarak atılmıştır.


Eğer iyi dağılmışsa her seferinde n/2 karşılaşma yaptığından Time Complexity O(log(n)) adımda olur.
Eğer kötü dağılmışsa her seferinde n/2 karşılaşma yapamadığından Time Complexity O(n.log(n)) adımda olur.

