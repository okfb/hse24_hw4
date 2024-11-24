# hse24_hw4 Illeritskiy
## КОД
Код был выполнен в wsl локально, см папку src

## Часть 1
### MultiQC
![image](https://github.com/user-attachments/assets/9e0343fe-e597-4787-b7f3-d05a8bcc3e82)
![image](https://github.com/user-attachments/assets/d7e1bcba-bb1c-43ee-a52a-94e1fb5b58cf)
![image](https://github.com/user-attachments/assets/c5a272f1-3458-42bb-b368-e37e614765eb)
![image](https://github.com/user-attachments/assets/37121f50-7094-45dd-b10c-be4289a8808d)
![image](https://github.com/user-attachments/assets/11a840b0-6d57-4ca9-bbd4-d1a79f8dfd1f)
![image](https://github.com/user-attachments/assets/5ccd6eb2-5993-4ef3-82b6-e8108e47c368)
![image](https://github.com/user-attachments/assets/b732b5d1-c999-4787-8290-b7d9f70a31c3)
![image](https://github.com/user-attachments/assets/a211a1bc-cf61-47c8-a15f-11442f5cf1f3)

### Таблица по образцам  
| ID | Тип | Общее число исходных чтений | Число и процент успешно откартированных чтений (не уникальные) | Число и процент успешно откартированных чтений (уникальные) | Общее число чтений, попавших на гены |
|----------|:----------:|:----------------:|:----------------:|:----------------:|:----------------:|
| **SRR3414635** | контрольный | 20956475  | 20715476, 98.85% | 18637053, 87.1% | 16463013 |
| **SRR3414636** | контрольный | 20307147  | 20073615, 98.85% | 18032679, 86.5% | 15942667 |
| **SRR3414637** | контрольный | 20385570  | 20149097, 98.84% | 18043406, 86.3% | 15914380 |
| **SRR3414629** | перепрограммированный | 21106089  | 20863369, 98.86% | 18573565, 88.0% | 16224313 |
| **SRR3414630** | перепрограммированный | 15244711  | 15077019, 98.90% | 13320505, 87.8% | 11583775 |
| **SRR3414631** | перепрограммированный | 24244069  | 23965262, 98.85% | 21159606, 87.5% | 18613501 |

## Часть 2
### MA-plot
![image](https://github.com/user-attachments/assets/2ece1916-25f2-4c40-af2f-a53491c9b5c3)

### Heatmap
![image](https://github.com/user-attachments/assets/81fb7e97-7667-4d68-a543-8cf764c87c99)

### Heatmap 20 most
![image](https://github.com/user-attachments/assets/1890f612-1fd8-4fe8-9a7d-77fdf9246718)

### Ищем гены поменявшие экспрессию

![image](https://github.com/user-attachments/assets/df6343ab-6eb6-4230-b0b4-85abb8ef6ce9)

![image](https://github.com/user-attachments/assets/93d4c831-614f-469e-840d-85bade83b406)

![image](https://github.com/user-attachments/assets/16a26cd3-a471-4f38-a62e-a840b8b397b7)

Можно наблюдать большой разброс по количеству чтений между контрольными и перепрограммированными образцами -> нашли гены  поменяввшие экспрессию
