# CV-project
final project

for testing, just run MTCNN/MTCNN.py, you can change the image to test by changing image number in line 161

for training, before run the following, create ccpd_train and ccpd_val in data_set
  MTCNN/data_set/preprocess.py
  
  MTCNN/data_preprocessing/gen_Pnet_train_data.py
  
  MTCNN/data_preprocessing/assemble_Pnet_imglist.py
  
  MTCNN/train/Train_Pnet.py
  
  MTCNN/data_preprocessing/gen_Onet_train_data.py'
  
  MTCNN/data_preprocessing/assemble_Onet_imglist.py
  
  MTCNN/train/Train_Onet.py
  
  MTCNN/MTCNN.py
