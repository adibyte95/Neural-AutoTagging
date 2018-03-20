# Neural-AutoTagging
Neural auto Tagging aims to automatically tag photos based on the few images that it has been shown.it uses <b>Siamese Neural Network</b>. this model is based on <b>FaceNet</b> model.
<br/>

<h2>Adding User to The Database</h2>
1. Through webcam: users can opt for option 1 in user registration to take a snapshot of themselves from the integrated wecam. program automatically crops the face part from the taken photo and stores in a desired place. moreover if the person is not looking at the webcam then the program waits until it detects a face.<br/>
2. Adding photo through webcam is easy but the photo quality can depend on the quality of the webcam and also lightning condition of the room so there is another option to add user from disk. this gives better results <br/>

<h2>Deleting User</h2>
there is also an option to delete user and all photographs stores from the data base

<h2>How well does it perform </h2>
enough of talking tech but the important question is how well does it really perform in real life.let me share some real snapshots to give you a real idea about this <br/>

here is a pic to priyanka chopra which it was able to detect perfectly
<img src= "https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/priyanka.jpg"/><br/>
its not that it can only detect faces in which person is looking directly. here is a picture of aishwarya rai who is looking slightly side ways <br/>
<img src="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/aish_2.jpg" /><br/>
it can also detect if two persons are present in the same frame which is the sole perpose of this repository. here is a picture of emma watson and beyonce which is deteced perfectly even though 4 female actress are present in the data base. <br/>
<img src ="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/emma_beyonce.jpg" /><br/>

so now the main question comes is it perfect. common nothing is perfect in this world and this is no exception. have a look at the following image in which abhishek is recognized as beyonce.<br/>
<img src="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/abhishek.jpg" ><br/>
here is another one<br/>
<img src="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/aish_abhi.jpg" />

<h2>Tips to improve performance </h2>
1. try using high quality of images. don't use webcam if you webcam is of poor quality
2. try training the model from ground up. i used trained weights here because of lack of computing power . this network can achieve good accuracy by minimizing some thing called triplet loss 

<h2>Note</h2>
any one can raise an issue if any bug is found. i am also open to pull requests.<br/>
<h2>Credits</h2>
1.Code for Facenet model is based on the assignment from Convolutional Neural Networks Specialization by Deeplearning.ai on Coursera.
2.Florian Schroff, Dmitry Kalenichenko, James Philbin (2015). <a href= "https://arxiv.org/pdf/1503.03832.pdf"> FaceNet: A Unified Embedding for Face Recognition and Clustering</a><br/>
3. Yaniv Taigman, Ming Yang, Marc'Aurelio Ranzato, Lior Wolf (2014). <a href="https://research.fb.com/wp-content/uploads/2016/11/deepface-closing-the-gap-to-human-level-performance-in-face-verification.pdf"> DeepFace: Closing the gap to human-level performance in face verification</a><br/>
