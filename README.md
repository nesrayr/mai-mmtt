Яруллин А.Р. М8О-401Б-21

Для классификации был выбрал датасет '[Mushroom Dataset](https://www.kaggle.com/datasets/prishasawhney/mushroom-dataset)' \
Задачей было классифицировать съедобные и несъедобные грибы  \
Для регрессии был выбран датасет '[Gold Price Regression](https://www.kaggle.com/datasets/franciscogcc/financial-data)'\
Задачей было предсказывать стоимость золота.

Метрика оценки качества регрессии: **R^2**;  
Метрика оценки качества классификации: **accuracy**;

*Метрики качества на тестовом наборе данных*
<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация</td>
        <td>0.9896363468122513</td>
        <td>0.9896363468122513</td>
        <td>0.7</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.6117887832623803</td>
        <td>0.997380569432721</td>
        <td>0.997324191148895</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация</td>
        <td>0.6365318774868141</td>
        <td>0.6507160909856782</td>
        <td>0.6487784330244314</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.9999210644865327</td>
        <td>0.9998470525181408</td>
        <td>0.9998311791591324</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация</td>
        <td>0.9786249653002683</td>
        <td>0.9786249653002683</td>
        <td>0.9787174979180161</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.9991181684775854</td>
        <td>0.9990319565470311</td>
        <td>0.9990827271856912</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация</td>
        <td>0.99093180346071999</td>
        <td>0.9915795317849542</td>
        <td>0.753770704173221</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.9996197129403056</td>
        <td>0.9993361905393987</td>
        <td>0.9970418789959087</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация</td>
        <td>0.8847968909040437</td>
        <td>0.9900990099009901</td>
        <td>0.9938366718027735</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.9994916496607711</td>
        <td>0.9996386504405321</td>
        <td>0.9995858782762815</td>
    </tr>
</table>


<br><br>
Таким образом, на выбранном датасете лучшей моделью для задач классификации оказалась модель **градиентного бустинга**(самостоятельная имплементация, после применения гипотез), а для задач регрессии **линейная модель**(библиотечная реализация)
<br>
