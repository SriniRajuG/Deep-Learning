# Deep-Learning

### Distracted Driver Detection

![DDD](https://storage.googleapis.com/kaggle-competitions/kaggle/5048/media/drivers_statefarm.png)

In this project we have images taken inside a car with a driver doing an activity (texting, eating, talking on the phone, makeup, reaching behind, etc) while driving. Aim of the project is to predict the likelihood of what the driver is doing in each picture. 
The 10 classes to predict are:

 *   c0: safe driving
 *   c1: texting - right
 *   c2: talking on the phone - right
 *   c3: texting - left
 *   c4: talking on the phone - left
 *   c5: operating the radio
 *   c6: drinking
 *   c7: reaching behind
 *   c8: hair and makeup
 *   c9: talking to passenger

### Time series Classification using CNN and Scalograms

In this project, I built a predictive maintenance solution by identifying faults in rolling element bearings. Converted a large time series data into multiple images using short-time Fourier transform and continuous wavelet transform. Used convolutional neural networks to classify images into 4 classes of defects to identify the point in time when the fault occured.

References:
* https://www.hindawi.com/journals/sv/2017/5067651/
* https://www.mathworks.com/help/wavelet/examples/classify-time-series-using-wavelet-analysis-and-deep-learning.html;jsessionid=af03afa362b6cd7405332813218f
* https://www.isca-speech.org/archive/Interspeech_2018/pdfs/1524.pdf

### Time Series Forecasting using LSTM

Generated a sine wave and used synced many-to-many LSTM http://karpathy.github.io/2015/05/21/rnn-effectiveness/ for forecasting.
