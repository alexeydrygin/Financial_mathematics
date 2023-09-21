# Финансовая математика (семинары)

## Урок 1. Временная стоимость денег. Процентные расчеты

> Задача 1. Инвестор купил акцию 6 лет назад по цене $10. Сейчас он продал ее за $50. Определить, какую доходность принесла ему эта инвестиция в процентах годовых.

Для расчета доходности инвестиции необходимо использовать формулу для годовой доходности, которая выглядит следующим образом: 

$$ r = \left(\frac{FV}{PV}\right)^{\frac{1}{n}} - 1 $$

где $FV$ - будущая стоимость инвестиции, $PV$ - начальная стоимость инвестиции, $n$ - количество лет, в течение которых была сделана инвестиция.

Подставляя значения в формулу, получаем:

$$ r = \left(\frac{50}{10}\right)^{\frac{1}{6}} - 1 = 0.3155 $$

Таким образом, доходность инвестиции составила 31.55% годовых.

> Задача 2. Инвестору исполнилось только что 30 лет. Он хочет выйти на пенсию в 60 лет и жить на доход с капитала. Допустим, его целевой уровень капитала к пенсии составляет $350 000. Если он ожидает ставку доходности на рынке порядка 8% годовых, то какую сумму ему надо инвестировать каждый год для достижения цели?

Для определения необходимой суммы инвестиций каждый год для достижения цели в $350 000 к пенсии, можно воспользоваться формулой для расчета аннуитетных платежей:

$$ PMT = \frac{FV \cdot r}{((1 + r)^n - 1) / r} $$

где $PMT$ - необходимая сумма инвестиций каждый год, $FV$ - будущая стоимость инвестиции, $r$ - годовая процентная ставка, $n$ - количество лет.

Подставляя значения в формулу, получаем:

$$ PMT = \frac{350,000 \cdot 0.08}{((1 + 0.08)^{60-30} - 1) / 0.08} = 3,441.73 $$

Таким образом, инвестору необходимо инвестировать $3,441.73 каждый год, чтобы достичь цели в $350,000 к пенсии, при условии годовой процентной ставки на рынке в 8%. Однако, стоит отметить, что для более точного расчета необходимо учитывать индивидуальные факторы, такие как инфляция, налоги и т.д.

> Задача 3. Человек взял ипотечный кредит на сумму 8 млн руб., на 20 лет под 10% годовых. Погашение кредита будет происходить ежемесячными аннуитетными платежами. Определить, сколько составит общая переплата (сумма процентов) по кредиту.


Для расчета общей переплаты по кредиту необходимо воспользоваться формулой:

$$
I = nP - A
$$

где $I$ - общая переплата, $n$ - количество платежей, $P$ - размер ежемесячного платежа, $A$ - сумма кредита.

Для расчета размера ежемесячного платежа можно воспользоваться формулой для аннуитетных платежей:

$$
P = \frac{A \cdot r \cdot (1 + r)^n}{(1 + r)^n - 1}
$$

где $r$ - месячная процентная ставка, $n$ - общее количество платежей.

Переведем годовую процентную ставку в месячную:

$$
r = \frac{10\%}{12} = 0.008333
$$

Общее количество платежей равно:

$$
n = 20 \cdot 12 = 240
$$

Сумма кредита равна 8 млн рублей. Подставляя значения в формулу для ежемесячного платежа, получаем:

$$
P = \frac{8,000,000 \cdot 0.008333 \cdot (1 + 0.008333)^{240}}{(1 + 0.008333)^{240} - 1} \approx 67,592
$$

Теперь можно подставить значения в формулу для общей переплаты:

$$
I = 240 \cdot 67,592 - 8,000,000 \approx 9,022,080
$$

Таким образом, общая переплата по кредиту составит около 9,022,080 рублей.

> Задача 4. Известно, что безрисковая ставка на рынке составляет 1%, инфляция ожидается 6% годовых и для данного проекта премия за риск равна 4%. Пусть ставка дисконтирования определяется как сумма этих трех составляющих, тогда чему равна приведенная стоимость потоков по проекту, если в первый год ожидается $2000, во второй $5000 и в третьем году проект будет продан за $10000?

Для расчета приведенной стоимости потоков по проекту необходимо воспользоваться формулой:

$$
PV = \frac{CF_1}{(1 + r)^1} + \frac{CF_2}{(1 + r)^2} + \frac{CF_3}{(1 + r)^3}
$$

где $PV$ - приведенная стоимость, $CF_i$ - денежный поток в i-ый год, $r$ - ставка дисконтирования.

Ставка дисконтирования в данном случае определяется как сумма безрисковой ставки (1%), ожидаемой инфляции (6%) и премии за риск (4%), то есть:

$$
r = 1\% + 6\% + 4\% = 11\%
$$

Подставляя значения в формулу, получаем:

$$
PV = \frac{2000}{(1 + 0.11)^1} + \frac{5000}{(1 + 0.11)^2} + \frac{10000}{(1 + 0.11)^3} \approx 12,427
$$

Таким образом, приведенная стоимость потоков по проекту составляет около 12,427 долларов.

> Задача 5. Что выгодней: положить деньги на депозит под 11% годовых с ежемесячной капитализацией или на депозит под 11,5% с ежегодной капитализацией процентов?

Для определения того, что выгоднее - положить деньги на депозит под 11% годовых с ежемесячной капитализацией или на депозит под 11,5% с ежегодной капитализацией процентов, необходимо рассчитать, какой вариант принесет больший доход.

Для расчета дохода по депозиту с ежемесячной капитализацией процентов можно воспользоваться формулой:

$$
S = P \cdot \left(1 + \frac{r}{12}\right)^{12n}
$$

где $S$ - итоговая сумма, $P$ - начальный вклад, $r$ - годовая процентная ставка, $n$ - количество лет.

Для расчета дохода по депозиту с ежегодной капитализацией процентов можно воспользоваться формулой:

$$
S = P \cdot \left(1 + r\right)^{n}
$$

где $S$ - итоговая сумма, $P$ - начальный вклад, $r$ - годовая процентная ставка, $n$ - количество лет.

Предположим, что начальный вклад составляет 100 000 рублей, и срок вклада равен 1 год. Тогда для депозита с ежемесячной капитализацией процентов годовая процентная ставка составляет 11% / 12 = 0,9167% в месяц, а для депозита с ежегодной капитализацией процентов годовая процентная ставка составляет 11,5%.

Для депозита с ежемесячной капитализацией процентов:

$$
S = 100000 \cdot \left(1 + \frac{0.9167\%}{12}\right)^{12} \approx 111,690.34
$$

Для депозита с ежегодной капитализацией процентов:

$$
S = 100000 \cdot \left(1 + 11.5\%\right)^{1} \approx 111,500
$$

Таким образом, депозит с ежемесячной капитализацией процентов принесет больший доход, чем депозит с ежегодной капитализацией процентов. 
