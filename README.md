# Task. XML\XSD & Parsing

Cоздать xml-файл, хранящий информацию об объектах определенной предметной области. Для валидации полученного xml-файла необходимо разработать соответствующую ему схему xsd. Выполнить парсинг xml- документа с использованием DOM, SAX, StAX парсеров.

# Требования
- использовать для атрибутов required & optional
- перечисления
- шаблоны и предельные значения
- использовать тип ID
- задание значений атрибутов по умолчанию
- расширение типов (имитация наследования)
- создать в xml-документе не менее 16 сущностей
- для записи логов использовать Log4J2
- код должен быть покрыт тестами

# Задание. Алмазный фонд
## Драгоценные и полудрагоценные камни:
Name – название камня.
Preciousness – может быть драгоценным либо полудрагоценным.
Origin – место добывания.
Visual parameters (должно быть несколько) – могут быть: цвет (зеленый, красный, желтый и т.д.), прозрачность (измеряется в процентах 0-100%), способы огранки (количество граней 4-15).
Value – вес камня (измеряется в каратах).
Корневой элемент назвать Gems.
