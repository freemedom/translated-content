---
title: NamedNodeMap
slug: Web/API/NamedNodeMap
translation_of: Web/API/NamedNodeMap
---
{{APIRef("DOM")}}

Интерфейс **`NamedNodeMap`** представляет собой коллекцию объектов {{domxref("Attr")}}. Объекты внутри `NamedNodeMap` не находятся в каком-либо определённом порядке, в отличие от {{domxref("NodeList")}}, хотя они могут быть доступны при использовании индекса, как в массиве.

Объект NamedNodeMap является "живым" и, таким образом, будет автоматически обновляться, если изменения будут внесены в его содержимое внутри или в другом месте.

> **Примечание:** Хотя данный интерфейс и называется `NamedNodeMap` , он не имеет ничего общего с объектом {{domxref("Node")}}, но до сих пор связан с объектом {{domxref(" Attr ")}}, который изначально был специализированным классом {{domxref("Node")}}.

## Свойства

Этот интерфейс не наследует никаких свойств.

- {{domxref("NamedNodeMap.length")}} {{ReadOnlyInline}}
  - : Возвращает количество объектов внутри объекта NamedNodeMap.

## Методы

Этот интерфейс не наследует никакого метода.

- {{domxref("NamedNodeMap.getNamedItem()")}}
  - : Возвращает значение {{domxref ("Attr")}}, соответствующее данному имени.
- {{domxref("NamedNodeMap.setNamedItem()")}}
  - : Заменяет или добавляет {{domxref ("Attr")}}, обозначенный в объекте NamedNodeMap заданным именем.
- {{domxref("NamedNodeMap.removeNamedItem()")}}
  - : Удаляет {{domxref ("Attr")}}, идентифицированный объектом NamedNodeMap .
- {{domxref("NamedNodeMap.item()")}}
  - : Возвращает значение {{domxref ("Attr")}} по заданному индексу или null, если индекс больше или равен числу узлов.
- {{domxref("NamedNodeMap.getNamedItemNS()")}}
  - : Возвращает {{domxref ("Attr")}}, идентифицированный пространством имён и связанным локальным именем.
- {{domxref("NamedNodeMap.setNamedItemNS()")}}
  - : Заменяет или добавляет {{domxref ("Attr")}}, идентифицированный в объекте NamedNodeMap данным пространством имён и связанным локальным именем.
- {{domxref("NamedNodeMap.removeNamedItemNS()")}}
  - : Удаляет {{domxref ("Attr")}}, идентифицированный данным пространством имён и связанным локальным именем.

## Specifications

| Specification                                                                                | Status                           | Comment                                                                |
| -------------------------------------------------------------------------------------------- | -------------------------------- | ---------------------------------------------------------------------- |
| {{SpecName('DOM WHATWG', '#interface-namednodemap', 'NamedNodeMap')}} | {{Spec2('DOM WHATWG')}} | Имеет дело с {{domxref("Attr")}} вместо {{domxref("Node")}}  |
| {{SpecName('DOM3 Core', 'core.html#ID-1780488922', 'NamedNodeMap')}} | {{Spec2('DOM3 Core')}}     | No change from {{SpecName('DOM2 Core')}}                        |
| {{SpecName('DOM2 Core', 'core.html#ID-1780488922', 'NamedNodeMap')}} | {{Spec2('DOM2 Core')}}     | Added `getNamedItemNS()`, `setNamedItemNS()` and `removeNamedItemNS()` |
| {{SpecName('DOM1', 'core.html#ID-1780488922', 'NamedNodeMap')}}         | {{Spec2('DOM1')}}         | Initial definition                                                     |

## Browser compatibility

{{Compat}}

## See also

- {{domxref("Element.attributes")}}
