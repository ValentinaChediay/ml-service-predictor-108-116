# Классификационная модель услуг 108 и 116

## Назначение

Модуль предназначен для обучения модели, определяющей вероятность предоставления услуг 108 и 116.

## Описание

Модуль содержит две реализации процесса обучения:
- обучение с использованием TensorFlow и сохранение в формате ONNX
- обучение с использованием scikit-learn и сохранение в формате ONNX


### Технологии
* Python 3.8
* Language: Python

### Сборка модуля
Должен быть установлен Python 3.8.

```shell
git clone https://github.com/ValentinaChediay/ml-service-predictor-108-116.git
cd ml-service-predictor-108-116
1. Создание виртуального окружения
python -m venv venv
2. Активация виртуального окружения
.\venv\Scripts\Activate
3. Установка зависимостей
pip install -r requirements.txt
4. Установка правильной версии typing-extensions для запуска jupyter
pip uninstall typing-extensions
pip install typing-extensions==4.1.1
```