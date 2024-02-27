## DOM

```
DOM - bu brauzerga yuklanadigan veb-sahifaning daraxtga o'xshash ko'rinishi.
U bir qator obyektlardan foydalangan holda veb-sahifani tashkil qiladi. Asosiy obyekt bu document obyekti bo'lib, u ichida boshqa o'z obyektlari ega bo'lgan obyektlarni o'z ichiga oladi.
```

![](./images/DOM.png)

<hr>

### Selectors :

- getElementById ;
- getElemenetByTagName ;
- getElementByClassName ;
- getElementByName ;
- querySelector ;
- querySelectorAll ;

<br>

```
getElementById - Elementlarni id orqali chaqirish uchun ishlatiladi.
Misol uchun : document.getElementById(#id)
```
<br>

```
getElementByTagName - Elementlarni HTML teglari orqali chaqirish uchun ishlatiladi.
Misol uchun : document.getElementByTagName('HTMLtag(div, h1, p ...)')
```
<br>

```
getElementByClassName - Elementlarni class name lari orqali chaqirish uchun ishlatiladi.
Misol uchun : document.getElementByClassName('.className')
```
<br>

```
getElementByNmae - Elementlarni "name" atributi orqali chaqirish uchun ishlatiladi.
Misol uchun : getElementByName('name')
```
<br>

```
querySelector - Bu selector universal selector hisoblanadi. Elementlarni "#id" "TagName" "ClasName" "Name" lari orqali chaqirish uchun ishlatiladi.
Misol uchun : querySelector(#id, .ClassName TagName Name ...)
```
<br>

```
querySelectorAll - Bu selector esa elementlarni kop takrorlanuvchi elementlarni faqatgina ".ClassName" va "TagName" orqali chaqirish uchun iwlatiladi. 
Misol uchun : querySelectorAll(.ClassName , TagName)
```
<br>
<hr>
<br>

### Atributes :

- getAttribute(name) ;
- setAttribute(name , value) ;
- hasAttribute(name) / bolean ;

<br>

```
getAtribute - Elementlarni "value" ya'ni qiymatini olish chaqirib berish uchun ishlatiladi.
Misol uchun : element.getAtribute("value")
```
<br>

```
setAtribute - esa elementlarni "name" orqali chaqirib olib "value" sini tayinlash uchun ishlatiladi. 
Misol uchun : 
element.setAtribute("name" , "value")
```
<br>

```
hasAtribute - esa elementlarni ichida keltirilgan "value" bor yoki yo'qligini aniqlab beradi va bizga boolean qaytaradi yani (true) yoki (folse) qiymat qaytaradi 
Misol uchun : element.hasAtribute("value") javobi esa agar o'sha "value" bo'lsa (true) mavjuda bo'lmasa esa (folse) qiymat qaytaradi...
```
<br>

<hr>

### ClassList :

```
ClassList - Bron bir HTML elementiga ("className") tayinlash uchun yoki mavjud ("className") ni uchirib yuborish uchun ishlatiladi va buning bir nechta methodlari mavjud...
```

#### Methods ClassList :

```
1. .add - ("ClassName") qo'shish uchun ishlatiladi
Misol uchun : div.ClassList.add("className") bu chaqirilgan div uchun "ClassName" qo'shib beradi
```

```
2. .remove - ("ClassName") o'chirib tashlash uchun ishlatiladi
Misol uchun : div.ClassList.remove("className") bu chaqirilgan divdagi aytilgan "ClassName" ni o'chirib beradi
```

```
3. .contains - ushbu kiritilgan ("ClassName") borligi yoki yo'qligini aniqlab beradi va bu bizga "boolean" ya'ni (true) yoki (folse) qiymat qaytaradi
Misol uchun : div.ClassList.contains("className") bu chaqirilgan divda o'sha "ClassName" bor yoki yo'qligini aniqlab beradi
```

```
4. .toggle - bu bizga usha ("ClassName") mavjud bo'lsa o'chirib beradi aks holda qo'shib beradi
Misol uchun : div.ClassList.toggle("className") ("")
```

### Dynamically DOM Manupulation:
 
- createElement('TagName')
- appendChild / append (element)
- prepentChild / prepend (element)
- maping

### DOM Event

#### on mouse :

- on / addEventListener
- click 
- dbClick
- mouseLeave
- mouseOver
- mouseMove

#### on keyboard :

- keyDown
- keyUp
- keyPress

#### Browser / Window Events :

- DOMContentLoaded
- Loaded
- Scroll
- Resize

#### Mapping Events :

- ForEach
- Map
- Filter
- Readuce


### JSON
```
 JSON - JavaScript Object Notation - so'zining qisqartmasi...
```








