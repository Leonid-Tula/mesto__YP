# Проект 5: Место

### Обзор

* [Ссылка на проект](https://leonid-tula.github.io/mesto/)

Проект построен на базе макета:
**Figma**

* [Ссылка на макет в Figma](https://www.figma.com/file/bjyvbKKJN2naO0ucURl2Z0/JavaScript.-Sprint-5?node-id=0%3A1)

**Картинки**

Картинки для проекта взяты из Фигмы и оптимизированны с помощью Tinypng.

**V 0.1**

При работе над проектом использовались:
- Выравнивание элементов с помощью Flex
- Построение сетки элементов с помощью Grid
- Для удобства восприятия на различных устройствах добавлена адаптивность с помощью @media запросов
- Попап релизован с помощью фиксированного позиционирования и сокрытия его по умолчанию с помощью display: none
- Для вызова Попапа использован JS путём применения toggle к классу popup_opened у блока popup
- При заполнении полей формы, соответствующим образом перезаписываются поля в блоке profile и выводятся в консоль для одобства отслеживания работы скрипта 
- Файловая система организованна в соответствие с БЭМ Nested

**V 0.11**
- Исправлены ошибки валидатора

**V 0.12**
- Исправление ошибок в мобильной вёрстке, выявленных перед отправкой на ревью

**V 0.2**
- Исправлены замечания с пометкой "Надо исправить"
- Исправлена часть замечаний с пометкой "можно лучше"
- Изменена структура формы в index.html
- Убраны лишние события из скрипта
- начальные значения подставляются в поля ввода формы отдельной функцией
- Для стилизации полей формы использованмодификатор
- Ко всем неоходимым элементам добавлен тег <button>
- Для текстовых полей в profile добавлено сокрытие части текста, выходящего за рамки блока
- Подправлены частично @media запросы для удобства восприятия на различных устройствах
- Скрипт убран в отдельную папку
- Для страницы в целом задан min-width: 320px

**V 0.31**
- для блока page задан border-box, что исключило горизонтальный скролл на разрешениях 358px и менее
- заданы корректные размеры для иконки закрытия попапа
- устранены замечания ревьюера с пометкой надо исправить
- устранены большие смещения элементов в верстке
- реорганизована структура скрипта путём добавления новых функций и переменных

**V 0.4**
- Изменена структура отступов: блок header имееет ширину 100%, page не имеет отступов, у content и footer задан боковой отступ при размере экрана менее 768px
- исправлено имя класса формы
- устранена опечатка в стилях шрифта у кнопки submit в форие

**V 0.5**
- Добавлено два попапа, один для добавления картинок, второй для разворачивания выбранной картинки на весь экран
- реализовано плавное закрытие/ открытие попапов
- реализована с помощью js кнопка удаления карточек на странице
- реализована с помощью js кнопка лайков для каждой карточки
- начальные карточки мест добавляются с помощью js
- удалены старые картинки, которые не применяются в этой работе
- отдельно стлилизован placeholder у формы добавления картинок

**V 0.551**
- Приведение имён элементов в соответствие с БЭМ

**V 0.6**
- удален закомментированный участок кода из разметки
- обновлена шапка readme
- исправлена ошибка, приводившая поломке верстки карточки места при вводе некорректного адреса источника картинки
- исправлены критичные замечания ревьюера
- частично исправлены замечания с пометкой можно лучше
- переписано упраление функциями открытия/ закрытия попапов
- переменные переназначены через const

**V 0.61**

- исправлен вызов глобальных переменных внутри функций
- исправлена функция закрытия попапа по нажатию на крестик, теперь закрывается только активный попап