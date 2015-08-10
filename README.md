# SocialNetworkServer

Сделать API для следующих запросов:

GET :

      /post - возвращает список всех записей
      
      /posts/:id - возвращает запись с заданным id (req.param.id)
      
      /user/:id/following - возвращает список фолоуэров указанного юзера
      
      /user/:id/folowers - возвращает список поклонников указанного юзера
      
      
DELETE:

      /posts/:id - удаляет запись с заданным id
      
      /user/:id/follow - отписаться от юзера с заданным id
      
      
PUT:

      /me - редактировать данные о себе
      
      /posts/:id редактировать запись (только для владельца записи)
      
      
POST:

      /user/:id/follow - подписаться на юзера с заданным id
      
