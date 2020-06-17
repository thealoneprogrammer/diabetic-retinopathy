Instructions to be followed
--------------------------------------------------

Install the below required packages:

django - (pip install django)
tensorflow - (pip install tensorflow)
pillow - (pip install pillow || pip install PIL)
numpy (pip install numpy)

===================================================

Configuration to be made:

Inside diabetic_retinopathy -> settings.py at last you have to put your local path to output directory currently it is my local path 

===================================================

Note: 

Currently the models have been trained using tesnsorflow keras you can find the models inside diab_retina_app -> model folder

===================================================

To execute the project run the below command:

python manage.py runserver

===================================================

Input:

choose the test image from the test directory given inside the project ie; diab_retina_app->test
Training images are not included in the folder since it's a large collection 
The same images you have sent have been used for training

===================================================

You are free to edit the front-end/processing logic as per your need

===================================================
