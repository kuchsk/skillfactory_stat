# skillfactory_stat
Profession Data Science - Статистические тесты в контексте EDA


asset-v1_SkillFactory+DST-3.0+28FEB2021+type@asset+block@EDA_4_Статистические_тесты_Практика_remake.ipynb
asset-v1_SkillFactory+DST-3.0+28FEB2021+type@asset+block@EDA_4_Статистические_тесты_Практика_remake.ipynb_
Практика. ИССЛЕДОВАНИЕ ДАННЫХ HR-АГЕНТСТВА
1. Постановка задачи
HR-агентство изучает тренды на рынке труда в IT. Компания хочет провести исследование на основе данных о зарплатах в сфере Data Science за 2020–2022 годы и получить некоторые выводы.
Описание столбцов Оригинальный датасет: “Data Science Job Salaries” (kaggle.com) https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries

Исследуйте данные и сделайте выводы по полученным результатам. Подкрепите свои рассуждения и выводы визуализациями и с помощью статистического тестирования проверьте, являются ли выводы статистически значимыми.

В процессе своего анализа вы должны:

Выяснить, какие факторы влияют на зарплату специалиста Data Scientist. А также ответить на ключевые вопросы HR-агентства:

Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
Как соотносятся зарплаты Data Scientist и Data Engineer в 2022 году?
Как соотносятся зарплаты специалистов Data Scientist в компаниях различных размеров?
Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании? Если вы найдёте в данных интересные закономерности, также отметьте их в своём анализе.
Продемонстрируйте использование разных тестов для проверки статистической значимости сделанных выводов:

тесты для количественного признака:

для одной выборки;
для двух выборок;
для нескольких выборок;
тест для категориальных признаков.
Результатом вашей работы должен стать ноутбук (IPYNB-файл) с кодом для исследования, а также с выводами и рассуждениями, полученными на основе разведывательного анализа.

В качестве ответа вставьте в форму ниже файл в формате IPYNB. Ментор проверит ваше решение, поставит оценку и даст комментарии.

Критерии оценки
Проверка соответствию - корректно загрузил данные.

Проверил датасет на наличие пропусков и дубликатов, а также на корректность типов данных столбцов.
Определил в данных неинформативные признаки, которые не будут участвовать в исследовании.
Классифицировал все признаки на числовые и категориальные.
Нашёл основные статистические характеристики для каждого из признаков.
Разведывательный анализ данных 2.1. Визуальный анализ данных

Выполнил визуальный анализ данных.

Сделан базовый анализ для каждого признака, участвующего в исследовании:

для числовых признаков построены гистограммы, иллюстрирующие распределения;

для категориальных признаков определено количество записей для каждой категории и построены соответствующие визуализации.

Создал корректные визуализации, которые демонстрируют влияние каждого из признаков, участвующих в исследовании, на зарплату по всем наименованиям Data Scientist или на зарплату по всем должностям.

На основе визуального анализа дал первичные ответы на поставленный в задании вопрос: «Какие факторы влияют на заработную плату?».

2.2. Статистический анализ данных

В исследовании подтвердил или опроверг свои первичные гипотезы, полученные на этапе визуального анализа, с помощью статистических тестов:
Корректно сформулировал нулевые и альтернативные гипотезы на основе поставленных бизнес-вопросов.
Правильно выбрал статистический тест для каждой из гипотез, предварительно проверив условие его применения (там, где это необходимо):
Проверка на нормальность;
Проверка равенства дисперсий в группах.
Успешно протестировал данные, продемонстрировав владение различными статистическими тестами:

Тесты для количественного признака:
для одной выборки;
для двух выборок;
для нескольких выборок;
тест для категориальных признаков.
Соответствие выводов бизнес-вопросам привёл развёрнутые и обоснованные ответы по каждому вопросу:

Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
Как соотносятся зарплаты Data Scientist и Data Engineer в 2022 году?
Как соотносятся зарплаты специалистов Data Scientist в компаниях различных размеров?
Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?
Представленные выводы корректны и соответствуют результатам, полученным в ходе статистического анализа.
Дополнительное исследование

Самостоятельно корректно сформулировал минимум три дополнительных бизнес-гипотезы о влиянии факторов на заработную плату специалистов и для каждой гипотезы:
представил визуальный анализ данных;произвёл статистическое тестирование;
сделал верные, соответствующие бизнес-вопросам выводы по полученным результатам.
Оформление исследования качественно оформил решение задачи:

Описана постановка задачи.На протяжении всего исследования прослеживается логика,
ноутбук имеет понятную структуру, разделён на части заголовками.
Есть промежуточные выводы.
Все визуализации имеют подписи к осям и заголовки и соответствуют стандартам оформления.
Сделан финальный вывод по исследованию.
Код понятный, оформлен по стандартам PEP-8 и сопровождён комментариями
Ответить на эти вопросы нам помогут следующие данные

Источник датасета:"ds_salaries.csv" (skillfactory.ru)

https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@ds_salaries.zip

Данные содержат следующие столбцы:
work_year Год, в котором была выплачена зарплата.

experience_level Опыт работы на этой должности в течение года со следующими возможными значениями: работы на этой должности в течение года со следующими возможными значениями:

EN — Entry-level/Junior;
MI — Mid-level/Intermediate;
SE — Senior-level/Expert;
EX — Executive-level/Director.
employment_type - Тип трудоустройства для этой роли:

PT — неполный рабочий день;
FT — полный рабочий день;
CT — контракт;
FL — фриланс.
job_title Роль, в которой соискатель работал в течение года.

salary Общая выплаченная валовая сумма заработной платы.

salary_currency Валюта выплачиваемой заработной платы в виде кода валюты ISO 4217.

salary_in_usd Зарплата в долларах США (валютный курс, делённый на среднее значение курса доллара США за соответствующий год через fxdata.foorilla.com).

employee_residence Основная страна проживания сотрудника в течение рабочего года в виде кода страны ISO 3166.

remote_ratio Общий объём работы, выполняемой удалённо. Возможные значения:

0 — удалённой работы нет (менее 20 %);
50 — частично удалённая работа;
100 — полностью удалённая работа (более 80 %).
company_location Страна главного офиса работодателя или филиала по контракту в виде кода страны ISO 3166.

company_size Среднее количество людей, работавших в компании в течение года:

S — менее 50 сотрудников (небольшая компания);
M — от 50 до 250 сотрудников (средняя компания);
L — более 250 сотрудников (крупная компания).
2. Загрузка данных

[29]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
# загружаем необходимые библиотеки
import pandas as pd
import numpy as np
import statsmodels.api as sm
import matplotlib.pyplot as plt
import seaborn as sns

from scipy import stats
from statsmodels import stats as sms
from scipy.stats import shapiro, ttest_ind, mannwhitneyu, kruskal, chi2_contingency, f_oneway

# делаем визуальную настройку графиков
sns.set_theme("notebook")
sns.set_palette("Set2")
Данные были скопированы в Google Drive, они доступны по ссылке.

Для скачивания данных используйте команду !wget.

Данные появятся в локальной директории.


[30]
1 сек.
   1
   2
   3
   4
# скачиваем датасет

