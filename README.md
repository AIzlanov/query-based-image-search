# Query Based Image Search — Документация

## Описание проекта
В рамках этого проекта мне поручено разработать демонстрационную версию поиска изображений по запросу.

Для демонстрационной версии нужно обучить модель, которая получит векторное представление изображения и текста,   
а на выходе выдаст число от 0 до 1, которое покажет насколько текст и картинка подходят друг другу.   

## Структура проекта
query-based-image-search/  
│  
├── data/  
|   └── train_images/*.jpg  
|   └── test_images/*.jpg  
│   └── CrowdAnnotations.tsv    
│   └── ExpertAnnotations.tsv    
│   └── train_dataset.csv    
│   └── test_queries.csv   
│   └── test_images.csv   
│   
├── requirements.txt (список необходимых библиотек)  
├── query-based-image-search.ipynb (тетрадка с проектом)  
└── README.md  (описание проекта)                                       

## Установка
0. [Скачать файлы](https://code.s3.yandex.net/datasets/dsplus_integrated_project_4.zip)  

1. Клонирование проекта  
```bash
git clone https://github.com/AIzlanov/query-based-image-search.git
```    

3. Установка зависимостей
```bash
pip install -r requirements.txt
```

## Заключение
В рамках этого проекта были реализованы следующий шаги:   
- разработана модель для поиска наиболее близкого фото по текстовому запросу 
- написана техническая документация   