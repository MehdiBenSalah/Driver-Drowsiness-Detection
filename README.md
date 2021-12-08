# Driver-Drowsiness-Detection and speech recognition </br>
When the driver's eyes remain closed for a certain time, an alarm is triggered. The driver must open his eyes and say a word generated </br>
randomly by the system to stop the alarm after ensuring the driver's awareness and vigilance. </br>
We have used : </br>
</br>
- dlib to detect some points of the eyes (landmarks) to compute a ratio (EAR: Eye Aspect Ratio) which allows to know if the eyes are closed </br>
- OpenCV to manipulate the videos</br>
- SpeechRecognition for voice recognition and transforming voice into text</br>
- the Concurrent.future module to ensure asynchronous execution of the alarm and voice recognition</br>
