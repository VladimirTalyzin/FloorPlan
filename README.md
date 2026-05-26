# FloorPlan
Сегментация планов помещений / Segmentation of the floor plan

![Segmentation of the floor plan](https://0v.ru/floor-plan/floor-plan-segmentation.png)

* **prepare-512.ipynb** - подготовка масок и разбиение их на кусочки 512х512.
* **FloorPlan-resnext101.ipynb** - обучение моделей и получение решения.


**Готовые обученные модели:**
* **Стены** https://0v.ru/floor-plan/models-resnext101-wall.zip
* **Окна** https://0v.ru/floor-plan/models-resnext101-window.zip
* **Двери** https://0v.ru/floor-plan/models-resnext101-door.zip

Формат моделей: cktp "Checkpoint"


**Зависимости:**

* pip install keras
* pip install tensorflow
* pip install albumentations
* pip install segmentation-models
* pip install numpy
* pip install scikit-learn
* pip install Pillow
* pip install tqdm
