ВНИМАНИЕ!!!

git добавляет -main в название папки и возникает ошибка при импорте:

from .pages.product_page import ProductPage
E   ImportError: attempted relative import with no known parent package

Нужно убрать тире из названия папки, после того, как скачаете мой проект. Можете заменить на нижнее подчёркивание или вообще удалите "-main" из названия папки!!! 

Почему-то....об этом не было сказано в курсе...

Просто убрать точку перед названием пакета при импорте проблему не решает... 
Я с этим столкнулся с чужими проектами и в моём та же история....