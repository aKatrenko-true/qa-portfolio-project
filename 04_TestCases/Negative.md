| ID | Scenario | Preconditions | Steps | Expected Result | Actual Result |
|----|---------|--------------|------|----------------|---------------|
| N01 | Empty checkout | Корзина | Пустые поля | Ошибка | Failed |
| N02 | Remove ghost item | Корзина | Delete | Без падения | Passed |
| N03 | Long strings | Checkout | 300 символов | Ошибка | Passed |
| N04 | Special chars | Checkout | @#$ | Ошибка | Passed |
| N05 | Checkout without cart | Корзина пуста | Purchase | Ошибка | Failed |
