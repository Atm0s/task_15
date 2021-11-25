# Task_7
Adaptive VC

DRY:
В секции .project__card убрал паддинг, который присутствовал в родительском элементе
-	padding-bottom: 30px;

В секции About me были и margin и padding. Убран паддинг.
+margin: 112px auto 110px;
-padding: 112px 0 110px;

Повторяющиеся свойства текстовых оберток в разных секциях вынесены в отдельный классы:
.text-wrapper{
	margin: 0 auto;
	max-width: 540px;
}

KISS:
В секции About_me были и margin и padding. Убран паддинг.
+margin: 112px auto 110px;
-padding: 112px 0 110px;

YAGNI:
Убран класс, за ненадобностью
.intro__desc {
	/* padding-left: 131px; */
}