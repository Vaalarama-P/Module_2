# Module_2

Цель проекта научится подготавливать "сырые" данные для дальнейшего построения модели, которая помогала бы предсказывать ключевое значение.
Задача проекта заключалась в том, чтобы провести анализ EDA для данных об учениках одной из школ, для построения дальнейшей модели предсказывания оценки очеников.

В данных были представлена база со значениями: 'school','sex','age','address','famsize','pstatus','medu','fedu','mjob','fjob','reason','guardian','traveltime','studytime','failures','schoolsup','famsup','paid','activities','nursery', 'higher','internet','romantic','famrel','freetime','goout','health','absences','score'
Ключевым значением является столбец score, по отношению к которому были произведены корреляуионный анализ числовых столбцов и анализ номинативных переменных.

Этапы работы:
- Был произвеен анализ числовых столбцов, выявлены выбросы, построены гистрограмы и проведен корреляционный анализ к параметру score.
- Сделаны предварительные выводы по числовым столбцам. Для дальнейшей работы по модели были выбраны положительно коррелирующие с score столбцы medu, fedu, studytime
- Был произвеен анализ номинативных столбцов, выявлены пустые поля, которые были заполнены наиболее часто встречающимися значениями в этом столбце.
- Сделано распределение номинативных переменных в зависимости от значения score с попмщью boxplot
- Проведен тест Стьюдента для номинативных значений. Выявлено 4 наиболее отличающихся колонки sex,  address, higher и  romantic
- С помощью логического анализа добавлены еще 2 колонки schoolsup, internet
- Подготовлен DataFrame с выбраными столбцами
- Сделаны выводы

Саморефлексия:
Доволен проведенныой работой. Сперва было сложно понять логику выполняемых действий, но к концу выполнения проекта картинка начала складываться в целостное понимание - зачем проводится такой объемный кусок работы. В итоге научился распозновать значимые и не важные параметры для дальнейшей модели и теперь жду следующего блока, чтобы научится пользоваться этими данными по назначению.
В следующем модуле уделю больше внимания факультативному обучению. Не всегда хватает информации полученной в модуле. В частности не всегда понятна информация и до конца осознать происходящее помогают сторонние сайты.
Считаю, что прохождение этого модуля поставило еще один кирпич в фундамент здания, построив которое я буду точно понимать как работать с анализом данных и создавать думающие программы.
