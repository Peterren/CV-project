# CV-project
final project

for testing, just run MTCNN/MTCNN.py, you can change the image to test by changing image number in line 161
  
  If you want to use the final weights that is trained by us, line 176 should be:
  
  bboxes = create_mtcnn_net(image, args.mini_lp, device, p_model_path='weights/pnet_Weights', o_model_path='weights/onet_Weights') 
  
  otherwsie, line 176 should be 
  
  bboxes = create_mtcnn_net(image, args.mini_lp, device, p_model_path='train/pnet_Weights', o_model_path='train/onet_Weights') 


for training, before run the following, create ccpd_train and ccpd_val in data_set
  MTCNN/data_set/preprocess.py
  
  MTCNN/data_preprocessing/gen_Pnet_train_data.py
  
  MTCNN/data_preprocessing/assemble_Pnet_imglist.py
  
  MTCNN/train/Train_Pnet.py
  
  MTCNN/data_preprocessing/gen_Onet_train_data.py'
  
  MTCNN/data_preprocessing/assemble_Onet_imglist.py
  
  MTCNN/train/Train_Onet.py
  
  MTCNN/MTCNN.py
