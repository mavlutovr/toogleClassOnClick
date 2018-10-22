# Toggle Class On Click

Добавляет / убирает класс у элемента при нажатии на кнопку.

## Как пользоваться

### Подключаем

1. В \<head\> добавляем код:

    ```html
    <script type="text/javascript" src="https://raw.githubusercontent.com/mavlutovr/toogleClassOnClick/master/toggleClassOnClick.js"></script>
    ```

2. В кнопку добавляем следующее

    ```html
    <div class="toggle-class"
         data-target=".top-menu" 
         data-class="menu-visible"
         >Кнопка</div>
    ```

    Где:

    * **toggle-class:** класс, который подключает кнопку к элементу.
    * **data-target:** 
    	здесь ищем элемент, у которого будем ставить / убирать класс, так же как в css (поэтому у классов ставим точку).
    * **data-class:**
    	какой класс ставить / убирать.

3. В элемент, у когорого меняем класс добавляем класс, который указали у кнопки в data-target

    ```html
    <div class="top-menu">
        Слой, у которого будет меняться класс
    </div>
    ```



## Источник

https://gomakethings.com/how-to-add-transition-animations-to-vanilla-javascript-show-and-hide-methods/
