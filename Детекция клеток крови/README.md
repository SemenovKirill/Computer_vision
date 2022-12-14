# Детекция клеток крови
Решение задачи object detection на датасете BCCD (https://github.com/Shenggan/BCCD_Dataset). На изображениях присутствуют объекты трёх классов:  
 - эритроциты (RBC)
 -  лейкоциты (WBC)
 -  тромбоциты (Platelets)  
Для решения задачи используется модель Single Shot MultiBox Detector, за основу взята вот эта реализация: https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Object-Detection

## Стек используемых инструментов:
 - Pytorch
 - PIL
 - Matplotlib
 - Используемая архитектура - SSD