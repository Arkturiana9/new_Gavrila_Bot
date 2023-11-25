# new_Gavrila_Bot
#Телеграм-бот  «Gavrila» представляет собой информационный ресурс, предоставляющий пользователю следующие возможности:
#1) чат с LLM - llama-7B-hf (на английском и русском языках) взято с https://huggingface.co/baffo32/decapoda-research-llama-7B-hf
#2)чат с chatgpt 3.5 (используется api сайта (https://ask.chadgpt.ru/))
#3)предсказание температуры воздуха в Москве с выводом графика (интервал прогнозирования с 11.11.2023 до 09.01.2024г.) 
Сами спрогнозированные значения температуры находятся здесь:
#https://drive.google.com/file/d/15Yxkm93tTsgStHPcUU2W5W_yv3GQyuDI/view?usp=sharing
#4)Вывод значений температуры воздуха в любом городе на текущую дату (используется api сайта openweathermap.org)

СОДЕРЖИМОЕ ПАПОК

Папка CSV - содержит спрогнозированные значения температуры в Москве от 4-х различных моделей на период с 11.11.023г. по 09.01.2024г.
df_all.csv  -  результаты прогноза всех 4-х моделей
df_fourier.csv  - прогноз с помощью ряда Фурье
df_lstm.csv - прогноз от LSTM
df_mean.csv - прогноз методом средних значений
df_prophet.csv - прогноз от Prophet
moscow_1975_2023_ok.csv - временной ряд для которого строился прогноз


Папка research - содержит 4 Jupyter Notebook с результатами исследований
1Forecast_df_all.ipynb  -  результаты прогноза всех 4-х моделей на период с 11.11.2023 по 09.01.2024г.
1forecast_Fourier_series_mean.ipynb  - прогноз с помощью ряда Фурье и прогноз методом средних значений
1Forecast_LSTM_Moscow_75_2023.ipynb - прогноз от LSTM
1Forecast_sarima_prophet_Moscow_75_2023.ipynb - прогноз от Prophet


Папка description - содержит описание проекта и презентацию проекта