# в ссылке указан id файла на Google Drive "1b_NEk_nrBLhYxBo-DI-TVLRsTIOYvk-r", id файла взят из ссылки на файл https://drive.google.com/file/d/1YFCuMCG9T8k3ys9HseCkb8dU86N4NN2m/view
!wget "https://drive.google.com/uc?export=download&id=1YFCuMCG9T8k3ys9HseCkb8dU86N4NN2m" -O ds_salaries.csv
--2025-07-17 15:05:00--  https://drive.google.com/uc?export=download&id=1YFCuMCG9T8k3ys9HseCkb8dU86N4NN2m
Resolving drive.google.com (drive.google.com)... 108.177.97.100, 108.177.97.101, 108.177.97.113, ...
Connecting to drive.google.com (drive.google.com)|108.177.97.100|:443... connected.
HTTP request sent, awaiting response... 303 See Other
Location: https://drive.usercontent.google.com/download?id=1YFCuMCG9T8k3ys9HseCkb8dU86N4NN2m&export=download [following]
--2025-07-17 15:05:00--  https://drive.usercontent.google.com/download?id=1YFCuMCG9T8k3ys9HseCkb8dU86N4NN2m&export=download
Resolving drive.usercontent.google.com (drive.usercontent.google.com)... 173.194.174.132, 2404:6800:4008:c03::84
Connecting to drive.usercontent.google.com (drive.usercontent.google.com)|173.194.174.132|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 36960 (36K) [application/octet-stream]
Saving to: ‘ds_salaries.csv’

ds_salaries.csv     100%[===================>]  36.09K  --.-KB/s    in 0s      

2025-07-17 15:05:01 (117 MB/s) - ‘ds_salaries.csv’ saved [36960/36960]


[31]
0 сек.
   1
   2
   3
# загружаем датасет
data = pd.read_csv('./ds_salaries.csv')
data.head()

Далее:

[32]
0 сек.
   1
   2
   3
# задаём уровень значимости
alpha = 0.05
print("Уровень значимости alpha = {:.2f}".format(alpha))
Уровень значимости alpha = 0.05
3. Описательный анализ данных

[33]
0 сек.
   1
data.info()
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 607 entries, 0 to 606
Data columns (total 12 columns):
 #   Column              Non-Null Count  Dtype 
---  ------              --------------  ----- 
 0   Unnamed: 0          607 non-null    int64 
 1   work_year           607 non-null    int64 
 2   experience_level    607 non-null    object
 3   employment_type     607 non-null    object
 4   job_title           607 non-null    object
 5   salary              607 non-null    int64 
 6   salary_currency     607 non-null    object
 7   salary_in_usd       607 non-null    int64 
 8   employee_residence  607 non-null    object
 9   remote_ratio        607 non-null    int64 
 10  company_location    607 non-null    object
 11  company_size        607 non-null    object
dtypes: int64(5), object(7)
memory usage: 57.0+ KB
В датасете 607 записей (без пропущенных значений).

4. Очистка данных
Проверим какие столбцы являются неинформативными и их можно удалить, обычно это столбцы
С высокой долей пропусков
С низким числом уникальных значений
С высоким числом одинаковых значений

[34]
0 сек.
12345678910111213141516171819202122232425262728
# Создаём список удалённых столбцов для отчёта
removed_columns = []

# 1. Удаление столбцов с высокой долей пропусков
threshold = 0.8
null_rates = data.isnull().mean()
cols_with_high_nulls = null_rates[null_rates >= threshold].index.tolist()
#data.drop(cols_with_high_nulls, axis=1, inplace=True)
removed_columns.extend([(col, 'высокий процент пропусков') for col in cols_with_high_nulls])


Может быть удалено столбцов: 1
Столбец 'employment_type' может быть удалён по причине: большинство значений одинаковое (>95%)
Проверим этот столбец для принятие решения об удалении

[35]
0 сек.
   1
data['employment_type'].value_counts()

Действительно, столбец 'employment_type' выглядит не очень информативно, но я его оставлю для дальнейшего анализа
Автоудаление ничего не дало, далее удаления от размышления
Unnamed: 0 удаляю, т.к. он представляет из себя индекс и с ним дубликаты приобретают уникальность
salary и salary_currency скомпанованы в столбце salary_in_usd, поэтому считаю их излишними и также удаляю

[36]
0 сек.
   1
   2
# Удаление неинформативных столбцов
data.drop(columns=['Unnamed: 0', 'salary', 'salary_currency'], inplace=True)
Проверим данные на наличие полных дубликатов:

[37]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
# Проверим количество дубликатов до удаления дубликатов
print(f'Количество дубликатов до удаления дубликатов: {data.duplicated().sum()}')

# Удаляем дубликаты:
data = data.drop_duplicates()
print(f'\nРазмер таблицы после удаления дубликатов: {data.shape}')

# Проверка дубликатов
duplicates = data.duplicated().sum()
print(f'\nКоличество дубликатов: {duplicates}')
Количество дубликатов до удаления дубликатов: 42

Размер таблицы после удаления дубликатов: (565, 9)

Количество дубликатов: 0
Удаление неинформативных столбцов позволило найти дубликаты и избавиться от них
Проверим данные на Количество пропущенных значений:

[38]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
# Проверка на количество пропущенных значений
missing_values = data.isnull().sum()
print('Количество пропущенных значений:')
print(missing_values)

# Удаление строк с пропущенными значениями, если они есть
if missing_values.sum() > 0:
    data.dropna(inplace=True)
    print('\nСтроки с пропущенными значениями были удалены.')
else:
    print('\nПропущенные значения отсутствуют. Строки не были удалены.')
Количество пропущенных значений:
work_year             0
experience_level      0
employment_type       0
job_title             0
salary_in_usd         0
employee_residence    0
remote_ratio          0
company_location      0
company_size          0
dtype: int64

Пропущенные значения отсутствуют. Строки не были удалены.
Пропущенные значения отсутствуют. Строки не были удалены.
5. Статистический анализ данных
Проведем дополнительные исследования данных

Базовый анализ данных.

Будет сделан базовый анализ для каждого признака, участвующего в исследовании:
Визуальный анализ данных.

Для числовых признаков будут построены гистограммы, иллюстрирующие распределения
Для категориальных признаков будет определено количество записей для каждой категории и построены соответствующие визуализации.

[39]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
  35
  36
  37
  38
# 1. Проверка типов данных
print("\nТипы данных столбцов:")
print(data.dtypes)

# 2. Классификация признаков
numeric_features = data.select_dtypes(include=np.number).columns.tolist()
categorical_features = data.select_dtypes(exclude=np.number).columns.tolist()

print("\nЧисловые признаки:", numeric_features)
print("\nКатегориальные признаки:", categorical_features)

# 3. Статистика для числовых признаков
print("\nСтатистика для числовых признаков:")
print(data[numeric_features].describe())

# 4. Статистика для категориальных признаков
print("\nСтатистика для категориальных признаков:")
print(data[categorical_features].describe(include='O'))

# 5. Анализ уникальных значений в категориальных признаках
print("\nУникальные значения в категориальных признаках:")
for col in categorical_features:
    print(f"{col}: {data[col].nunique()} уникальных значений")

# 6. Анализ зарплаты
print("\nРаспределение зарплат (процентное соотношение):")
salary_dist = data['salary_in_usd'].value_counts(normalize=True) * 100
print(salary_dist.apply(lambda x: f"{x:.2f}%"))

