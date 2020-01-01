# About autoPhotoFrame
Its' a project during LSA lesson,a RaspberryPi based thing. By using webcam take a photo and then identify where's human's face.After that combine the face with some special photoframes then send it to a telegrambot. 
## How to use
1.clone the project：
```
git clone https://github.com/YiLiangChen/autoPhotoFrame.git
```
2.run those code in following sequence：
```
fswebcam human.png ( make sure your webcam linked to your RaspberryPi and ready for work ,this command will take a photo)
```
```
detectface.py ( it will find out human's face in photo and resize it)
```
```
merge.py (it will put the face with photoframe together then you can see the final photo in your folder)
```
at last ```bot.py```
