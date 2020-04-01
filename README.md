# Risk-Project
Group Risk Project by Alekseeva Stepanida, Garifullina Azalia, Shchukina Aleksandra

29/02/2020 - Welcome!

-----------------

## (Marat) Final Assessment


### Market Risk

1. Stocks foreign. Неверно определены критические значения для бэктеста. p=1% для VaR 1%, а у вас 5%. Получается Вы сравниваете количество пробоев 1% VaR с критическими значениями для 5% VaR. Это сделано для всех проведенных бэктестов. Поэтому из них следует, что риски переоценены, хотя это не так. (4 балла)

2. Stock domestic. На один день нет валютного риска, а на 10 дневного горизонта валютный риск существует только 9 дней, VaRы расчитаны неверно. Хотя ход мыслей хороший. Нет бэктеста. (1 балла за подход в целом)

2. Bonds. Абсурдный результат - ES по модулю меньше VaR. (3 балл, за бэктест и VaR).

Итог по рыночным рискам: 8 балла.

### Credit Risk

1. CAP(ROC). AR неверно с ошибкой для СAP, поэтому AR для CAP и ROC оказываются разными. По вашему выходит, что ROC и CAP показывают разное качество модели, что абсурдно. Мотивировка вывода о рейтинговой философии некорректна, т.к. динамические свойства PD приведены неверно. (0 балл)

2. PDs. Все ок. 2 балла.

3. Критерии качества. Доверительные интервалы рассчитаны неверно, весь множитель при квантили должен быть под корнем. В LR тесте неверное число степеней свободы. 1 балл.

4. Матрицы. В когортном методе не вычислена матрица по статистике переходов за пять лет. Остальное ок. 3 балла.

5. Портфель. На всех листах должен быть один и тот же набор общеэкономических сценариев y, при агрегации будут складываться убытки в категориях из разных сценариев, что неразумно. Абсурдный результат - отрицательные UL, т.е. VaR меньше ожидаемых убытков. 1 балл.

Итог по кредитным рискам: 7 баллов.

**Итог за курс:  0.5\*8+0.5\*7 = 7.5=> 8**.

**Спасибо за работу! Успехов!**