# Drupal course project

от Петър Любенов

Фак. №: 1709010883

## obshtatsi.net

Темата на курсовия проект е 
> Система за настаняване на студенти в общежитие. 

*(За правилното функциониране на сайта, виртуалния хост трябва да е с домейн obshtatsi.net)*

Сайтът представлява вътрешна система, предназначена за експлоатация от служителите на фирма, предоставяща общежития на студенти. Системата позволява задаване на блокове и входове и настаняване на студентите в стая в избран блок и вход.

Блок/вход са таксономия а student е content type, запазващ данните на студента (име, фамилия, факултетен номер, специалност, курс) и къде е настанен (блок/вход, стая)


## Webforms 

Системата предоставя възможност на студенти да изпращат кандидатури за общежитие като предоставят личните си данни. Служителите могат да виждат резултатите и да настанят студента в стая.

## Custom module

Страницата `/faq` е от custom module (`www/modules/custom/hello_world`). Представлява обикновена страница за често задавани въпроси. Маркъпа се генерира от масив с въпросите и отговорите

## Графична тема

Проекта използва темата [Bootstrap](https://www.drupal.org/project/bootstrap) с добавен custom css код за леки промени.
