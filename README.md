# hse_hw1_meth

## Ссылки на коллаб ноутбуки:
### Анализ QC прочтений
https://colab.research.google.com/drive/14wsBi2EBHxo7xqxMqm37T7CINXbXhw_k#scrollTo=LclK2iCTDdue
### Работа с bam-files с выравниваниями BS-seq ридов на 11-ю хромосому мыши:
https://colab.research.google.com/drive/1sT-MTtJBfPaFhYk_RtUM9JB003HyUgBg?hl=ru

## Анализ QC прочтений
Мною был выбран образец 8cell. Изучив полученные данные я сделал вывод, что результат вполне логичен. Метилированные цитозины - остаются неизменными, в то время как неметилированные цитозины при данном секвенировании превращаются в урацилы ( комплементарные тиминам). Уровень метилирования небольшой, следовательно, уровень неизменных цитозинов будет низким, а количество тиминов возрастет.
Также можно заметить, что из-за небольшого уровня метилирования происходит смещение содержания GC в сторону меньших значений. Следовательно, идет снижение содержания цитозинов.
