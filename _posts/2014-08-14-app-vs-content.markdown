---
layout: post
title: Вёрстка контента и вёрстка приложений
tag: человеческое
published: false
author: Маринин Тим
short: Маринин Тим о разнице в подходах и требованиях к фронтенду.
---

> &mdash; Тим, там ещё одна бага с подсчётом высот в дэйли<br> 
> &mdash; Аааааааргх!

Раньше в интернете существовали только контентные проекты — статьи, длинные тексты или ленты фотографий, и вся вёрстка сводилась к тому, чтобы грамотно представить содержимое. А затем появились веб-приложения и принесли с собой новые вызовы: необходимо представить весь необходимый контент в рамках одного экрана, ничего не должно сломаться, интерфейс может и, наверняка, будет меняться каждую неделю.

Сравним веб-приложения и контентные проекты:

<style>
td, th { padding: 0 1rem 1rem 0; }
th { text-align: left; }
</style>
| Контент | Приложения |
|---------|------------|
|Скролл — основной элемент интерфейса | Великое множество элементов управления |
|Главное — представить контент | Главное — функциональность |
|Мало JS, имеет смысл Progressive Enhancement | Много JS, можно не ориентироваться на людей без него|

Соответственно, к их вёрстке применимы разные требования: контент должен быть свёрстан для максимально удобного потребления (типографика), вёрстка приложения — быть максимально надёжной.

Страшно ли, если добавится ещё одна строка? В контенте — ни капли; а в ненадёжно свёрстанном приложении может возникнуть общий скролл или наложиться одно на другое (или ещё что похуже!)