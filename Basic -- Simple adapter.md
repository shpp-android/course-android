# Адаптер для списков
В мобильных приложениях часто нужно отобразить список каких-либо значений. 
Значений может быть очень большое количество и возникает вопрос, как оптимизировать вывод на экран, ведь классический способ отображения -- 
когда для каждого элемента создается отдельный экземплят класса отображения в памяти. 
Например, если использовать классический способ, то для отображения 1000 текстовых элементов нужно было бы создать 
1000 экземпляров TextView и добавить их на LinearLayout или RelativeLayout.
