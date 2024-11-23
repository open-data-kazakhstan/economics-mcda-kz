# Қазақстан аймақтарының кірістері мен шығындары туралы деректер

Бұл репозиторийде Қазақстанның аймақтары бойынша **тұрғындардың тұтыну шығындары** мен **кірістері** туралы деректер бар. Датасет әрбір аймақтың әлеуметтік-экономикалық жағдайын талдауға және әртүрлі статистикалық немесе экономикалық модельдер құруға арналған.

## 📄 Датасет сипаттамасы

### Бағандар:
- **Регионы** – Қазақстанның аймақтарының атаулары.
- **Потребительские_расходы** – Жалпы тұтыну шығындары (барлық шығындардың салыстырмалы үлесі).
- **Продовольственные_товары** – Азық-түлік тауарларына жұмсалған шығындар үлесі.
- **Непродовольственные_товары** – Азық-түлік емес тауарларға жұмсалған шығындар үлесі.
- **Платные_услуги** – Ақылы қызметтерге жұмсалған шығындар үлесі.
- **Материальная_помощь_родственникам_и_знакомым_алименты** – Туыстар мен таныстарға материалдық көмекке жұмсалған қаржы.
- **Налоги_платежи_и_другие_выплаты** – Салықтар, төлемдер және басқа да міндетті төлемдер.
- **Погашение_кредита_и_долга** – Несие және қарыздарды өтеуге жұмсалған қаржы.
- **Доход_от_трудовой_деятельности** – Еңбек қызметінен алынған кірістердің жалпы үлесі.
- **Доход_от_работы_по_найму** – Жұмыспен қамтылған қызметкерлердің кірісі.
- **Доход_от_самостоятельной_занятости_и_предпринимательства** – Жеке кәсіпкерлік пен өзін-өзі жұмыспен қамтудан түскен кіріс.
- **Пенсии** – Зейнетақы кірісі.
- **Пособия** – Әлеуметтік жәрдемақылар.
- **АСП_и_жилищная_помощь** – АСП (адресная социальная помощь) және тұрғын үйге көрсетілетін көмек.
- **Стипендия** – Стипендиялардан алынған кірістер.
- **Матеральная_помощь_от_родственников_и_знакомых_алименты** – Туыстар мен таныстардан алынған материалдық көмек және алименттер.
- **Доходы_от_собственности** – Меншік нысандарынан түскен кірістер.
- **Прочие_доходы** – Басқа кіріс көздері.
- **Доля_безработицы_на_населения** – Аймақтағы халықтың жұмыссыздық деңгейінің үлесі.

## 🛠 Қолдану

Бұл датасет келесі мақсаттарда қолданылуы мүмкін:
- Әлеуметтік-экономикалық айырмашылықтарды талдау.
- Аймақтардың кіріс пен шығыс құрылымын салыстыру.
- Экономикалық немесе статистикалық модельдер құру.

# 📊 График нормализованных данных

Ниже представлен график для данных, хранящихся в файле `normalized_data.csv`. Этот файл содержит нормализованные значения, где каждый показатель находится в диапазоне от 0 до 1.

### Визуализация:

<LineChart data={{ url: 'datasets/normalized_data.csv' }} title="Нормализованные значения" xAxis="Показатели" yAxis="Нормализованное значение" />

## 🗂️ [city_population.csv](datasets/city_population.md)


