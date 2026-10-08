# Assessing Full Turning

The aim of this project, developed during my internship, was to automatically extract relevant features from a full turning task using three IMU sensors: one placed on the lower back and one on each foot.

The task consisted of two consecutive 360° turns, performed in opposite directions and the partecipants were .

The main features extracted by the pipeline include:

* duration-related parameters;
* velocity-based parameters;
* number of steps;
* orientation of the two turns.

The input of the pipeline is a folder containing the IMU data files. The files are named according to the trial number, subject ID, and experimental condition, allowing the pipeline to automatically identify and process the different recordings.

The analysis considered the following experimental conditions:

* Medication ON and Medication OFF;
* Single Task and Dual Task.

The dataset used to test the pipeline is **not included in this repository**, in order to protect the privacy of the study participants and prevent the disclosure of personal or sensitive data.

It is also included the subsequent Statistical Analysis wrote in order to study the responsiveness to the change of conditions and to the different scores of the clinical scale used. 
