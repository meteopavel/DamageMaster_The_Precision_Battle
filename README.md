# 🎯 DamageMaster: The Precision Battle

Проект представляет собой текстовую RPG-игру, где ваша задача — рассчитать урон по противнику за 5 ходов так, чтобы он попал в диапазон ±10 от здоровья противника 🎯. Используйте три типа атак: лёгкую 💥, среднюю ⚔️ и тяжёлую 🚀, чтобы одержать победу!

---

## 📋 Основные возможности

- **Три типа атак** 💥⚔️🚀:
  - Лёгкая атака (`lite`): урон от 2 до 5 очков.
  - Средняя атака (`mid`): урон от 15 до 25 очков.
  - Тяжёлая атака (`hard`): урон от 30 до 40 очков.

- **Случайное здоровье противника** 🎲:
  - Здоровье противника генерируется случайным образом в диапазоне от 80 до 120 очков.

- **Режим повтора игры** 🔁:
  - После завершения раунда вы можете начать новую игру, введя `y`, или завершить игру, введя `n`.

- **Победа или поражение** 🏆😢:
  - Если ваш общий урон попадает в диапазон ±10 от здоровья противника, вы побеждаете! В противном случае — поражение.

---

## 🚀 Как начать играть

1. **Установите зависимости**  
   Убедитесь, что у вас установлен Python 3.x. Если в проекте есть зависимости, установите их:
   ```bash
   pip install -r requirements.txt
   ```
2. **Запустите игру**
    Выполните основной файл для запуска игры:
    ```bash
    python main.py
    ```
3. **Выбирайте атаки**
    На каждом из 5 ходов вводите тип атаки: lite, mid или hard. Например:
    ```plaintext
    Введи тип атаки: mid
    Количество очков твоей атаки: 20.
    ```
4. **Проверьте результат**
    После 5 ходов игра покажет, победили ли вы или проиграли:
    ```plaintext
    Тобой нанесён урон противнику равный 95.
    Очки здоровья противника до твоей атаки: 100.
    Ура! Победа за тобой!
    ```
5. **Играйте снова**
    Чтобы сыграть ещё раз, введите `y`. Для выхода из игры введите `n`.
