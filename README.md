# Тестовое задание для летней школы Macroscop

Цель:
Реализовать автоматическое наложение очков на лица на основании
ключевых точек (лэндмарок), используя средства созданного
окружения.
### Файлы
Ссылка на данные: [MacroscopTest.zip](<https://drive.google.com/file/d/1Y8rReI2ErrpRwVVfST-joX-wfR-WfuN1/view>)

Список файлов:
* images - директория с фотографиями
* annotations.txt - файл с аннотациями ко всем фотографиям
* glasses.png - модель очков в формате RGBA
* Test.ipynb - выполненное тестовое задание построенное на предложенной организаторвами заготовке
* Template.ipynb - заготовка для задания от организаторов

### Формат аннотации:
* filename 
* upper_face_corner_x 
* upper_face_corner_y 
* bottom_face_corner_x
* bottom_face_corner_y 
* left_eye_x 
* left_eye_y 
* right_eye_x 
* right_eye_y 
* nose_x
* nose_y 
* left_mouth_x 
* left_mouth_y 
* right_mouth_x 
* right_mouth_y.

Координаты левого верхнего и правого нижнего углов описывающего
прямоугольника заданы относительно изображения (от 0 до 1).
Координаты лэндмарок - относительно описывающего прямоугольника:
