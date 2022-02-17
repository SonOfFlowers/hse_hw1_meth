# hse_hw1_meth

## Ссылки на коллаб ноутбуки:
### Анализ QC прочтений
https://colab.research.google.com/drive/14wsBi2EBHxo7xqxMqm37T7CINXbXhw_k#scrollTo=LclK2iCTDdue
### Работа с bam-files с выравниваниями BS-seq ридов на 11-ю хромосому мыши:
https://colab.research.google.com/drive/1sT-MTtJBfPaFhYk_RtUM9JB003HyUgBg?hl=ru

## Анализ QC прочтений
![image](https://user-images.githubusercontent.com/93160309/154544203-d7a99223-65ee-4b30-8ee7-99ea220161bf.png)

![image](https://user-images.githubusercontent.com/93160309/154544328-74fe1b34-b274-4cd0-bfe1-a5d1952b3610.png)

Мною был выбран образец 8cell. Изучив полученные данные я сделал вывод, что результат вполне логичен. Метилированные цитозины - остаются неизменными, в то время как неметилированные цитозины при данном секвенировании превращаются в урацилы ( комплементарные тиминам). Уровень метилирования небольшой, следовательно, уровень неизменных цитозинов будет низким, а количество тиминов возрастет.
Также можно заметить, что из-за небольшого уровня метилирования происходит смещение содержания GC в сторону меньших значений. Следовательно, идет снижение содержания цитозинов.

## Вторая часть, в которой я плакал два дня подряд, из-за беспощадного коллаба (коротко в таблицах и графиках)

### 1. Картирование

![image](https://user-images.githubusercontent.com/93160309/154545833-76aec4a3-197b-4d50-b12c-e90eabad2c70.png)

### 2. Дедупликация

![image](https://user-images.githubusercontent.com/93160309/154546134-2b38a203-489f-472c-b0e8-6dd1699607e5.png)

Дедупликацию делал одновременную. Скрипт в блокноте. 

![image](https://user-images.githubusercontent.com/93160309/154546861-8d974526-5e88-49f6-b372-0d98d9363d71.png)

### 3. Метелирование цитозинов
Коллинг прошёл. Всё обсчитано.

### 4. Работа с M-bias plot
В результате были полученны графики (расположенные ниже по убыванию процента CpG-метилирования). Наименьшая доля  метелирования наблюдается у образца icm (22-24%), а у Epiblast (77-78%) - наибольшая. Образец 8_cell (42-45%) показал средние значения. 

ICM:

![image](https://user-images.githubusercontent.com/93160309/154551449-e425b7c2-4b1e-4171-82d7-a59553aa8840.png)

![image](https://user-images.githubusercontent.com/93160309/154551514-373f6464-5b9f-47f1-a515-3ba4d402a545.png)

Epiblast:

![image](https://user-images.githubusercontent.com/93160309/154551953-7761e7cc-42b7-41e2-bdde-10ea1c24d709.png)

![image](https://user-images.githubusercontent.com/93160309/154552165-d6223bda-79f8-4b06-8e66-18947bb25a09.png)

8cell:

![image](https://user-images.githubusercontent.com/93160309/154552239-0a515114-ddb8-493c-bbda-1f1b037e9958.png)

![image](https://user-images.githubusercontent.com/93160309/154552277-22a844df-e5ae-45f7-8b14-04456d6e8f33.png)











