# SeleniumFindLocator
Selenıum find Unique locator with Css Selector
1) İd ile --> htmltag#id ,#id ,
div#ornek = div[id='ornek'] ikiside aynı işleve sahiptir.
etiketi div,  id'si ornek olan elementleri bulmamızı sağlar.
a#ornek = a[id='ornek'] yine aynı şekilde etiketi "a" id'si "ornek” olan elementi bulmamızı sağlar.
  
 
-------------------------------------------------------------------------------------------------------------------------------------

2) class ile -->htmltag.ornek, a.örnek , .örnek 
div.ornek = div[class='örnek'] ikiside aynı işleve sahiptir.
etiketi div , class'ı  “örnek” olan elementleri bulmamızı sağlar.
.ornek burada ise class'ı  “örnek” olan bütün elementleri bulmamızı sağlar.
 
 
 -------------------------------------------------------------------------------------------------------------------------------------

3) input#username.form-control
bu örnekte ise etiketi  ‘input ‘ id'si  ‘username’ ve class'ı  ‘form-control’  olan elementi bulmamızı sağlar.
 

-------------------------------------------------------------------------------------------------------------------------------------
 
4) input[id='username'][type='email']
burada ise etiketi ‘input’, id'si 'username' ve type'ı 'email' olan elementleri bulmamızı sağlar.
 
-------------------------------------------------------------------------------------------------------------------------------------
 
5) input[id*=txt]
etiketi  ‘Input’ ve id'si içerisinde ‘txt’ kelimesi geçen bütün elementleri bulmamızı sağlar.
 
-------------------------------------------------------------------------------------------------------------------------------------
 
6) div[id^=my]
etiketi ‘div ‘  ve id'si ‘my ile başlayan elementleri bulmamızı sağlar.
 
-------------------------------------------------------------------------------------------------------------------------------------
 
7) input[id$='user']
etiketi ‘input’ ve id'si ‘Name’ ile biten elementleri bulmamızı sağlar.
 
-------------------------------------------------------------------------------------------------------------------------------------
 
8) ul.örnek>li:first-of-type
etiketi 'ul' class’ı ‘örnek’ olan elementin altında , etiketi 'li' olan ilk elementi bulmamızı sağlar.
 


------------------------------------------------------------------------------------------------------------------------------------- 
9) ul.örnek>li:last-of-type
etiketi 'ul' class’ı örnekolan elementin altında , etiketi 'li' olan son elementi bulmamızı sağlar.
 
-------------------------------------------------------------------------------------------------------------------------------------
 
10)ul.örnek>li:nth-of-type(4)
etiketi 'ul'  class'ı örnek olan elementin altında , etiketi 'li' olan 4. elementi bulmamızı sağlar.
 
------------------------------------------------------------------------------------------------------------------------------------- 
11) ul.örnek>:nth-child(3)
etiketi 'ul'  class’ı örnek olan elementin altında ,  4. elementi bulmamızı sağlar etiket belirtmemize gerek yoktur.
 
 
-------------------------------------------------------------------------------------------------------------------------------------
 
 
 

