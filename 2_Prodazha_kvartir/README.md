# __Цель проекта__

#### Нам предоставлены данные сервиса Яндекс.Недвижимость — данные из объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. В рамках проекта определяем зависимость рыночной стоимости объектов недвижимости от различных параметров. Это позволит построить автоматизированную систему, которая отследит аномалии и мошенническую деятельность.По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

# __Выводы__

#### 1. В результате выполнения проекта проведен анализ данных сервиса Яндекс.Недвижимость.  Определены зависимости рыночной стоимости объектов недвижимости от различных параметров. Наиболее существенное влияние на стоимость жилого помещения оказывают его площадь, количество комнат, этаж, удаленность от центра. 
#### 2. Время размещения объявления не влияет (день недели, месяц) на скорость продажи квартиры. С годами цены на квартиры изменяются в зависимости от экономической ситуации в стране. Также определены редкие и выбивающиеся значения в полях 'rooms', 'last_price', 'ceiling_height', 'total_area'. Строки с такими значениями удалены из набора данных для исключения влияния частных объявлений на статистику по остальным значениям. 
#### 3. Проведен отдельный анализ и определение "ценрального района" (радиус в км от географического центра). Характерные особенности главным образом не отличаются от остальных районов, однако средняя стоимость и качество квартир в нем выше (кол-во комнат, высота потолков, общая площадь).
