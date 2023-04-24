# CE-888
Stress-Predict Dataset

The goal of this research is to create a dataset that can predict stress and then analyze the collected biophysiological data from healthy individuals who were subjected to various emotional states. The aim is to evaluate how effective the common indicators of stress are in identifying stress and to develop a device that can monitor stress levels with accuracy. The study involved 35 healthy volunteers who underwent three different tasks that induced stress, namely the Stroop color word test, interview session, and hyperventilation session. The tasks were conducted over a period of 60 minutes, with a relaxation period in-between. During the tasks, Empatica watches were used to continuously monitor blood volume pulse (BVP), inter-beat intervals, and heart rate, while a PPG-based respiratory rate estimation algorithm was used to estimate the respiratory rate. The collected data was then subjected to descriptive, statistical, and classification analysis. This research aims to serve as a foundation for the development of a reliable stress monitoring device.
Dataset Files
|-- Processed_data
|-----	heartrate_resprate_timestamps_labels folder
	|-----	Improved_Combined_hr_rsp_binary_PX.csv (contain information of heart rates and respiratory rates along with timestamps and labels (for nonstress/baseline and 1 for stress task duration). Here X is participant number) 
	|-----	Time_logs.xlsx (contain date and start/end time of each task for each participant, Irish standard time)
|-----	heartrate_timestamps_labels folder
	|-----	PX_comb_binary.csv (contain information of heart rates along with timestamps and labels (for nonstress/baseline and 1 for stress task duration). Here X is participant number) 
|-----	resprrate_timestamps_labels folder
	|-----	Improved_PX_comb_10sec_binary.csv (contain information of respiratory rates along with timestamps and labels (for nonstress/baseline and 1 for stress task duration). Here X is participant number) 
|-----	Improved_All_Combined_hr_rsp_binary.csv (contain information of heart rates and respiratory rates of all the participants along with timestamps and labels (for nonstress/baseline and 1 for stress task duration))
|-----	Questionnaires_scores.xlsx (contains information about the PSS and STAI questionnaire scores of each participant)
|-----	Time_logs.xlsx (contain date and start/end time of each task for each participant, Irish standard time)
|-- Raw_data
|-----	SX folder (folders with raw files from Empatica E4. Where X is participant number)
|-----	ACC.csv (contains accelerometer data (x, y, z axis))
|-----	BVP.csv (contains raw BVP data)
|-----	EDA.csv (contains EDA data (skin conductance))
|-----	HR.csv (contains heart rate data)
|-----	IBI.csv (contains inter-beat-interval data)
|-----	info.txt (contains information about all the csv file and sampling rate)
|-----	tags_SX.csv (contains timestamp tags. start-end time of each task)
|-----	TEMP.csv (contains skin temperature data)
Libraries
Following libraries were used for analysis:
•	Statistical Analysis (Rstudio):
o	tidyverse
o	gtsummary
o	sjPlot
o	knitr
o	nlme
o	tidyr
•	Descriptive Analysis (python):
o	pandas
o	numpy
o	seaborn
o	matplotlib
•	Classification Analysis (python):
o	Numpy
o	Tensorflow
o	Pandas
o	Scikitlearn
o	Scipy
o	Pickle
o	Matplotlib
o	Keras