# 7. Географические данные
country_cols = ['employee_residence', 'company_location']
for col in country_cols:
    print(f"\n{col}:")
    print(f"  Уникальных значений: {data[col].nunique()}")
    print(f"  Топ 5 стран:\n{data[col].value_counts(normalize=True).nlargest(5)}")

# 8. Анализ удаленной работы
print(f"\nРаспределение remote_ratio:\n{data['remote_ratio'].value_counts(normalize=True).round(2)}")

Типы данных столбцов:
work_year              int64
experience_level      object
employment_type       object
job_title             object
salary_in_usd          int64
employee_residence    object
remote_ratio           int64
company_location      object
company_size          object
dtype: object

Числовые признаки: ['work_year', 'salary_in_usd', 'remote_ratio']

Категориальные признаки: ['experience_level', 'employment_type', 'job_title', 'employee_residence', 'company_location', 'company_size']

Статистика для числовых признаков:
         work_year  salary_in_usd  remote_ratio
count   565.000000     565.000000    565.000000
mean   2021.364602  110610.343363     69.911504
std       0.698138   72280.702792     40.900666
min    2020.000000    2859.000000      0.000000
25%    2021.000000   60757.000000     50.000000
50%    2021.000000  100000.000000    100.000000
75%    2022.000000  150000.000000    100.000000
max    2022.000000  600000.000000    100.000000

Статистика для категориальных признаков:
       experience_level employment_type       job_title employee_residence  \
count               565             565             565                565   
unique                4               4              50                 57   
top                  SE              FT  Data Scientist                 US   
freq                243             546             130                295   

       company_location company_size  
count               565          565  
unique               50            3  
top                  US            M  
freq                318          290  

Уникальные значения в категориальных признаках:
experience_level: 4 уникальных значений
employment_type: 4 уникальных значений
job_title: 50 уникальных значений
employee_residence: 57 уникальных значений
company_location: 50 уникальных значений
company_size: 3 уникальных значений

Распределение зарплат (процентное соотношение):
salary_in_usd
100000    2.30%
150000    2.12%
120000    2.12%
200000    1.59%
80000     1.42%
          ...  
69000     0.18%
54000     0.18%
116150    0.18%
140250    0.18%
175100    0.18%
Name: proportion, Length: 369, dtype: object

employee_residence:
  Уникальных значений: 57
  Топ 5 стран:
employee_residence
US    0.522124
GB    0.076106
IN    0.053097
CA    0.047788
DE    0.042478
Name: proportion, dtype: float64

company_location:
  Уникальных значений: 50
  Топ 5 стран:
company_location
US    0.562832
GB    0.081416
CA    0.049558
DE    0.047788
IN    0.042478
Name: proportion, dtype: float64

Распределение remote_ratio:
remote_ratio
100    0.61
0      0.21
50     0.17
Name: proportion, dtype: float64

[40]
2 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
# 9. Визуализация числовых признаков
numeric_features = ['work_year', 'salary_in_usd', 'remote_ratio']
for feature in numeric_features:
    plt.figure(figsize=(8, 4))
    sns.histplot(data[feature], bins=20, kde=True)
    plt.title(f'Распределение признака {feature}')
    plt.xlabel(feature)
    plt.ylabel('Количество')
    plt.show()

# 10. Визуализация категориальных признаков
for feature in categorical_features:
    counts = data[feature].value_counts()
    plt.figure(figsize=(18, 4))
    sns.barplot(x=counts.index, y=counts.values)
    plt.title(f'Распределение признака {feature}')
    plt.xlabel(feature)
    plt.ylabel('Количество записей')
    plt.xticks(rotation=45)
    plt.show()


[41]
0 сек.
   1
   2
   3
# 11. Краткое описание категориальных признаков (таблица)
for feature in categorical_features:
    print(f"\n{feature}:\n{data[feature].value_counts().to_frame()}\n")

experience_level:
                  count
experience_level       
SE                  243
MI                  208
EN                   88
EX                   26


employment_type:
                 count
employment_type       
FT                 546
PT                  10
CT                   5
FL                   4


job_title:
                                          count
job_title                                      
Data Scientist                              130
Data Engineer                               121
Data Analyst                                 82
Machine Learning Engineer                    39
Research Scientist                           16
Data Science Manager                         12
Data Architect                               11
Machine Learning Scientist                    8
Big Data Engineer                             8
Director of Data Science                      7
AI Scientist                                  7
Principal Data Scientist                      7
Data Science Consultant                       7
Data Analytics Manager                        7
BI Data Analyst                               6
Computer Vision Engineer                      6
ML Engineer                                   6
Lead Data Engineer                            6
Applied Data Scientist                        5
Business Data Analyst                         5
Data Engineering Manager                      5
Head of Data                                  5
Data Analytics Engineer                       4
Head of Data Science                          4
Applied Machine Learning Scientist            4
Analytics Engineer                            4
Machine Learning Developer                    3
Data Science Engineer                         3
Lead Data Analyst                             3
Machine Learning Infrastructure Engineer      3
Lead Data Scientist                           3
Principal Data Engineer                       3
Computer Vision Software Engineer             3
Product Data Analyst                          2
Principal Data Analyst                        2
Cloud Data Engineer                           2
Financial Data Analyst                        2
Director of Data Engineering                  2
Machine Learning Manager                      1
3D Computer Vision Researcher                 1
Marketing Data Analyst                        1
Data Specialist                               1
Finance Data Analyst                          1
Big Data Architect                            1
Staff Data Scientist                          1
ETL Developer                                 1
Head of Machine Learning                      1
NLP Engineer                                  1
Lead Machine Learning Engineer                1
Data Analytics Lead                           1


employee_residence:
                    count
employee_residence       
US                    295
GB                     43
IN                     30
CA                     27
DE                     24
FR                     18
ES                     15
GR                     12
JP                      7
PT                      6
PK                      6
BR                      6
NL                      5
IT                      4
RU                      4
PL                      4
AE                      3
TR                      3
AU                      3
VN                      3
AT                      3
DK                      2
NG                      2
HU                      2
MX                      2
SI                      2
RO                      2
BE                      2
SG                      2
PH                      1
CN                      1
HN                      1
NZ                      1
UA                      1
IQ                      1
CL                      1
MT                      1
IR                      1
CO                      1
HR                      1
BG                      1
KE                      1
MD                      1
RS                      1
HK                      1
LU                      1
JE                      1
CZ                      1
PR                      1
AR                      1
DZ                      1
MY                      1
TN                      1
EE                      1
BO                      1
IE                      1
CH                      1


company_location:
                  count
company_location       
US                  318
GB                   46
CA                   28
DE                   27
IN                   24
FR                   15
ES                   14
GR                   10
JP                    6
NL                    4
PT                    4
PL                    4
AT                    4
MX                    3
DK                    3
AE                    3
PK                    3
LU                    3
TR                    3
BR                    3
AU                    3
RU                    2
CN                    2
CH                    2
BE                    2
NG                    2
SI                    2
IT                    2
CZ                    2
NZ                    1
HU                    1
HN                    1
SG                    1
HR                    1
MT                    1
IL                    1
UA                    1
RO                    1
IQ                    1
MD                    1
CL                    1
IR                    1
VN                    1
KE                    1
CO                    1
AS                    1
DZ                    1
EE                    1
MY                    1
IE                    1


company_size:
              count
company_size       
M               290
L               193
S                82

Общие выводы:

