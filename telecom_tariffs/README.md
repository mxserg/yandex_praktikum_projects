# Определение выгодного тарифа для телеком компании

## Задача
На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа

## Используемые библиотеки
`Pandas`, `NumPy`, `SciPy`, `Matplotlib`, `Seaborn`, `Plotly`

## Основные выводы
- Активность пользователей тарифных планах отличается друг от друга, как показал анализ распределений средних значений и вариативности предоставляемых услуг;
- Пользователи тарифа "Ультра" ведут траты хаотично, четкой тенденции по месяцам не прослеживается. Тем не менее, в среднем большиснтво клиентов укладываются в абонентскую планту - менее четверти клиентов доплачивают за превышение лимитов.
- Чаще всего пользователи превышали лимиты по интернет-трафику. Имеено этим обусловлен больший процент выручки у пользователей тарифа "Смарт". К тому же, именно у абонента этого тарифного плана отмечена максимальная выручка в выборке.
- Таким образом, для оператора будет выгоднее тариф "Смарт" с сохранением текущих лимитов по абонентской плате.