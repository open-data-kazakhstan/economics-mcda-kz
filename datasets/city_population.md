# 🗂️ `city_population.csv`

## Сипаттама
Бұл деректер жинағы Қазақстанның әр өңіріндегі халық саны туралы ақпаратты қамтиды. Әрбір өңір үшін жалпы халық саны, ерлер және әйелдер саны көрсетілген.  

| Баған атауы    | Сипаттама                                   |
|----------------|---------------------------------------------|
| `Region`       | Өңірдің атауы                               |
| `Total`        | Жалпы халық саны                            |
| `Males`        | Ерлер саны                                  |
| `Females`      | Әйелдер саны                                |

## Деректер үлгісі
| Region                      | Total     | Males    | Females  |
|-----------------------------|-----------|----------|----------|
| Abai Region                 | 610189    | 298770   | 311419   |
| Akmola Region               | 787971    | 385124   | 402847   |
| Aktobe Region               | 928185    | 455105   | 473080   |
| Almaty Region               | 1505984   | 752422   | 753562   |
| Atyrau Region               | 693040    | 342146   | 350894   |

## Құрылым
Файл 20 өңірдің және Қазақстан Республикасының жалпы халық саны туралы деректерді қамтиды. Барлық мәндер сандық деректер ретінде ұсынылған. 

### Өңірлердің толық тізімі:
1. Abai Region  
2. Akmola Region  
3. Aktobe Region  
4. Almaty Region  
5. Atyrau Region  
6. West Kazakhstan Region  
7. Jambyl Region  
8. Jetisu Region  
9. Karaganda Region  
10. Kostanay Region  
11. Kyzylorda Region  
12. Mangystau Region  
13. Pavlodar Region  
14. North Kazakhstan Region  
15. Turkistan Region  
16. Ulytau Region  
17. East Kazakhstan Region  
18. Astana city  
19. Almaty city  
20. Shymkent city  
21. The Republic of Kazakhstan (жалпы деректер)

## Деректерді пайдалану
Бұл деректерді талдау немесе Қазақстан өңірлерінің халық саны туралы визуализация жасау үшін қолдануға болады.

### Мысалы:
```python
import pandas as pd

# Деректерді жүктеу
data = pd.read_csv('city_population.csv')

# Жалпы халық саны бойынша алғашқы 5 өңірді көрсету
top_regions = data.sort_values(by='Total', ascending=False).head(5)
print(top_regions)
