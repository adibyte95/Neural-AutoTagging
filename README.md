# Neural-AutoTagging
Neural auto Tagging aims to automatically tag photos based on the few images that it has been shown.it uses <b>Siamese Neural Network</b>. this model is based on <b>FaceNet</b> model.
<br/>

<h2>Adding User to The Database</h2><br/>
1. Through webcam: users can opt for option 1 in user registration to take a snapshot of themselves from the integrated wecam. program automatically crops the face part from the taken photo and stores in a desired place. moreover if the person is not looking at the webcam then the program waits until it detects a face.<br/>
2. Adding photo through webcam is easy but the photo quality can depend on the quality of the webcam and also lightning condition of the room so there is another option to add user from disk. this gives better results <br/>

<h2>Deleting User</h2><br/>
there is also an option to delete user and all photographs stores from the data base

<h2>How well does it perform </h2><br/>
enough of talking tech but the important question is how well does it really perform in real life.let me share some real snapshots to give you a real idea about this <br/>

here is a pic to priyanka chopra which it was able to detect perfectly
<img src= "https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/priyanka.jpg"/><br/>
its not that it can only detect faces in which person is looking directly. here is a picture of aishwarya rai who is looking slightly side ways <br/>
<img src="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/aish_2.jpg" /><br/>
it can also detect if two persons are present in the same frame which is the sole perpose of this repository. here is a picture of emma watson and beyonce which is deteced perfectly even though 4 female actress are present in the data base. <br/>
<img src ="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/emma_beyonce.jpg" /><br/>

so now the main question comes is it perfet. common nothing is perfect in this world and this is no exception. have a look at the following image in which abhishek is recognized as beyonce.<br/>
<img src="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/abhishek.jpg" ><br/>
here is another one<br/>
<img sc="https://github.com/adibyte95/Neural-AutoTagging/blob/master/tagged_photos/aish_abhi.jpg" />
