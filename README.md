# Phase problem
Этот проект является переносом [решения фазовой проблемы](https://github.com/Stergrim/Solving-the-phase-problem) с **Matlab** на **C#** с добавлением графического интерфейса.

## Каталоги
>**Graph3D**: сторонний проект для 3D отрисовки поверхности <br>
>**Phase-problem-main**: папка основного проекта <br>
>**Release**: сборка решения в виде exe файла <br>
>**demos**: графический материал для README <br>

## Этапы
Этапы, описанные ниже, соответствуют [примеру запуска решения фазовой проблемы](https://github.com/Stergrim/Solving-the-phase-problem/tree/main/demos#readme): <br>
этап №1 – 1, 2, 3 пункты; <br>
этап №2 – 4 пункт; <br>
этап №3 – 5, 6 пункты. <br>

### **Этап №1 (…)**
1. Расчёт полиномов Цернике **(+)**
2. Формирование волнового фронта **(+)**
3. Визуализация волнового фронта **(+)**
4. Пользовательский интерфейс **(+)**
5. Рефакторинг кода **(…)**

**Результаты:** <br>
***Главное окно приложения***
 
<figure>
<img src="https://github.com/Stergrim/Phase-problem/blob/master/demos/MainWindow.jpg" width="600"/>
</figure>

***Окно для определения коэффицинтов Цернике***

<figure>
<img src="https://github.com/Stergrim/Phase-problem/blob/master/demos/SetWindow.jpg" width="450"/>
</figure>

### **Этап №2 (…)**
1. Расчёт распределения интенсивности **(…)**
2. Визуализация в виде двумерного изображения **(…)**
3. Добавление в основную форму вкладки с изображением картины распределения интенсивности и вкладки с задаваемыми параметрами **(…)**

### **Этап №3 (…)**
1. Реализация метода оптимизации многомерной функции **(…)**
2. Визуализация результатов в отдельной вкладке основного окна **(…)**
