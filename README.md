### *Jmeter - HW_1 Сделать сценарий с перечисленными эндпоинтами*
_________________________
Дать нагрузку на (50)[https://github.com/EvgeneyKEO/JMETER/blob/main/Summary_report_Users_50.csv], (250)[https://github.com/EvgeneyKEO/JMETER/blob/16fe632011b53684c49c048eb46800823581604d/Summary_report_Users_250.csv], (500)[https://github.com/EvgeneyKEO/JMETER/blob/16fe632011b53684c49c048eb46800823581604d/Summary_report_Users_500.csv] потоков.
Результаты прогонов выг1рузить в CSV.
Настройки Jmeter, файл .jmx выгружаем на гит.
_________________________

1) http://162.55.220.72:5005/get_method
```
req.
GET
name: str
age: int
```

2) http://162.55.220.72:5005/user_info_2
```
req.
POST
name: str
age: int
salary: int
```

3) http://162.55.220.72:5005/user_info_3
```
req.
POST
name: str
age: int
salary: int
```

4) http://162.55.220.72:5005/object_info_1
```
req.
GET
name: str
age: int
weight: int
```

5) http://162.55.220.72:5005/object_info_2
```
req.
GET
name: str
age: int
salary: int
```

6) http://162.55.220.72:5005/object_info_3
```
req.
GET
name: str
age: int
salary: int
```

7) http://162.55.220.72:5005/object_info_4
```
req.
GET
name: str
age: int
salary: int
```
