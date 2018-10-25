# Toggle Class On Click

Добавляет / убирает класс у элемента при нажатии на кнопку.

Работает без jQuery.

## Как пользоваться

### 1. Подключаем

1. Создаем папку **js**

2. Скачиваем файл **toggleClassOnClick.js**
    и помещаем его в папку **js**

3. В \<head\> добавляем код:

    ```html
    <script type="text/javascript" src="js/toggleClassOnClick.js"></script>
    ```

### 2. Настраиваем

1. В кнопку добавляем следующее

    ```html
    <div class="toggle-class"
         data-tag=".top-menu" 
         data-class="menu-visible"
         >Кнопка</div>
    ```

    Где:

    * **toggle-class:**
    	этот класс просто превращает кнопку в переключатель, который ставит / убирает класс с элемента.
    * **data-tag:** 
    	здесь ищем тег, у которого будем ставить / убирать класс, так же как в css (поэтому у классов ставим точку).
    * **data-class:**
    	какой класс ставить / убирать.

2. В элемент, у когорого меняем класс добавляем класс, который указали у кнопки в data-tag

    ```html
    <div class="top-menu">
        Слой, у которого будет меняться класс
    </div>
    ```



## Источник

https://gomakethings.com/how-to-add-transition-animations-to-vanilla-javascript-show-and-hide-methods/
