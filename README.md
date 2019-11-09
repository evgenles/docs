﻿# Стиль библиографии по ГОСТ Р 7.0.5-2008

Данный стиль соответствует стандарту ГОСТ Р 7.0.5-2008 и может использоваться в Microsoft Office Word для автоматической генерации библиографической ссылки (списка литературы). Стандарт ГОСТ Р 7.0.5-2008 распространяется на библиографические ссылки, используемые в опубликованных и неопубликованных документах на любых носителях. Стандарт предназначен для авторов, редакторов, издателей.

Ознакомиться со стандартом можно по ссылке: [Библиографическая ссылка на wikisource.org](http://ru.wikisource.org/wiki/ГОСТ_Р_7.0.5—2008).

## Поддержка

На текущий момент поддерживаются Office 2010, 2013 и 2016.

Использовать стиль в Office 2007 не получится, так как он содержит ошибку, а точнее, не по стандарту указывает языки источников при формировании библиографии. В результате стиль не может определить, на русском или английском языке написан источник.

## Как пользоваться 

Файл стиля (*.xsl) следует поместить в директорию стилей библиографических ссылок:

* Для Office 2010:       [System Volume]:\Program Files\Microsoft Office\Office 14\Bibliography\Style
* Для Office 2013/2016:  [System Volume]:\Users\\[User Name]\AppData\Roaming\Microsoft\Bibliography\Style

В меню «Ссылки» выбрать стиль «ГОСТ Р 7.0.5-2008 (сортировка по именам)» и работать с источниками. При создании источника следует обязательно указывать язык, иначе по умолчанию им будет английский.

Чтобы пользоваться стилем с сортировкой по именам авторов, нужно обработать документ (*.docx) специальной программой — BibWord Extender. Подробности на [странице](http://det-random.livejournal.com/28819.html) или у  [создателей BibWord по-английски](http://bibword.codeplex.com/wikipage?title=BibWord%20Extender&referringTitle=FAQ).

## Известные затруднения пользователей

Бывает, что в списке литературы не видно номеров столбцов: вместо них могут быть точки или просто пустота. Это происходит, когда стиль абзаца (не путать со стилем библиографии) имеет ненулевой отступ, и число просто "уезжает" вправо, где его не видно. Чтобы исправить положение, достаточно изменить стиль или просто выделить первый столбец (список литературы -- это таблица) и выставить в нем нулевой отступ (первый способ является предпочтительным).

## Дальнейшее развитие

Следует отметить, что средства Office Open XML не позволяют реализовать все возможные варианты затекстовых ссылок и библиографических ссылок, предусмотренные ГОСТом, но для большинства применений их достаточно. 

Введение новых возможностей, исправление ошибок и неточностей и сообщение ссылок на альтернативные методы работы с библиографиями в документах приветствуется.
