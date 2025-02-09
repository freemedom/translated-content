---
title: XMLHttpRequest.upload
slug: Web/API/XMLHttpRequest/upload
translation_of: Web/API/XMLHttpRequest/upload
---
{{APIRef('XMLHttpRequest')}}

Свойство **XMLHttpRequest.upload** возвращает объект {{domxref("XMLHttpRequestUpload")}}, представляющий процесс загрузки. Это непрозрачный объект, но так как он является {{domxref("XMLHttpRequestEventTarget")}}, к нему можно добавить обработчики событий.

Обработчики событий, которые можно добавить к объекту загрузки:

| Обработчик    | Событие                                             |
| ------------- | --------------------------------------------------- |
| `onloadstart` | Начало запроса                                      |
| `onprogress`  | Происходит передача данных                          |
| `onabort`     | Запрос был отменён                                  |
| `onerror`     | При запросе произошла ошибка                        |
| `onload`      | Запрос завершился                                   |
| `ontimeout`   | Запрос не завершился ко времени, указанному автором |
| `onloadend`   | Запрос завершился (успешно или с ошибкой)           |

## Спецификации

{{Specifications}}

## Поддержка браузерами

{{Compat}}
