 # Распознавание объектов по аудиосигналу

Этот проект реализует систему классификации звуков с помощью машинного обучения.  

## Функциональность

- Загружает аудиофайл (WAV или MP3).
- Обрабатывает аудио (преобразование в моно, установка частоты дискретизации,  размер выборки).
- Извлекает признаки из аудио (MFCC, спектральный центроид, спектральный спад).
- Предсказывает класс объекта на основе извлеченных признаков.
- Отображает предсказанный класс.

## Требования

- Python 3.7+
- Librosa
- NumPy
- Pandas
- SciPy
- Scikit-learn
- TensorFlow
- Pydub
- Keras
- Gradio

## Установка

1.  Клонируйте репозиторий:
     ```bash
    git clone https://github.com/DiKachura/pattern_recognition_audio.git
     ```
 
2.  Установите зависимости:
     ```bash
    pip install -r requirements.txt
     ```
 
## Запуск

1.  Запустите файл `audio_classifier_gradio.py`:
```bash
    python audio_classifier_gradio.py
```
 
2.  Откройте веб-интерфейс:  Веб-интерфейс Gradio откроется в браузере.  
3.  Загрузите аудиофайл:  Нажмите на кнопку "Загрузить файл"  и  выберите  аудиофайл  (WAV  или  MP3).
4.  Получите предсказание:  На  экране  отобразится  предсказанный  класс.
5.  Также можно записать свой аудиофайл прям из интерфейса, для этого нажмите на значек записи.

##  Автор

Diana Kachura
 
