# Lab3 - датасет MNIST  
### 1) Полносвязная нейронная сеть ( Fully-Connected Neural Network)
* Для полносвязного слоя реализуйте прямой проход  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/21e45191-527e-4db7-84cb-64da59e45a22)
* Для полносвязного слоя реализуйте обратный проход  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/20175254-f036-475e-9809-20059674ed6c)
* Реализуйте прямой проход для слоя активации ReLU  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/d3563122-2213-4062-8492-9a7ff4f8aaf5)
* Реализуйте обратный проход для слоя активации ReLU  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/420488c5-ea95-4b2d-b59c-5e86c3cd1014)
* Реализуйте двухслойную полносвязную сеть - класс TwoLayerNet. Проверьте свою реализацию, запустив код ниже.  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/89873495-4195-48c6-a168-7d6968c89fa1)
* Ознакомьтесь с API для обучения и тестирования моделей. Используйте экземпляр класса Solver для обучения двухслойной полносвязной сети. Необходимо достичь минимум 50% верно классифицированных объектов на валидационном наборе.  
 ![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/ef92e554-3942-4b4e-9cee-9c7e30339bfa)
* Реализуйте полносвязную сеть с произвольным числом скрытых слоев - класс FullyConnectedNet.
* Реализуйте sgd_momentum  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/2c0469af-750f-4767-bc25-04ac85c767fe)
* Сравните результаты обучения шестислойной сети, обученной классическим градиентным спуском и адаптивным алгоритмом с импульсом.  
  ![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/efe594b5-8021-4f77-b120-cf1f9cad7d28)
* Реализуйте алгоритмы RMSProp and Adam с коррекцией смещения  
  ![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/acc136ac-e557-4786-83ff-7e355a61f569)
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/96e7f9e9-460d-4168-b5b3-0a199302ea29)
* Обучите пару глубоких сетей с испольованием RMSProp и Adam алгоритмов обновления весов  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/50c60d9a-f597-41e8-afbf-de71383d4c68)
* Получите лучшую полносвязную сеть для классификации вашего набора   
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/7ad0c043-e51a-4e47-92fb-90c5bb4bafcd)

### 2) Нормализация по мини-батчам (Batch normalization)
* Реализуйте прямой проход для слоя батч-нормализации  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/2f41b0f7-1161-4901-8ca1-ee49c4c76ca9)
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/5372fc03-1817-4cdc-b0db-9643a3627e31)
* Реализуйте обратный проход  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/34d5817e-38c3-4672-aaf2-d0fb68e53403)
* Измените реализацию класса FullyConnectedNet, добавив батч-нормализацию.
* Обучите 6-ти слойную сеть на наборе из 1000 изображений с батч-нормализацией и без нее. Визуализируйте процесс обучения для двух сетей.  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/d8766359-0222-4bf8-818d-84179dd04fd7)
* Обучите 6-тислойную сеть с батч-нормализацией и без нее, используя разные размеры батча.  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/73452973-548b-49b9-bf44-5ab956e77d15)
### 3) Dropout
* Реализуйте прямой проход для dropout-слоя  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/140c5400-3808-4513-9b0f-1dc568a5f209)
* Реализуйте обратный проход для dropout-слоя  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/42f290f5-a62e-4324-b6bd-fbe0630f92eb)
* Добавьте в реализацию класса FullyConnectedNet поддержку dropout
* Обучите две двухслойные сети с dropout-слоем (вероятность отсева 0,25) и без на наборе из 500 изображений. Визуализируйте графики обучения.  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/3c041ed4-7596-4014-9424-f64e3c22508a)
### 4) Сверточные нейронные сети (Convolutional Networks)
* Реализуйте прямой проход для сверточного слоя  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/f04ea6a5-363e-4125-9f3d-42ba4014cab0)
* Реализуйте обратный проход  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/9ab697b6-ca33-4400-962e-ba3124fb3af9)
* Реализуйте прямой проход для max-pooling слоя  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/d75d40e5-5f0f-4006-8537-6da6e8a598f8)
* Реализуйте обратный проход для max-pooling слоя  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/4cfed32f-92a6-440b-9847-e694e3a91c5f)
* Напишите реализацию класса ThreeLayerConvNet
* Попробуйте добиться эффекта переобучения. Обучите модель на небольшом наборе данных.  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/e363187a-156d-417f-b4e0-ba2a8f26a885)
* Обучите сеть на полном наборе данных  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/9408436c-d1c7-4c43-bbac-04bcff19fd36)
* Визуализируйте фильтры на первом слое обученной сети  
![image](https://github.com/last-shadow-I/DL_2023/assets/91950488/484e7a5c-d972-4660-a380-2421dd2b07ab)
