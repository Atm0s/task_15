# Module_15
Ending task for module 15. Standards.

## DRY, KISS, YAGNI
### DRY:
* В секции .project__card убрал паддинг, который присутствовал в родительском элементе
-	padding-bottom: 30px;
* В секции About me были и margin и padding. Убран паддинг.
+margin: 112px auto 110px;
-padding: 112px 0 110px;
* Повторяющиеся свойства текстовых оберток в разных секциях вынесены в отдельный классы:
.text-wrapper{
	margin: 0 auto;
	max-width: 540px;
}
### KISS:
* В секции About_me были и margin и padding. * Убран паддинг.
+margin: 112px auto 110px;
-padding: 112px 0 110px;
### AGNI:
* Убран класс, за ненадобностью
.intro__desc {
	/* padding-left: 131px; */
}

## 2 W3C
* Код приведен в соответсвие для проверки валидатором validator.w3.org

## Pixel Perfect
* Добавлено.

## BEM 
В основе своей уже был в данном проекте.
* Отредактирована секция с формой
(.request-form)
* Без рабивки по файлам.

## Linters
* ESlint
* Auto Close Tag
* Auto Complete Tag
* Auto Rename Tag
* Better comments
* CSS Formatter
* Beautify