Распределение зарплат имеет правостороннюю асимметрию, с основным скоплением значений в диапазоне от 50,000 до 200,000 USD
В большинстве случаев наблюдается значительное смещение интересов в пользу США:
Более 52% сотрудников живут в США
Более 56% компаний расположены в США
В топе профессий — Data Scientist, с 243 специалистами (примерно 43% от выборки).
Большинство сотрудников — с полным удаленным режимом (100%), около 61%.
В основном — работают в средних компаниях (размер 'M'), примерно 51%.
Средняя зарплата — около 110,610
Есть и максимумы до 600,000
Детали по категориям:

Опыт: большинство — SE (Senior Engineer/Expert), почти половина — опыт уровня SE или MI (Middle).
Тип занятости: абсолютное большинство — Full-time (FT) (546 из 565).
География:
employee_residence — 57 стран, в топе США (52.2%), Великобритания, Индия, Канада, Германия.
company_location — 50 стран, лидируют США (56.3%), Великобритания, Канада, Германия, Индия.
Remote Ratio:
61% сотрудников полностью удалены (100%), 21% — в офисе, остальные — частично.
Наблюдается положительная динамика зарплат 2020 по 2022 год
Размер компании существенно влияет на уровень оплаты: максимальные зарплаты наблюдаются в компаниях среднего размера (M)
Распределение специалистов по размеру компаний показывает, что Data Scientist чаще работают в средних и крупных компаниях, тогда как Data Engineer более равномерно распределены
Уровень опыта является ключевым фактором, влияющим на зарплату: специалисты уровня SE и EX получают значительно больше, чем EN и MI
Распределение зарплат:

Значительные пики около 100,000, 150,000, и до 600,000.
Распределение показывает высокую концентрацию в среднем диапазоне
большинство данных — о специалистах Data Scientist из США и связанных с удаленной работой
Далее пойду по списку...
6. Выяснение факторов влияющих на зарплату Data Scientist и ответы на вопросы HR-агенства
6.1 Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
Проверка распределения зарплат
Для начала проведу тест Шапиро-Уилка, который позволяет определить, соответствует ли распределение зарплат нормальному закону


[42]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
print('Проверка нормальности распределения зарплат:')
# Фильтрация данных по должности
data_ds = data[data['job_title'] == 'Data Scientist']
# Статистика
stat, p_value = stats.shapiro(data_ds['salary_in_usd'])
print(f'Статистика: {stat:.4f}, p-значение: {p_value:.4f}')

# Вывод результата проверки нормальности
if p_value < 0.05:
    print("Распределение зарплат НЕ является нормальным (p < 0.05). Используем непараметрический тест.")
else:
    print("Распределение зарплат является примерно нормальным (p >= 0.05). Можно использовать параметры тесты.")
Проверка нормальности распределения зарплат:
Статистика: 0.9381, p-значение: 0.0000
Распределение зарплат НЕ является нормальным (p < 0.05). Используем непараметрический тест.
Проверка различий в уровнях зарплат по годам
Для оценки наличия статистически значимых различий между зарплатами в разные годы использован непараметрический тест Краскела-Уоллиса, который не требует предположения о нормальности распределения.


[43]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
  35
  36
  37
  38
  39
  40
# Разделение данных по годам
sal_2020 = data_ds[data_ds['work_year'] == 2020]['salary_in_usd']
sal_2021 = data_ds[data_ds['work_year'] == 2021]['salary_in_usd']
sal_2022 = data_ds[data_ds['work_year'] == 2022]['salary_in_usd']

# Тест Краскела-Уоллиса
stat, p = kruskal(sal_2020, sal_2021, sal_2022)
print(f'Статистика: {stat:.4f}, p-значение: {p:.4f}')

# Вычисляем средние или медианы по группам для определения направления изменений
mean_2020 = sal_2020.median()
mean_2021 = sal_2021.median()
mean_2022 = sal_2022.median()

# Визуализации распределений зарплат по годам
plt.figure(figsize=(10,6))
sns.boxplot(x='work_year', y='salary_in_usd', data=data_ds)
plt.title('Распределение зарплат по годам (2020-2022)')
plt.xlabel('Год')
plt.ylabel('Зарплата в USD')
plt.show()

plt.figure(figsize=(10,6))
sns.violinplot(x='work_year', y='salary_in_usd', data=data_ds)
plt.title('Распределение зарплат по годам (2020-2022)')
plt.xlabel('Год')
plt.ylabel('Зарплата в USD')
plt.show()

# Вывод результата в зависимости от p-значения и направления изменения
if p < 0.05:
    # Определяем направление изменения зарплат по медианам
    if mean_2022 > mean_2020:
        print("Статистически значимое увеличение зарплат с 2020 по 2022 годы.")
    elif mean_2022 < mean_2020:
        print("Статистически значимое снижение зарплат с 2020 по 2022 годы.")
    else:
        print("Статистически значимые изменения в зарплатах не обнаружены.")
else:
    print("Нет статистически значимых различий в зарплатах между годами.")

H0 (нулевая гипотеза): Зарплаты у специалистов Data Scientist не различаются по годам.
H1 (альтернативная гипотеза): Зарплаты различаются по годам.
Результат теста показал p-значение, меньшее 0.05, что свидетельствует о статистической значимости различий в уровнях зарплат между 2020, 2021 и 2022 годами.

Выводы

Проведенный тест Краскела-Уоллиса подтвердил наличие существенных различий в уровнях зарплат Data Scientist между 2020, 2021 и 2022 годами.
Это говорит о наличии динамики изменения зарплат в исследуемом периоде.
H0 (нулевая гипотеза): Зарплаты у специалистов Data Scientist не различаются по годам.
H1 (альтернативная гипотеза): Зарплаты различаются по годам.
Результат теста показал p-значение, меньшее 0.05, что свидетельствует о статистической значимости различий в уровнях зарплат между 2020, 2021 и 2022 годами.

Выводы

Проведенный тест Краскела-Уоллиса подтвердил наличие существенных различий в уровнях зарплат Data Scientist между 2020, 2021 и 2022 годами.
Это говорит о наличии динамики изменения зарплат в исследуемом периоде.
6.2 Как соотносятся зарплаты Data Scientist и Data Engineer в 2022 году?

[44]
0 сек.
12345678910111213141516171819202122232425262728293031323334353637383940414243444546
# 1. Фильтрация данных
ds_2022 = data[(data['job_title'] == 'Data Scientist') & (data['work_year'] == 2022)]
de_2022 = data[(data['job_title'] == 'Data Engineer') & (data['work_year'] == 2022)]

# 2. Визуализация распределения зарплат
plt.figure(figsize=(10, 6))
sns.boxplot(x='job_title', y='salary_in_usd', data=pd.concat([ds_2022, de_2022]))
plt.title('Сравнение зарплат Data Scientist и Data Engineer в 2022 году')
plt.xlabel('Должность')
plt.ylabel('Зарплата в USD')


Итоговый вывод
Средняя зарплата Data Scientist на 5.4% выше , чем у Data Engineer.

Однако: по тесту Манна-Уитни p-значение больше обычного уровня значимости 0.05, мы не можем отвергнуть нулевую гипотезу. Вывод: Это означает, что статистически значимых различий в распределении зарплат между специалистами на позициях Data Scientist и Data Engineer в 2022 году нет.

5.3 Как соотносятся зарплаты специалистов Data Scientist в компаниях различных размеров?

