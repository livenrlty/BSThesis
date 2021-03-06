# Классификация временных рядов с помощью их признакового описания.

## Структура проекта

* `paper/` — текст работы.
* `code/lapprox/models` — исходный код моделей локальной аппроксимации.
    * На данный момент реализованы AR, ARMA, SEMOR, FFT и SSA.
* `code/lapprox/joint` — исходный код их ассамблеи (отображения в промежуточное
признаковое пространство).
* `code/lapprox/segments` — библиотека для работы с сегментами (приведение сегментов к одному размеру и вычесление "среднего" с помощью кубических сплайнов)
* `code/lapprox/segments` — дополнительные утилиты.
* `code/lapprox/thirdparty` — внешние зависимости.

## Примеры

* `code/Example.ipynb` — пример использования отображения для сегмента.
* `code/DataSandbox.ipynb` — обработка данных для использования в алгоритме обучения.
* `code/Learn.ipynb` — оптимизация совокупности моделей локальной аппроксимации.
