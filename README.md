**Лектор:** Дмитрий Петрович Ветров

**Семинаристы:** Кирилл Струминский, Артём Соболев, Арсений Ашуха, Олег Иванов, Айбек Аланов, Артëм Гадецкий, Оганесян Виктор, Александр Гришин

**Ассистенты:** Никита Юдин, Александр Марков, Никита Бондарцев, Денис Ракитин

**Контакты:** по всем вопросам, связанным с курсом, просьба писать на **bayesml@gmail.com**. В название письма обязательно добавлять тег **[ШАД НБМ20]** (письма без этого тега могут просто не дойти до преподавателей).

У курса также есть чат в телеграме. Все объявления по курсу будут выкладываться именно в этом чате, поэтому настоятельно рекомендуется к нему присоединиться. Основной язык чата - английский.

### Краткое описание

Курс посвящен применению байесовских методов в глубинном обучении. На лекциях будет рассказано о применении вероятностного моделирования для построения порождающих моделей данных, использованию состязающихся сетей для приближенного вывода, моделированию неопределенности в параметрах нейронной сети и о некоторых открытых проблемах глубинного обучения.

### Новости

### Отчётность по курсу и критерии оценки

* В рамках курса предполагается выполнение 4 практических заданий, каждое из которых оценивается из 10-ти баллов.
* Из них складывается оценка как как среднее **взвешенное** <br>
<Средняя_оценка_за_задания>= 1 / 6 * SVD + 1 / 6 * NF + 1 / 3 * VAE + 1 / 3 * DLV (аббревиатуры тем)
* Необходимым условием получения оценки 3/4/5 (по пятибальной шкале) за курс является сдача не менее 1/2/3 практических заданий соответственно.
* В конце семестра можно опционально сдать экзамен по курсу (он не обязателен, оценку «отлично» можно получить и без него!). Путем сдачи экзамена можно повысить свою оценку максимум на 3 балла.
* Итоговый балл за курс вычисляется по формуле <Средняя_оценка_за_задания> + 0.3*<Оценка_за_экзамен>. <br> Итоговый балл округляется математически.
* Оценке 5 в пятибальной шкале соответствует оценка 8 и выше, оценке 4 -- оценка [6, 8), оценке 3 -- промежуток [4, 6).

### Практические задания

* В рамках курса предполагается выполнение четырех практических заданий на следующие темы: Sparse Variational Dropout, Normalizing Flows, Variational Autoencoder, Discrete Latent Variables.
* Приём заданий по курсу осуществляется в системе anytask.
* Все задания сдаются на Python 3 с использованием PyTorch.
* Все задания должны выполняться студентами самостоятельно. Использование кода коллег или кода из открытых источников запрещено и будет считаться плагиатом. Все студенты, замешанные в плагиате (в том числе и те, у кого списали), будут сурово наказаны.
* Все задания оцениваются из 10 баллов. За сдачу заданий позже срока начисляется штраф в размере 0.3 балла за каждый день просрочки, но суммарно не более 6-и баллов. Для студентов филиалов первая неделя после срока идёт без штрафа.
* На выполнение каждого задания будет даваться от 1 до 2 недель. В некоторых заданиях будут бонусные пункты.

**Даты выдачи заданий:** 24 Февраля, 3 Марта, 10 Марта, 24 Марта

### Расписание занятий

| Занятие |    Дата занятия    | Название (Материалы) |
|:-------------:|:-------------:| ----- |
| 1 | 10 февраля | Лекция «Стохастический вариационный вывод» <br> Семинар «Применение SVI на примере масштабируемых тематических моделей» <br> ([блогпост](https://hackmd.io/@asobolev/HJywykf-8) Артема Соболева) |
| 2 | 17 февраля      | Лекция «Дважды стохастический вариационный вывод» <br> Семинар «Дисперсия стохастических градиентов в примерах» |
| 3 | 24 февраля      | Лекция «Байесовские нейронные сети» <br> Семинар «Локальная репараметризация» |
| 4 | 3 марта | Лекция «Вариационный автокодировщик, нормализующие потоки для вариационного вывода» <br> Семинар «Репараметризация, оценки с выборкой по значимости (IWAE)» |
| 5 | 10 марта | Лекция «Методы снижения дисперсии в моделях со скрытыми переменными» <br> Семинар «Методы снижения дисперсии в моделях со скрытыми переменными» |
| 6 | 17 марта | Лекция «Оценка отношения плотностей распределений, применение на примере \alpha-GAN» <br> Семинар «f-GAN» |
| 7 | 24 марта | Лекция «Stochastic softmax» <br> Семинар «Stochastic softmax» |
| 8 | 31 марта | Лекция по последним результатам в области исследования поверхности функции потерь нейросетей <br> Семинар «Deep MCMC» |

 
### Экзамен

### Рекомендуемая литература

1. Murphy K.P. [Machine Learning: A Probabilistic Perspective.](http://www.twirpx.com/file/1347295/) The MIT Press, 2012.
2. Bishop C.M. [Pattern Recognition and Machine Learning.](http://www.twirpx.com/file/146159/) Springer, 2006.
3. Mackay D.J.C. [Information Theory, Inference, and Learning Algorithms.](http://www.inference.phy.cam.ac.uk/mackay/itila/book.html) Cambridge University Press, 2003.
4. Ian Goodfellow and Yoshua Bengio and Aaron Courville [Deep Learning.](http://www.deeplearningbook.org/) MIT Press, 2016.

### Полезные ссылки

[Сайт](http://bayesgroup.ru) группы Байесовских методов.
