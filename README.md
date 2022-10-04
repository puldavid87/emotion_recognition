# EMOTION RECOGNITION BASED ON SENSORS AND ML

Human-computer interaction plays a fundamental role in training machine learning models since computers can learn from human behavior. Therefore, this task can be done by cameras and sensors. However, in some scenarios, cameras need a controlled environment to take good-quality pictures and extract patterns from the muscles of the face. Consequently, sensors are a flexible solution in rough applications when humans constantly move or their emotions have weak muscle contractions. In this IoT application,  electromyography sensors are allocated to the human face to recognize the six primary emotions: happiness, anger, surprise, fear, sadness, and disgust. 

## DATASET: 

Two EMG channels sensor is located in the Corrugator Supercilii in the forehead's upper part of the eyebrow. This is the primary muscle over the negative emotions of sadness, anger, and disgust (1). Another sensor is allocated in the Zygomaticus major, the muscle located in the cheek near the mouth. This muscle has a high activity on emotions of happiness, fear, and surprise (2). Finally, the last sensor collects data from the Depressor Anuguli Oris, which is in the lower part of the mouth towards the jaw, acting mainly on the emotions of surprise, happiness, and sadness (3). 

## BACKGROUND:

- **Facial muscles:** The facial muscles are the fibers (elastic tissue) that support sensory organs to perform their activities. For example, chewing, smelling, hearing, or listening. Motor neurons carry out this process by giving instructions to muscles by electrical pulses to maintain muscle contraction. This electrical activity is called motor unit action potential (MUAP), representing the duration, electrical amplitude, and phases of muscle contraction. Typical MUAP duration is between 5 and 15 ms. In this scenario, the facial muscles are divided into three: (1) the top group, which generates eyebrow movement, frowning mainly to allow eye-opening; (2) the middle group, closely involved with mouth movements, helps phonation, and some very particular muscles allow chewing; and (3) the bottom group is responsible for generating facial movements due to the lips' soft tissues. 

![EMG](https://github.com/puldavid87/emotion_recognition/blob/main/design_best.png). 
Location of three EMG sensors to collect data. Sensor 1:  Orbicularis oculi and the Corrugator supercilii muscles. Sensor 2:  Zygomaticus major. Sensor 3: Depressor Anguli Oris and Masseter muscles. Green section: top face's muscles. Blue section: middle face's muscles, and Purple section: bottom face's muscles

Therefore, the facial actions coding system ([FACS](https://web.archive.org/web/20110520164252/http://face-and-emotion.com/dataface/facs/description.jsp) indexes the facial expressions in actions units (AU) to match with the biomechanic information obtained in MUAP analysis of EMG signals. Furthermore, this approach aims at splitting the face into individual movements of their specific muscle activation to describe emotions \cite{Lewinski2014}. Therefore, FACS has intensity scoring by appending letters A–E (for minimal-maximal intensity) to the action unit number. Consequently, the target emotions that FACS helps to determine are as follows: surprise, sadness, happiness, anger, disgust, and fear. 

## RESOURCES:

- [Python Code](https://github.com/puldavid87/emotion_recognition/blob/main/emg_data_collection.ipynb)
- [Dataset](https://github.com/puldavid87/emotion_recognition/blob/main/emg_data.csv)
- [Webpage project](https://iot4.paulrosero-montalvo.com/emg/)
- [Article](https://iot4.paulrosero-montalvo.com/gallery/article_emg_draft.pdf)
