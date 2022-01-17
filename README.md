# tf-keras-image-recog
Tensorflow app with keras model to recognize images and label them


#Prereq:
Docker (docker desktop)

Git


#Run in Docker!

How to run:

git clone https://github.com/VincentLideboKjellman/tf-keras-image-recog.git

cd tf-keras-image-recog

docker build -t my-app .     (dont forget the dot :) )

docker run -it --rm -p 5000:5000 my-app

Then open http://localhost:5000 to view!


