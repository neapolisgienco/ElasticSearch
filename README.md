# ElasticSearch
Полнотекстовый поиск в Symfony на примере ElasticSearch

## ветка main
- начальный вариант загрузки(Find goods v1) только хомяк без вариаций
- вариант загрузки с тильдой .'~2'); с двумя опечатками



## ветка total-with-filter-by-price-and-labor
Итоговый вариант c фильтром по цене и фильтром true false

## Дамп базы:
```
insert into public.good (id, name, price, description, is_active)
values  (8, 'Хомяк', 1000, 'Весел, пушист', true),
(3, 'Хомячок исправленный', 1000, 'Маленький, пушистый, цветной', true);
```

Автор: [Владислав Гиенко](mailto:neapolis@inbox.ru)# ElasticSearch

