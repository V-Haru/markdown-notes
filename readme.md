# Guía de markdown
> Basada en la guía en github


## ENCABEZADOS
Para crear `encabezados` se utiliza el `#`.

# h1
## h2
### h3
#### h4
##### h5
###### h5

## Listas
Para crear `listas desordenadas` se utilizan los `*`, para añadir una sub lista se utilizan el `tab + *`.
* Item 1
* Item 2
    * Item 1
    * Item 2

Para crear `listas ordenadas` se utilizan los `#.`, para añadir una sub lista se utilizan el `tab + #.`, además de que se pueden combinar.
1. Item 1
2. Item 2
    1. Item 1
    * Item 2

## Links
Para usar links se utiliza `[NAME_PAGE](LINK)`
[GitHub](http://github.com)

## Imagenes
```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```

## Énfasis
italic `*text*`
*This text will be italic*

italic `_text_`
_This will also be italic_

bold `*text*`
**This text will be bold**

bold `__text__`
__This will also be bold__

también se pueden combinar entre ellas `*You **can** combine them*`

*You **can** combine them*

## Citas
Se utiliza el `>` seguido del texto
> Un gran poder conlleva una gran responsabilidad

## Código
Se utilizan ` ``` ` seguido del lenguaje y el código, seguido de las comillas  ` ``` `.
```javascript
function test() {
 console.log("text");
}
```

## Tablas
```
First Header | Second Header
------------ | -------------
Content cell 1 | Content cell 2
Content column 1 | Content column 2

```
