<script type="text/javascript">
var lastResFind=""; // последний удачный результат
var copy_page=""; // копия страницы в ихсодном виде
function TrimStr(s) {
     s = s.replace( /^\s+/g, '');
  return s.replace( /\s+$/g, '');
}
function FindOnPage(inputId) {//ищет текст на странице, в параметр передается ID поля для ввода
  var obj = window.document.getElementById(inputId);
  var textToFind;
  
  if (obj) {
    textToFind = TrimStr(obj.value);//обрезаем пробелы
  } else {
    alert("Введенная фраза не найдена");
    return;
  }
  if (textToFind == "") {
    alert("Вы ничего не ввели");
    return;
  }
   
  if(document.body.innerHTML.indexOf(textToFind)=="-1")
  alert("Ничего не найдено, проверьте правильность ввода!");
   
  if(copy_page.length>0)
        document.body.innerHTML=copy_page;
  else copy_page=document.body.innerHTML;
 
   
  document.body.innerHTML = document.body.innerHTML.replace(eval("/name="+lastResFind+"/gi")," ");//стираем предыдущие якори для скрола
  document.body.innerHTML = document.body.innerHTML.replace(eval("/"+textToFind+"/gi"),"<a name="+textToFind+" style='background:red'>"+textToFind+"</a>"); //Заменяем найденный текст ссылками с якорем;
  lastResFind=textToFind; // сохраняем фразу для поиска, чтобы в дальнейшем по ней стереть все ссылки
  window.location = '#'+textToFind;//перемещаем скрол к последнему найденному совпадению
 } 
</script>
`Статьи/Все`

# Перемещение по статьям
<input type="text" id="text-to-find" value="Поиск статьи" style="opacity: 0.5;"> 
<input type="button" onclick="javascript: FindOnPage('text-to-find'); return false;" value="Искать" style="opacity: 0.5;" />

​

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> 5 способ съесть своё говно</font>](https://pl0xo.github.io/5-sposobov-siest-svoiyo-govno1/)

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> Попа кака</font>](https://pl0xo.github.io/popa-kaka2/)

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> мемы скатились и вот почему</font>](https://pl0xo.github.io/msivp3/)

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> Крипер 2004 боженька. Но почему? Сейчас мы разберем это.</font>](https://pl0xo.github.io/unnamed3)

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> Фанфик о Иисус Хрестос#5905 и Айзек#2413</font>](https://pl0xo.github.io/fanfik5)

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> факты о том, что негры говно</font>](https://pl0xo.github.io/negrigovno6)

![http://www.777icons.com/libs/folder/16x16/lcd.gif](http://www.777icons.com/libs/folder/16x16/lcd.gif)[<font size="3"> топ 5 сливов анкхи</font>](https://youtu.be/dQw4w9WgXcQ)

Статьи: **7**

​
❓ [Как создать статью](https://pl0xo.github.io/add/)
