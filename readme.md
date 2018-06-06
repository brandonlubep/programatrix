# Platzom

Platzon es un idioma inventado para el [curso de fundamentos js](htts//platzi.com/js)
de [platzi](htts//platzi.com)

## Descripcion de idioma
-si la palabra termina en  'ar' se le quitan los caracteres
-si la palabra incia con Z, se le añade 'pe' al final
-si la palabra traducida tiene 10 o mas letras se debe
partr a la mitad y unirla por un '-'
-si la palabra original es palindroma se devuelve l misma palabra intercalando mayusculas

## Instalacion

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

console.log(platzom('programar'));
console.log(platzom('Zorro'));
console.log(platzom('Zarpar'));
console.log(platzom('abecedario'));
console.log(platzom('sometemos'));

```
