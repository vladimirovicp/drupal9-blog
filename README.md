# drupal9-blog

## Модули
> * admin_toolbar

## Стандартные модули 
> * Configuration Translation
> * Content Translation
> * Interface Translation
> * Language
>
> * Media
> * Media Library

## Настройки
> *Удаление префикса Ru admin/config/regional/language/detection/url
> * Сдства обработки изображений 100%
> * Отключаем WWW в файле .htaccess
> Убрать комментарии
> ```
>  RewriteCond %{HTTP_HOST} ^www\.(.+)$ [NC]
>  RewriteRule ^ http%{ENV:protossl}://%1%{REQUEST_URI} [L,R=301]
> ```

## Тип материала
### News
> * 

