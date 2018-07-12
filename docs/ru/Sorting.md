---
title: Сортировка
---

# Сортировка

Область в ClosedXML.Report можно сортировать по столбцам. Это выполняется с помощью тэга столбца `<<sort>>` в служебной ячейке нужных столбцов. 

![tlists1_sort](../../images/sorting-01.png)

Вы можете включить сортировку по убыванию, дописав к тэгу параметр desc (`<<sort desc>>`). В готовом отчете вы обнаружите после этого сортировку по убыванию. 

![tlists1_sort_desc](../../images/sorting-02.png)

Также вы можете указать порядок сортировки столбцов используя параметр num (`<<sort num=2>>`). В следующем примере область будет отсортирована сначала по столбцу Payment Method, а затем по столбцу Ship Date по убыванию.

![tlists1_sort_num xlsx](../../images/sorting-03.png)

Сортировка в ClosedXML.Report имеет ограничение: все данные должны быть расположены в одной строке, включая формулы полей и обычные формулы Excel, но это ограничение не должно быть проблемой, т.к. вы можете отсортировать данные перед тем как отдать их в ClosedXML.Report.