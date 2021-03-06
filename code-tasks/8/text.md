## select

Если мы хотим добавить раскрывающийся список, то можно воспользоваться тегом `select`.
Внутри данного тега определяются варианты выбора с помощью тега `option`. 

Атрибут `value` в данном случае - это значение, которое будет доставлено на сервер при отправке.
Если `value` не задан, то берется текст внутри `option`.

```html
<form>
  <label for="city">Выберите свой город:</label>
  <select id="city" name="city">
    <option value="Moscow">Москва</option>
    <option value="Saint-Petersburg">Санкт-Петербург</option>
    <option value="Kaliningrad">Калининград</option>
    <option value="Omsk">Омск</option>
    <option value="Kazan">Казань</option>
  </select>
</form>
```

Результат:

<div class="html">
    <form>
      <label for="city">Выберите свой город:</label>
      <select id="city" name="city">
        <option value="Moscow">Москва</option>
        <option value="Saint-Petersburg">Санкт-Петербург</option>
        <option value="Kaliningrad">Калининград</option>
        <option value="Omsk">Омск</option>
        <option value="Kazan">Казань</option>
      </select>
    </form>
</div>

## Задание

Добавьте раскрывающийся список "Специализация", в котором будут следующие варианты:
- Machine Learning,
- Backend,
- Frontend,
- Big Data,
- GameDev.