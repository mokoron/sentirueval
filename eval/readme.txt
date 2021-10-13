В архивах twit-calc-osx.zip и twit-calc-Win64.zip находятся скрипты для оценки задачи классификации твитов. В архивах сборки под соответствующие операционные системы.

Запуск: node calc.js <type> result.xml etalon.xml
Выбираем type: ttk или bank

Например, есть файл с ответами системы по твитам телекоммуникационным компаниям: my_result_ttk.xml и эталонный файл ttk_test_etalon.xml
node calc.js ttk my_result_ttk.xml ttk_test_etalon.xml

Система выдаст результат в виде подсчета TP, TN, FP, FN для положительного и отрицательного классов; Precision, Recall и F-measure по каждому из классов и общую F-measure (макроусреднение)

