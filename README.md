# researchMethod
The project is responsible for SA detection. If u need to run program please ensure the below package installed.

Python 3.8.8 (default, Apr 13 2021, 19:58:26)
GCC 7.3.0
Keras 2.4.0
tensorflow 2.3.0

If you have any query about running this program, please contact zixian.zhang21@student.xjtlu.edu.cn

Next is some notes about each step of this programe.

1) preprocessing.py: responsible for feature extraction
	If you need to run this preprocssing.py, you need to download data from https://physionet.org/physiobank/database/apnea-ecg/ and put the details file to dataset directory in this project.(Data is too big to carry)


2) training.py: responsible for model training


3)pre-training.py: responsible  for fitting model
	

please run preprocessing.py first to get clean data package. Then run training.py to get model. Fianlly run pre-training.py to get result.
