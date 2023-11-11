#FSM - Доработка страницы Users

1. Таблица Users с владельцами участков (колонки Plot ID, First name, Last Name, Phone, Email, Last login)
2. Пагинация по 20 записей на страницу (аналогично таблице Plots)
3. Поиск по номеру телефона, имени и email пользователя
4. Страница реализована в схожем дизайне, как страница с Plots
5. Возможность создания/редактирования пользователя (поля First name, Last name, Phone, Email, Plots)
6. Через запятую в форме редактирования/создания User'a, можно перечислять несколько Plots
7. Валидация формы редактирования/создания User'a, не сохраняем результат если все input кроме Plots не заполнены
8. Фильтрации в редактировании/создании User, телефон фильтруется по неччисловым символам, email преобразуется в lowercase
9. Подсветка Users в меню при нахождении на странице Users
10. Возможность удаления пользователя