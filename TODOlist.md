# TODO
### Minimal:
- [ ] Клас ValueToken (відповідає просто числу, вміє лише повератти своє значення)
- [ ] Клас OperatorToken (відповідає операції, вміє повертати пріоритет операції і обчислювати дію на основі двох аргументів)
- [ ] Отримати вираз з CLI і правильно розділити його на список токенів операторів і значень
- [ ] Написату структуру стеку
- [ ] Отримати RPN через shunting-yard алгоритм
- [ ] Обчислити RPN
### Hard: 
- [ ] Добавити підтримку в OperatorToken операції з правою асоціативністю ^ (піднесення до степеня)
- [ ] Добавити підтримку дужок
- [ ] Добавити підтримку в OperatorToken унарної операції - (від'ємні числа)