[45]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
  35
  36
  37
  38
  39
  40
  41
  42
  43
  44
  45
  46
# Фильтр по Data Scientist
data_ds = data[data['job_title'] == 'Data Scientist']

# Визуализация средних зарплат по размеру компании
avg_salary_by_size = data_ds.groupby('company_size')['salary_in_usd'].mean().reset_index()
avg_salary_by_size = avg_salary_by_size.sort_values(by='salary_in_usd', ascending=False)

plt.figure(figsize=(8,6))
sns.barplot(x='company_size', y='salary_in_usd', data=avg_salary_by_size)
plt.title('Средняя зарплата Data Scientist в компаниях разного размера')
plt.xlabel('Размер компании')
plt.ylabel('Средняя зарплата (USD)')
plt.show()

# Проверка нормальности распределений зарплат по размерам компаний
company_sizes = data_ds['company_size'].unique()
salary_groups = [data_ds[data_ds['company_size'] == size]['salary_in_usd'] for size in company_sizes]
normal_results = [shapiro(group) for group in salary_groups]

# Проверка нормальности
if all(p > 0.05 for _, p in normal_results):
    from scipy.stats import f_oneway
    stat, p_value = f_oneway(*salary_groups)
    test_name = "ANOVA"
    reason = "все группы нормально распределены"
else:
    from scipy.stats import kruskal
    stat, p_value = kruskal(*salary_groups)
    test_name = "Краскела-Уоллиса"
    reason = "хотя бы одна группа не прошла проверку нормальности"

# Вывод результатов теста
print(f"Используемый тест: {test_name} ({reason})")
print(f"Статистика: {stat:.4f}")
print(f"p-значение: {p_value:.4f}")

if p_value < 0.05:
    print("Есть статистически значимые различия в зарплатах в зависимости от размера компании.")
else:
    print("Нет статистически значимых различий в зарплатах по размерам компаний.")

# Числовые соотношения
max_salary = avg_salary_by_size['salary_in_usd'].max()
for index, row in avg_salary_by_size.iterrows():
    ratio = row['salary_in_usd'] / max_salary
    print(f"{row['company_size']}: {row['salary_in_usd']:.2f} USD ({ratio:.2%} от максимальной)")

Влияние размера компании

Выявлено, что наиболее высокие зарплаты наблюдаются в компаниях среднего размера - М

Используемый тест: Краскела-Уоллиса (хотя бы одна группа не прошла проверку нормальности)

Статистика: 22.7467 p-значение: 0.0000

Есть статистически значимые различия в зарплатах в зависимости от размера компании.

M: 120080.58 USD (100.00% от максимальной)
L: 102743.42 USD (85.56% от максимальной)
S: 51925.76 USD (43.24% от максимальной)
5.4 Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?

[46]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
# Фильтруем только нужные должности
filtered_data = data[data['job_title'].isin(['Data Scientist', 'Data Engineer'])]

# Создаем таблицу сопряженности
contingency_table = pd.crosstab(filtered_data['job_title'], filtered_data['company_size'])

# Визуализируем таблицу сопряженности
sns.heatmap(contingency_table, annot=True, fmt='d', cmap='YlGnBu', annot_kws={'size':8})
plt.title('Связь должностей и размера компании')
plt.xlabel('Размер компании')
plt.ylabel('Должность')
plt.show()

# Применяем тест хи-квадрат
chi2, p_value, dof, expected = chi2_contingency(contingency_table)

# Проверка гипотезы
alpha = 0.05
print(f"Chi-squared: {chi2:.4f}")
print(f"P-value: {p_value:.4f}")

if p_value < alpha:
    print("Результат: Есть статистически значимая зависимость между должностью и размером компании (отвергаем нулевую гипотезу).")
else:
    print("Результат: Нет статистически значимой зависимости между должностью и размером компании (не отвергаем нулевую гипотезу).")

Взаимосвязь должностей и размера компании

Тест хи-квадрат выявил статистически значимую связь между должностью специалиста и размером компании (p < 0.05)
Это подтверждает гипотезу о том, что распределение специалистов по должностям зависит от размера организации
5.6 Дополнительные итересные закономерности
5.6.1 Зависимость Средней зарплаты от уровня опыта

[47]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
  35
  36
  37
  38
  39
  40
  41
  42
  43
  44
# Сначала посмотрим визуально
# Группируем выборку
grouped_exp = data.groupby('experience_level')['salary_in_usd'].mean().sort_values()

# График
sns.barplot(x=grouped_exp.index, y=grouped_exp.values)
plt.title('Средняя зарплата по уровню опыта')
plt.ylabel('Зарплата (USD)')
plt.xlabel('Уровень опыта')
plt.show()

# Считаем медиану зарплаты для каждого уровня опыта
median_salary = data.groupby('experience_level')['salary_in_usd'].median().sort_values()

# Получаем отсортированный порядок уровней опыта
sorted_experience_levels = median_salary.index.tolist()

# Строим boxplot с отсортированными уровнями опыта
sns.boxplot(x='experience_level', y='salary_in_usd', data=data, order=sorted_experience_levels)

plt.title('Зарплата по уровню опыта')
plt.ylabel('Зарплата (USD)')
plt.xlabel('Уровень опыта')
plt.show()

# На графиках явно видно различие в зарплате от уровня опыта. Проверим...
# т.к. размер групп сильно различается
groups = {}
for level in data['experience_level'].unique():
    groups[level] = data[data['experience_level'] == level]['salary_in_usd']

# Проведем тест Краскела-Уоллиса
stat_kw, p_kw = kruskal(*groups.values())

print(f"Размеры групп:")
for level, group_data in groups.items():
    print(f"{level}: {len(group_data)}")

print(f"\nРезультаты теста Краскела-Уоллиса: статистика={stat_kw:.3f}, p-value={p_kw:.3f}")

if p_kw > 0.05:
    print("Нет статистически значимых различий между группами.")
else:
    print("Обнаружены статистически значимые различия между группами.")

Размеры групп сильно различаются

MI: 208
SE: 243
EN: 88
EX: 26
Результаты теста Краскела-Уоллиса: статистика=172.973, p-value=0.000

Вывод: Обнаружены статистически значимые различия между группами. С ростом опыта растет и зарплата

5.6.2 Зависимость от типа занятости (employment_type)

[48]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
# Визуализация средней зарплаты по типу занятости
grouped_empl = data.groupby('employment_type')['salary_in_usd'].mean()
# Сортировка значений по убыванию
grouped_empl = grouped_empl.sort_values(ascending=False)
#График
sns.barplot(x=grouped_empl.index, y=grouped_empl.values)
plt.title('Средняя зарплата по типу занятости')
plt.ylabel('Зарплата (USD)')
plt.xlabel('Тип занятости')
plt.show()

# Выясним размер групп 
print(f"Размеры групп:\n{data['employment_type'].value_counts()}\n")

# Проверка на нормальность каждой группы (хотя размера было бы достаточно)
for name, group in data.groupby('employment_type'):
    stat, p = stats.shapiro(group['salary_in_usd'])
    print(f"Группа: {name} | Статистика Шапиро-Уилка={stat:.3f}, p-value={p:.3f}")
    if p < 0.05:
        print(f"Распределение зарплат в группе '{name}' не является нормальным.")
    else:
        print(f"Распределение зарплат в группе '{name}' можно считать нормальным.")

