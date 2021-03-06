#### Проект 7.  Модель предсказаний прибыли компании и выбор прибыльных регионов для разработки нефти

 **Цель исследования** - Необходимо предсказать локацию для бурения нефтяной скважины. Для анализа представлены данные по трем регионам.

 **Задачи** :
 
	1. Предобработка данных.
	2. Обучить модели на данных из трех регионов.
	3. Подготовить функцию для расчета прибыли по значениям предсказаний.
	4. Подсчитать риски и прибыль для каждого региона.
	
 **Инструменты анализа** - `pandas`, `numpy`, `matplotlib`, `scipy`, `sklearn`.
 
 **Краткие выводы**:
 
	1. Были обучены модели на данных из трех регионов, расчитаны метрики качества предсказаний и 
	срдние значения объемов добычи.
	2. Расчитан риск убытков для каждого региона.
	3. Выбран регион добычи, исходя из низких рисков убытков и величины вероятной прибыли.