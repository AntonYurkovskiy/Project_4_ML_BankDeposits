![](/11440.jpg)

# Дата-сайенc проект в сфере финтех по выявлению наиболее лояльных клиентов банка

В нашем распоряжении данные о последней маркетинговой кампании, которую проводил банк: задачей было привлечь клиентов для открытия депозита. Задача специалиста Дата-сайенc проанализировать эти данные, выявить закономерность и найти решающие факторы, повлиявшие на то, что клиент вложил деньги именно в этот банк. Выполнение этой задачи поспособствует увеличению доходов банка и поможет понять целевую аудиторию, которую необходимо привлекать путём рекламы и различных предложений.

**Бизнес-задача:**<br> Определить характеристики, по которым можно выявить клиентов, более склонных к открытию депозита в банке, и за счёт этого повысить результативность маркетинговой кампании.

**Техническая задача для специалиста Data Science:** <br>Построить модель машинного обучения, которая на основе предложенных характеристик клиента будет предсказывать, воспользуется он предложением об открытии депозита или нет.

## Основные цели:

* Произвести исследование данных, создать визуализации, вычислить метрики;<br>
* Выявить характерные черты для потенциальных клиентов, чтобы чётко очертить ЦА и увеличить прибыль банка.
* Использовать разные инструменты для повышения качества прогноза.

## Описание данных:

Первоначальная версия датасета содержит **17 полей** со следующей информацией:

**Данные о клиентах банка:**

**`age`** - возраст;<br>
**`job`** - сфера занятости;<br>
**`marital`** - семейное положение;<br>
**`education`** - уровень образования;<br>
**`default`** - имеется ли просроченный кредит;<br>
**`housing`** - имеется ли кредит на жильё;<br>
**`loan`** - имеется ли кредит на личные нужды;<br>
**`balance`** - баланс.

**Данные, связанные с последним контактом в контексте текущей маркетинговой кампании:**

**`contact`** - тип контакта с клиентом;<br>
**`month`** - месяц, в котором был последний контакт;<br>
**`day`** - день, в который был последний контакт;<br>
**`duration`** - продолжительность контакта в секундах.

*Прочие признаки:*

**`campaign`** - количество контактов с этим клиентом в течение текущей кампании;<br>
**`pdays`** - количество пропущенных дней с момента последней маркетинговой кампании до контакта в текущей кампании;<br>
**`previous`** - количество контактов до текущей кампании;<br>
**`poutcome`** - результат прошлой маркетинговой кампании.

И **целевая переменная** **`deposit`**, которая определяет, согласится ли клиент открыть депозит в банке. Именно её мы будем пытаться предсказать в данном кейсе.

## Этапы проекта:

### 1. Первичная обработка данных

В рамках этой части предстоит обработать пропуски и выбросы в данных.

### 2. Разведывательный анализ данных (EDA)

Необходимо исследовать данные, нащупать первые закономерности и выдвинуть гипотезы.

### 3. Отбор и преобразование признаков

На этом этапе предстоит перекодировать и преобразовать данные таким образом, чтобы их можно было использовать при решении задачи классификации. 

### 4. Решение задачи классификации: логистическая регрессия и решающие деревья

На данном этапе предстоит построить прогностическую модель и оценить её качество. Подобрать оптимальные параметры модели для того, и получить наилучший результат для конкретного алгоритма.

### 5. Решение задачи классификации: ансамбли моделей и построение прогноза

На заключительном этапе необходимо доработать предсказание с использованием более сложных алгоритмов и оценить, с помощью какой модели возможно сделать более качественные прогнозы.