# Берем тест Краскел-Уоллиса, т.к. есть ненормальные и размеры групп сильно отличаются
groups = [group['salary_in_usd'].values for name, group in data.groupby('employment_type')]
h_statistic, p_value = stats.kruskal(*groups)

print("\nСредняя зарплата по типу занятости:\n", grouped_empl)
print(f"Статистика Краскел-Уоллиса: H-статистика={h_statistic:.3f}, p-значение={p_value:.3f}")

if p_value < 0.05:
    print("Существует статистически значимое различие между группами")
else:
    print("Статистических различий между группами нет")

Выводы:

Средний уровень зарплаты по типам занятости:

Самая высокая средняя зарплата у сотрудников, работающих на контрактной основе (CT), составляет 184 575 USD что значительно больше по сравнению с другими типами занятости.
Вторая по уровню — полная занятость (FT), со средней зарплатой 111 812 USD.
Часовая занятость (FL) 48 000 USD.
Частичная занятость (PT) — 33 071 USD.
Влияние типа занятости на уровень зарплаты:

Анализ показал, что тип занятости значительно влияет на уровень зарплаты.
Статистический тест Краскел-Уоллиса подтвердил, что различия между группами являются статистически значимыми (p-значение < 0.05).
Таким образом, тип занятости значительно влияет на уровень зарплаты

5.6.3 Растет ли зарплата каждый год?

[49]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
  35
  36
  37
  38
  39
  40
  41
  42
  43
  44
  45
  46
  47
  48
# Отфильтруем данные по годам
df_2020 = data[data['work_year'] == 2020]['salary_in_usd']
df_2021 = data[data['work_year'] == 2021]['salary_in_usd']
df_2022 = data[data['work_year'] == 2022]['salary_in_usd']

# Визуализация распределения зарплат по годам
plt.figure(figsize=(10,6))
sns.boxplot(x='work_year', y='salary_in_usd', data=data)
plt.title('Распределение зарплат по годам (2020-2022)')
plt.xlabel('Год')
plt.ylabel('Зарплата в USD')
plt.show()

plt.figure(figsize=(10,6))
sns.violinplot(x='work_year', y='salary_in_usd', data=data)
plt.title('Распределение зарплат по годам (2020-2022)')
plt.xlabel('Год')
plt.ylabel('Зарплата в USD')
plt.show()

# Проверка нормальности с помощью теста Шапиро-Уилка
p_values = []
for year, group in zip([2020, 2021, 2022], [df_2020, df_2021, df_2022]):
    stat, p = stats.shapiro(group)
    p_values.append(p)
    print(f"Год {year} | Статистика Шапиро-Уилка={stat:.3f}, p-value={p:.3f}")
    if p < 0.05:
        print(f"Распределение зарплат в {year} не является нормальным.")
    else:
        print(f"Распределение зарплат в {year} можно считать нормальным.")

# Выбор подходящего теста (потом сокращу)
if all(p > 0.05 for p in p_values):
    # Все группы нормальны и дисперсии равны - используем ANOVA
    F_stat, p_value = stats.f_oneway(df_2020, df_2021, df_2022)
    print(f"\nВсе группы нормальны и дисперсии равны - используем ANOVA | F-статистика={F_stat:.3f}, p-value={p_value:.3f}")
    if p_value < 0.05:
        print("Есть статистическая разница между группами зарплат по годам.")
    else:
        print("Нет статистической разницы между группами зарплат по годам.")
else:
    # Не все условия выполнены — используем Краскел-Уоллиса
    h_statistic, p_value = stats.kruskal(df_2020, df_2021, df_2022)
    print(f"\nНе все условия выполнены — используем Краскел-Уоллиса | H-статистика={h_statistic:.3f}, p-value={p_value:.3f}")
    if p_value < 0.05:
        print("Есть статистическая разница между группами зарплат по годам.")
    else:
        print("Нет статистической разницы между группами зарплат по годам.")

Вывод: Зарплата растет

5.6.4 Проверим как соотносятся уровень опыта с удаленной работой

[50]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
# Создаем кросс-таблицу: experience_level vs employment_type
ct_experience_employment = pd.crosstab(data['experience_level'], data['remote_ratio'])

# Визуализация: столбчатая диаграмма для experience_level по employment_type
ct_experience_employment.plot(kind='bar', stacked=True, figsize=(10,6))
plt.title('Опыт работы vs Удаленный коэффициент')
plt.xlabel('Уровень опыта')
plt.ylabel('Удаленный коэффициент')
plt.legend(title='Удаленка')
plt.show()

# Создаем таблицу сопряженности (кросс-таблицу)
ct = pd.crosstab(data['experience_level'], data['remote_ratio'])

print("Кросс-таблица:\n", ct)

# Выполняем χ²-тест независимости
chi2, p, dof, ex = chi2_contingency(ct)

print(f'χ²-статистика: {chi2}')
print(f'p-value: {p}')

# Интерпретация
alpha = 0.05
if p < alpha:
    print("Есть статистически значимая зависимость между уровнем опыта и удаленным коэффициентом (отклоняем H0).")
else:
    print("Нет статистически значимой зависимости между уровнем опыта и удаленным коэффициентом (не отвергаем H0).")

Вывод: Удаленная работа занимает большую часть в работе любой группы, опытные работники чаще работают на удаленке Продолжу исследование...

5.6.5 Построю таблицу сопряженности и выясню зависимость Уровня опыта и Удаленного коэффициента

[51]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
cross_tab = pd.crosstab(index=data['remote_ratio'], columns=data['experience_level'])
ax = sns.heatmap(cross_tab, annot=True, linewidth=.5, fmt='.0f', cmap="coolwarm")
ax.set(xlabel='Удаленный коэффициент', ylabel='Уровень опыта')
plt.title('Таблица сопряженности')
plt.show()

from scipy.stats import chi2_contingency

# Выполняем χ²-тест для таблицы сопряженности
chi2, p_value, dof, expected = chi2_contingency(cross_tab)

print(f'Chi-squared statistic: {chi2}')
print(f'p-value: {p_value}')

alpha = 0.05
if p < alpha:
    print("Есть статистически значимая зависимость между уровнем опыта и удаленным коэффициентом (отклоняем H0).")
else:
    print("Нет статистически значимой зависимости между уровнем опыта и удаленным коэффициентом (не отвергаем H0).")

Вывод:

Общая картина распределения:
В группе с уровнем опыта "100" (самый высокий уровень) наблюдается значительное скопление участников в категории "SE" (самая удаленная работа), где их количество составляет 166, что является крупнейшим числом среди всех категорий.

В группе с уровнем опыта "0" (отсутствие опыта или минимальный опыт) наибольшее число — 54 — приходится на категорию "MI".

В группе "50" по опыту наиболее распространена категория "EN" (минимально удаленная работа), с 25 участниками.

Связь между уровнем опыта и удаленностью:
Можно заметить, что с увеличением уровня опыта (от 0 до 100) растет число участников, предпочитающих более удаленную работу (SE). В частности, в группе с опытом 100 их 166, что явно указывает на тренд к более высокой удаленности у опытных специалистов.

В то же время, участники с низким уровнем опыта (0 и 50) распределены более равномерно по категориям, но с заметным преобладанием менее удаленных вариантов ("EN" и "MI").

