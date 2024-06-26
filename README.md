# A-B-teasting-dating-app

Механика приложения следующая: пользователи видят в приложении анкеты друг друга и могут ставить друг другу лайки или дизлайки. Если пользователи поставили друг другу лайк – это называется мэтч, и у пользователей появляется возможность познакомиться.

Команда приложения разработала новый алгоритм для поиска наиболее подходящих анкет. Для проверки работы алгоритма был проведен АБ-тест. Все пользователи были разделены на две группы. Пользователи в группе с номером 0 пользовались приложением со старым алгоритмом. Все пользователи в группе 1 пользовались приложением с новым алгоритмом для поиска анкет.

# Задача:
Оценить, правда ли, что новый алгоритм улучшил качество сервиса.

**Стек:** Python и библиотеки(pandas, seaborn, numpy, scipy.stats, requests, json, pingouin), API + немного статистики и продуктовых метрик.

# Цель: 
Определение более эффективного алгоритма приложения при помощи анализа данных АВ-тестирования.
# 
- Произведена предобработка данных
- Подсчитана конверсия в мэтч каждой из групп.
Используя критерий хи-квадрат, статистически доказано: новый алгоритм работает лучше.
- Проанализирована активность пользователей: с новым алгоритмом пользователи стали активнее.
Проведенный t-тест статистически доказывает верность утверждения.

# Результат: 
С помощью подсчета метрик(конверсия в мэтч, активность пользователей) и статистических тестов доказано, что новый алгоритм эффективнее старого.
