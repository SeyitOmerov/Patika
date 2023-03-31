# Patika
www.patika.dev
//patika.dev -> Insertion Sort Proje Ödevi

[22,27,16,2,18,6] 

//Insertion Sorting Aşamaları aşağıda sıralanmıştır.

    [22,27,16,2,18,6] // (n)
1-> [2,27,16,22,18,6] //Sıradan giderek en küçük sayı 2 ile en baştaki 22'yi yer değiştiriyor.
    
    [2,27,16,22,18,6] // (n-1)
2-> [2,6,16,22,18,27] //27'den başlayarak en küçük olan 6'yı buluyor ve yer değiştiriyor.

    [2,6,16,22,18,27] // (n-2)
3-> [2,6,16,22,18,27] //16'nın küçük olduğunu görerek aynen bırakıyor.

    [2,6,16,22,18,27] // (n-3)
4-> [2,6,16,18,22,27] //22'den itibaren arayarak 18'i buluyor ve yer değiştiriyor.

    [2,6,16,18,22,27] // (n-4)
5-> [2,6,16,18,22,27] //22'nin en küçük olduğunu görerek aynen bırakıyor.

    //Baştan dizi sırayla taranarak her aşamada bulunan en küçük sayı dizinin başındaki değerle yer değiştirilerek sıralam işlemi yapılıyor.

    //Yukarıdaki Big-O gösteriminden anlaşıldığı üzere diziyi sıralamak için dizideki eleman
    
    sayısı kadar işlem yapılabilir. Bu durumu 1'den n'e kadar olan sayıların toplamı olarak 
    
    formüle edebiliriz. Formül((1/2)*(n.(n+1))) Bu işlem Big-O Notation gösterimlerinden O(n^2) 
    
    olarak kabul edebiliriz.
   
    Soru :Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? 

    Cevap: Average case: Aradığımız sayının ortada olması kapsamına girer.

    ..
    ..

    Soru:
    [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

    Cevap:

    [7,3,5,8,2,9,4,15,6]
1-> [2,3,5,8,7,9,4,15,6]

    [2,3,5,8,7,9,4,15,6]
2-> [2,3,5,8,7,9,4,15,6]

    [2,3,5,8,7,9,4,15,6]
3-> [2,3,4,8,7,9,5,15,6]

    [2,3,4,8,7,9,5,15,6]
4-> [2,3,4,5,7,9,8,15,6]

    ..
    ..