Общим итогом, больше опыта - больше возможности работать удаленно
5.6.6 Найдем главных удаленщиков

[52]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
# Создаем категорию remote_ratio
data['remote_category'] = pd.cut(data['remote_ratio'], bins=[-1, 0, 50, 100], labels=['Нет удаленной работы', 'Частичная удаленная', 'Полностью удаленная'])

# Создаем кросс-таблицу: remote_category vs job_title
ct_remote_job_title = pd.crosstab(data['remote_category'], data['job_title'])

# Визуализация: топ 8 должностей по удаленности
top_jobs = data['job_title'].value_counts().index[:8]
ct_remote_top_jobs = pd.crosstab(data['remote_category'], data['job_title'])
ct_remote_top_jobs = ct_remote_top_jobs[top_jobs]

ct_remote_top_jobs.plot(kind='bar', stacked=True, figsize=(10,6))
plt.title('Влияние удаленности на топ-8 должностей')
plt.xlabel('Категория удаленности')
plt.ylabel('Количество')
plt.legend(title='Должность', bbox_to_anchor=(1.05, 1), loc='upper left')
plt.tight_layout()
plt.show()

# Создаем кросс-таблицу между remote_category и job_title
ct_remote_job_title = pd.crosstab(data['remote_category'], data['job_title'])

# Выполняем χ²-тест независимости
chi2, p, dof, ex = chi2_contingency(ct_remote_job_title)

print(f'χ²-статистика: {chi2}')
print(f'p-value: {p}')

# Интерпретация
alpha = 0.05
if p < alpha:
    print("Есть статистически значимая зависимость между категорией удаленности и должностью (отклоняем H0).")
else:
    print("Нет статистически значимой зависимости между категорией удаленности и должностью (не отвергаем H0).")

Вывод: Главные удаленщики - Data специалисты

5.6.7 Выясним зависимость между средней зарплатой и количеством вакансий в странах

[53]
0 сек.
   1
   2
   3
   4
   5
   6
   7
   8
   9
  10
  11
  12
  13
  14
  15
  16
  17
  18
  19
  20
  21
  22
  23
  24
  25
  26
  27
  28
  29
  30
  31
  32
  33
  34
  35
  36
  37
  38
  39
  40
  41
  42
  43
  44
  45
  46
  47
  48
  49
  50
  51
  52
  53
  54
  55
  56
  57
  58
  59
  60
  61
  62
  63
# Группируем по странам и считаем среднюю зарплату и количество вакансий
grouped = data.groupby('company_location').agg(average_salary=('salary_in_usd', 'mean'), vacancy_count=('salary_in_usd', 'size')).reset_index()

# Получаем топ-20 стран по средней зарплате
top20 = grouped.sort_values('average_salary', ascending=False).head(20)

# Проверим нормальность для средней зарплаты
stat_salary, p_salary = shapiro(top20['average_salary'])
print(f"Нормальность средней зарплаты: p-value={p_salary:.3f}")

# Проверим нормальность для количества вакансий
stat_vacancy, p_vacancy = shapiro(top20['vacancy_count'])
print(f"Нормальность количества вакансий: p-value={p_vacancy:.3f}")

# Визуализация
sns.set(style="darkgrid")
fig, ax1 = plt.subplots(figsize=(12, 8))

# Барплот для средней зарплаты
sns.barplot(x='average_salary', y='company_location', data=top20, ax=ax1)
ax1.set_xlabel('Средняя зарплата в USD')
ax1.set_ylabel('Страна компании')
ax1.set_title('Топ 20 стран по средней зарплате и количеству вакансий')

# Создаем вторую ось для количества вакансий
ax2 = ax1.twiny()

# Строим точки для количества вакансий и добавляем интерпретацию
sns.scatterplot(x='vacancy_count', y='company_location', data=top20, ax=ax2, color='orange', s=100, label='Количество вакансий')

ax2.set_xlabel('Количество вакансий')
ax2.legend(loc='upper right')

plt.tight_layout()
plt.show()

# Проверим нормальность для средней зарплаты
stat_salary, p_salary = shapiro(top20['average_salary'])
print(f"Нормальность средней зарплаты: p-value={p_salary:.3f}")

# Проверим нормальность для количества вакансий
stat_vacancy, p_vacancy = shapiro(top20['vacancy_count'])
print(f"Нормальность количества вакансий: p-value={p_vacancy:.3f}")

# Расчет корреляции Спирмена
correlation_spearman = top20['average_salary'].corr(top20['vacancy_count'], method='spearman')
print(f"Коэффициент корреляции Спирмена: {correlation_spearman:.2f}")

# Интерпретация
if correlation_spearman > 0.7:
    interpretation = "сильной положительной связи"
elif correlation_spearman > 0.4:
    interpretation = "умеренной положительной связи"
elif correlation_spearman > 0.1:
    interpretation = "слабой положительной связи"
elif correlation_spearman < -0.1:
    interpretation = "слабой отрицательной связи"
elif correlation_spearman < -0.4:
    interpretation = "умеренной отрицательной связи"
else:
    interpretation = "отсутствии значимой связи"

print(f"Это говорит о {interpretation} между средней зарплатой и количеством вакансий по странам.")

Выводы:

Самые большие зарплаты в России, но этот показатель базируется всего на двух вакансиях,
в то время как в US 318 вакансий, но зп ниже чем в России
По исследованию это говорит о отсутствии значимой связи между средней зарплатой и количеством вакансий по странам.
Интерактивная карта зарплат (десерт)

[54]
12 сек.
    1
    2
    3
    4
    5
    6
    7
    8
    9
   10
   11
   12
   13
   14
   15
   16
   17
   18
   19
   20
   21
   22
   23
   24
   25
   26
   27
   28
   29
   30
   31
   32
   33
   34
   35
   36
   37
   38
   39
   40
   41
   42
   43
   44
   45
   46
   47
   48
   49
   50
   51
   52
   53
   54
   55
   56
   57
   58
   59
   60
   61
   62
   63
   64
   65
   66
   67
   68
   69
   70
   71
   72
   73
   74
   75
   76
   77
   78
   79
   80
   81
   82
   83
   84
   85
   86
   87
   88
   89
   90
   91
   92
   93
   94
   95
   96
   97
   98
   99
  100
  101
  102
  103
  104
  105
  106
  107
  108
  109
  110
  111
  112
  113
  114
  115
  116
  117
  118
  119
  120
  121
  122
  123
  124
  125
  126
  127
  128
  129
  130
  131
  132
  133
  134
  135
  136
  137
  138
  139
  140
  141
  142
  143
  144
  145
  146
  147
  148
  149
  150
  151
  152
  153
  154
  155
  156
  157
  158
  159
  160
  161
  162
  163
  164
  165
  166
  167
  168
  169
  170
  171
  172
  173
  174
  175
  176
  177
  178
  179
  180
  181
  182
!pip install -q dash
!pip install -q pycountry

import dash
from dash import Dash, dcc, html, Input, Output, State
import plotly.express as px
import pycountry

# Преобразование кодов стран в имена
iso2_to_name = {country.alpha_2: country.name for country in pycountry.countries}
data['country_name'] = data['company_location'].map(iso2_to_name)

# Уникальные значения для фильтров
def get_options(series):
    return [{'label': str(val), 'value': val} for val in sorted(series.unique())]

