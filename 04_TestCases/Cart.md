| ID | Название | Preconditions | Steps | Expected Result | Actual Result |
|----|---------|--------------|------|----------------|---------------|
| C01 | Add product | Логин выполнен | Add to cart | Товар добавлен | Passed |
| C02 | Remove product | Товар в корзине | Delete | Удалён | Passed |
| C03 | Multiple items | Корзина пуста | Добавить 3 товара | Все добавлены | Passed |
| C04 | Refresh cart | Товар добавлен | Refresh | Корзина сохранена | Failed |
| C05 | Remove last | 1 товар | Delete | Корзина пуста | Passed |
| C06 | Back to catalog | Корзина | Back | Каталог открыт | Passed |
| C07 | Clear cart | Корзина | Удалить всё | Пусто | Passed |
| C08 | Duplicate items | Каталог | Add x3 | Кол-во растёт | Failed |
