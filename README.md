# Saratov-Streets-JSON
Улицы Саратова в JSON формате, разделенные по районам.
Данные взяты с сайта http://saratov.ginfo.ru/ulicy/ 10.04.2022

Скрипт для парсинга:
```javascript
const streets = [] 
document.querySelectorAll('.street_unit').forEach(unit => { streets.push(unit.querySelector('a').innerHTML) })
streets
```
