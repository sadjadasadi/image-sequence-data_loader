
This project helps you to read data images in a sequence manner as input to the CNN-LSTM model.

![alt text](https://github.com/sadjadasadi/image-sequence-data_loader/blob/main/2.png)


Note:
The dataset directory must have a template like below

![alt text](https://github.com/sadjadasadi/image-sequence-data_loader/blob/main/3.png)

+ at first time_step ,data_dir ,img_format must be config. 

Warning: if sth is wrong, check this issue: 

    In Win, paths use backslash "\" and in Unix based use forward slash "/" as path separator, so check line ...dir.split('\\')...  
    
    for example in Colab you must use dir.split("/") ...


Next update:
+ read from videos



