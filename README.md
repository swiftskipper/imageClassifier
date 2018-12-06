# imageClassifier

Here is the full demo presented on We Are Developers AI Congress in Vienna, on Dec. 4th 2018.

It demonstrates the process of making an image classifier for iOS using Swift - end-to-end. 
Training of the model has been done with Create ML im XCode / Playgroud.
The final app uses Core ML for inference, based on the model.

If you want to recreate the, steps would be as follows:

1. Open trainTheModel.playground and run it
2. Eventualy, click on down arrow next to the ImageClassifier label and set 
fine tuning options for the training
3. Drag-and-drop the whole folder Training into ImageClassifier box
4. Wait for few seconds and save the model
5. Open coreMLDemo folder and coreMlDemo.xcodeproj in it
6. Eventualy, replace existing .mlmodel file with the model you madel
7. Run the app

All the pictures are made using iPhone 7 with no additional modifications applied.
You can prepare your own image set by following these steps

1. Make images with camera and place them in separate folders.
2. Name folders according to content. Folder names will be labels for inference
3. Split folders in relation 80:20 in two containing folders nemed Training and Test, 
as I did it here 

The model I made is as small as 66 kb. 

My recommendations for experiments would be:

1. Try with more categories
2. Add more images to each category and follow 
the numbers related to model accuracy
3. Change training parameters: Crop, Blur, Expose, Noise, Flip and Max iterations


Happy with experiments.









