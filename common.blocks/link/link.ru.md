# link

Блок `link` доопределен на уровне библиотеки.

## Ипользование блока с кастомным контентом

```bemjson
{
    block : 'link',
    content : 'тут что угодно'
}
```

## Ипользование блока по умолчанию

### Мода `text` добавляет обертку в виде элемента блока `text` текстом для декoративного использования

```bemjson
{
    block : 'link',
    text : 'текст ссылки'
}
```

### Мода `icon` добавляет обертку в виде элемента блока `icon` над иконкой для декoративного использования

```bemjson
{
    block : 'link',
    icon: { block: 'icon' },
    text : 'текст ссылки'
}
```