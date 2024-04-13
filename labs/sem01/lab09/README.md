# Быстрые сортировки

Лаба: http://cs.mipt.ru/algo/lessons/sem_1/lab10.html


## Визуализации

быстрых сортировок на [примере фотографии Катюши](../lab07).

"Тик" времени — перестановка элементов.

### Quick Sort

<p align="center">
   <a href="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExeG0xcmloZGx0eTJrMGpqOTF6NTlyN3pocHRuNGVjczFqZHJleGQydyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/JqlT8MFakmjDRg2oXV/giphy.gif">
     <img src="./images/gif/panda_quick_unfair_50_lossy_35_width_400.gif" alt="Quick Sort View of Moscow Panda Katyusha" title="Katyusha & Quick Sort" />
   </a>
</p>
<p align="center">
  <em>Пример быстрой сортировки: "быстрая" версия (перестановка "сразу" всех элементов при разбиении по барьеру). Барьер — медиана (не очень честно, зато наглядно, насколько возможно 😅).</em>
</p>

<p align="center">
   <a href="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYjd2ZW1tcmlpcHc1Z2RzY200dm03eHJ0cXpmbmloMzBiMjM3aGpyayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/MKDjeCwc39qEUrviim/giphy.gif">
     <img src="./images/gif/panda_quick_50_lossy_35_width_400.gif" alt="Quick Sort View of Moscow Panda Katyusha" title="Katyusha & Quick Sort" />
   </a>
</p>
<p align="center">
  <em>Пример быстрой сортировки: более "честная" версия (показаны все попарные перестановки при разбиении по барьеру). Барьер — также медиана.</em>
</p>


### Merge Sort

<p align="center">
   <a href="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExc2Q0aW4wbTR0ZTZ1NGJsa3hhZXR0eW82OXlpdW1pY3FhaWdka3pheCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/IDZwawDQ6SFrXboMOE/giphy.gif">
     <img src="./images/gif/panda_merge_inplace1_50_lossy_35_width_400.gif" alt="Merge Sort View of Moscow Panda Katyusha" title="Katyusha & Merge Sort" />
   </a>
</p>
<p align="center">
  <em>Пример сортировки слиянием. Представленная сортировка, в отличие от классической, проходит in-place. Так, что слияние двух частей чем-то похоже на сортировку вставками (для каждого элемента из правой половины ищется место среди элементов левой половины). При этом вставка на нужное место занимает лишь один "тик" времени (чтобы освободить место, несколько элементов сдвигаются вправо одновременно), так чтобы по итогу общее время сортировки в "тиках" как можно меньше отличалось от времени сортировки при классическом слиянии с использованием нового массива.</em>
</p>
