#Object-Recognization-using-resnet
# Object-Recognization-using-resnet
# configuring the path of Kaggle.json file
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json

# dataset api
!kaggle competitions download -c cifar-10
