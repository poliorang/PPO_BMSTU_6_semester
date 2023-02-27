# PPO - Lab 01

## Мобильное приложение для проведения соревнований Российской Федерации Подводного Рыболовства

### Краткое описание идеи проекта  
Соревнования Российской Федерации Подводного Рыболовства проходят в 2 дня: каждый из участников команды (команда состоит из 2 или 3 человек) приносит на взвешивание подстреленню рыбу, судьи взвешивают ее, фиксируют вес и полученные очки за каждую единицу. По итогам первого дня необходимо иметь промежуточный командный и личный рейтинг, по итогам второго дня - финальный командный и личный рейтинг, самая крупная и самая мелкая рыба.

Необходимо реализовать БД, возможность наполнять ее данными и производить операции над ними посредством интерфейса мобильного приложения. Также требуется возможность для авторизации _участника_ соревнований, _судьи_ и _администратора_.  

### Краткое описание предметной области  
Предметная область - соревнования по подводной охоте: регистрация участников, добавление данных об улове, составление и сортировка рейтинга. 

### Актуальность и целесообразность  
С детства являюсь свидетелем описанного выше процесса (только очки считаются вручную и на калькуляторе, а рейтинг составляется на бумажке) - автоматизировать данную процедуру просто необходимо. Особенно будет содручно при большом количестве участников.

### Use-Case  

![UC](./lab01/UseCase.svg)


### Пользовательские сценарии  

`Участник` имеет возможность просматривать рейтинг, сортировать его, искать конкретного участника по имени и фамилии, просматривать профили участников.  

`Судья` имеет возможность зарегистрироваться/авторизоваться, создавать/редактировать/удалять профили участников, создавать/переформировывать/удалять команды из участников, добавлять/редактировать/удалять в улов участника рыбу (ее вес, очки), просматривать рейтинг, сортировать его, искать конкретного участника по имени и фамилии, просматривать профили участников.  

`Администратор` имеет возможность зарегистрироваться/авторизоваться, просматривать/удалять профили судей, создавать/редактировать/удалять профили участников, создавать/переформировывать/удалять команды из участников, добавлять/редактировать/удалять в улов участника рыбу (ее вес, очки), просматривать рейтинг, сортировать его, искать конкретного участника по имени и фамилии, просматривать профили участников.  
