# ДЗ 1 BS

Парсер берет книги продающиеся на сайте https://echo-books.com/shop/

## Основной функционал: 

Код извлекает ссылку на книгу, цену (в евро), доступность, название, автора, и категории в которых книга находится на сайте. Чтобы взять максимум топ 2000 самых популярных книг из каждой категории у меня требуется где-то 10m45s, получается 8743 уникальных книг. Файл csv с этим результатом приложен как all_books.csv.

## Альтернативный функционал

Также есть вариант прогонять код без категорий. Это быстрее, и у меня занимает где-то 12 мин. чтобы сохранить информацию всех 24276 книг с сайта. Файл csv с этим результатом приложен как no_categories_all_books.csv.