# Создаем словарь с возможными фильтрами
filters_config = {
    'year': {
        'label': 'Год',
        'options': get_options(data['work_year']),
        'initial': [str(year) for year in data['work_year'].unique()]
    },
    'experience': {
        'label': 'Уровень опыта',
        'options': get_options(data['experience_level']),
        'initial': list(data['experience_level'].unique())
    },
    'employment': {
        'label': 'Тип занятости',
        'options': get_options(data['employment_type']),
        'initial': list(data['employment_type'].unique())
    },
    'job': {
        'label': 'Должность',
        'options': get_options(data['job_title']),
        'initial': list(data['job_title'].unique())
    }
}

# Универсальная функция для создания групп фильтров с кнопками "Все" и "Снять"
def create_filter_group(filter_id, label, options, initial):
    return html.Div([
        html.H5(label),
        html.Button('Все', id=f'select-all-{filter_id}', n_clicks=0),
        html.Button('Снять', id=f'deselect-all-{filter_id}', n_clicks=0),
        dcc.Checklist(
            id=filter_id,
            options=options,
            value=initial,
            inline=True,
            labelStyle={'margin-right': '15px'}
        )
    ], style={'padding': '10px', 'border': '1px solid #ddd', 'margin': '10px', 'background': '#f9f9f9'})
    
# Создаем элементы фильтров
filter_groups = []
for key, config in filters_config.items():
    filter_groups.append(
        create_filter_group(key, config['label'], config['options'], config['initial'])
    )

# Основной лейаут
app = Dash(__name__)
app.layout = html.Div([
    html.H1("Интерактивная карта зарплат", style={'textAlign': 'center'}),
    html.Div(filter_groups, style={'display': 'flex', 'flex-wrap': 'wrap', 'justify-content': 'space-around'}),
    dcc.Graph(id='world-map', style={'height': '80vh'})
])

# Обработка кнопок "Все"/"Снять" для каждого фильтра
for key in filters_config.keys():
    @app.callback(
        Output(key, 'value'),
        [Input(f'select-all-{key}', 'n_clicks'),
         Input(f'deselect-all-{key}', 'n_clicks')],
        State(key, 'options')
    )
    def update_checklist(select_all_clicks, deselect_all_clicks, options, filter_id=key):
        ctx = dash.callback_context
        if not ctx.triggered:
            return [opt['value'] for opt in options]
        button_id = ctx.triggered[0]['prop_id'].split('.')[0]
        if button_id == f'select-all-{filter_id}':
            return [opt['value'] for opt in options]
        elif button_id == f'deselect-all-{filter_id}':
            return []
        return [opt['value'] for opt in options]

# Обновляем карту при изменении фильтров
@app.callback(
    Output('world-map', 'figure'),
    [Input(f'{key}', 'value') for key in filters_config.keys()]
)
def update_map(years, exp_levels, emp_types, jobs):
    # Преобразуем годы в строки для сравнения
    years_str = [str(y) for y in years]
    
    filtered = data[
        (data['work_year'].astype(str).isin(years_str)) &
        (data['experience_level'].isin(exp_levels)) &
        (data['employment_type'].isin(emp_types)) &
        (data['job_title'].isin(jobs))
    ]
    
    if filtered.empty:
        # Пустая карта, если данных нет
        fig = px.choropleth()
        fig.update_layout(title='Нет данных по выбранным фильтрам')
        return fig

    # Аггрегация по странам
    aggregated = filtered.groupby('country_name', as_index=False)['salary_in_usd'].mean()

    # Вычисление корреляции
    if len(aggregated) > 1:
        # Можно использовать корреляцию Спирмена, учитывая распределение
        correlation = aggregated['salary_in_usd'].corr(filtered['salary_in_usd'], method='spearman')
        # Интерпретация
        if correlation > 0.7:
            interpretation = "Сильная положительная связь"
        elif correlation > 0.4:
            interpretation = "Умеренная положительная связь"
        elif correlation > 0.1:
            interpretation = "Слабая положительная связь"
        elif correlation < -0.1:
            interpretation = "Слабая отрицательная связь"
        elif correlation < -0.4:
            interpretation = "Умеренная отрицательная связь"
        elif correlation < -0.7:
            interpretation = "Сильная отрицательная связь"
        else:
            interpretation = "Отсутствие значимой связи"
    else:
        correlation = None
        interpretation = "Недостаточно данных для оценки связи"

    # Построение карты
    fig = px.choropleth(
        aggregated,
        locations='country_name',
        locationmode='country names',
        color='salary_in_usd',
        hover_name='country_name',
        color_continuous_scale='Viridis',
        labels={'salary_in_usd': 'Зарплата (USD)'},
        title='Средние зарплаты по странам'
    )

    # Добавляем подпись с интерпретацией
    annotation_text = f"Коэффициент корреляции (Спирмен): {correlation:.2f}<br>{interpretation}"

    fig.add_annotation(
        text=annotation_text,
        align='left',
        showarrow=False,
        xref='paper',
        yref='paper',
        x=0,
        y=-0.2,
        bordercolor='black',
        borderwidth=1,
        bgcolor='white'
    )

    # Настройка формы и оформления
    fig.update_layout(
        coloraxis_colorbar=dict(title='USD', x=0.85),
        margin=dict(l=0, r=0, t=40, b=80),
        title=dict(text='Средние зарплаты по странам', x=0.5, font=dict(size=20))
    )

    fig.update_traces(
        hovertemplate="<b>%{hovertext}</b><br>Зарплата: %{z:,.0f} USD"
    )

    return fig


if __name__ == '__main__':
    app.run(debug=True)
    # app.run_server(debug=True)

Интерактивная визуализация: карта позволяет наглядно отображать средние зарплаты специалистов по странам с возможностью фильтрации по различным параметрам.

Фильтрация данных:можно настраивать отображение карты по:

Годам

Уровню опыта

Типу занятости

Должностям

6. Итоговые результаты исследования
Ключевые выводы исследования
Основные тенденции на рынке

Динамика зарплат: зафиксирован статистически значимый рост заработной платы специалистов Data Scientist в период с 2020 по 2022 год

Сравнение специализаций: в 2022 году наблюдается выравнивание уровня зарплат между специалистами Data Scientist и Data Engineer

Влияние масштаба бизнеса: выявлена следующая иерархия по уровню оплаты труда:

Лидирующие позиции — средние компании
Второе место — крупные организации
Третье место — малые предприятия
Взаимосвязь параметров: обнаружена корреляция между должностной позицией (Data Scientist/Data Engineer) и размером компании

Анализ зарплат по странам: Были выявлены страны с самыми высокими и низкими средними зарплатами.

Определено, что в России средняя зарплата основана на небольшом количестве вакансий (только 2), тогда как в США — на 318 вакансиях.
Обнаружена слабая положительная связь между средней зарплатой и количеством вакансий по странам.
Факторы, влияющие на уровень дохода
Профессиональный опыт:

Значительное влияние на размер заработной платы
Руководители и старшие специалисты получают более высокую оплату
Форма занятости:

Контрактные сотрудники имеют преимущество в уровне дохода
Формат работы:

Удаленный формат ассоциируется с более высокими зарплатами
Особенно характерен для специалистов высокого уровня
подготовил Кучеревский С.К. kuchsk@gmail.com

Платные продукты Colab - Отменить подписку
Made 1 formatting edit on line 71
