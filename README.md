# Mod Listener Machine Learning Patch for controlling motors with classified audio input

Instructions

Download as zip file associated with Modlisteningproject.maxproj

Check you have externals 
Fluid.acmpslice~.mxo
Fluid.list2bug.mxo
Fluid.mfcc~.mxo
strcut.mxo
strrchr.mxo

If they aren't displaying install FluicCorpusManipulation with Max Package manager

Launch modlisteningproject.maxpat

Launch PWM receiver patch from the Wav-Seq repository

Build the model 
Use this example video to see a demo of filling the data set classifying and labelling data : 
https://learn.flucoma.org/learn/classification-neural-network/
Create new labels for each sound classification
Play sounds back and see if the classification is working - the names should change depending on what sound is playing. 

Once it is working control the modpianosequencer.maxpat to control Wav-Seq from the different tags. Each of the 5 tags can be linked to a preset number in the sequencer patch. This will result in different midi notes and timbre changing according to the audio being sent to the modlisteningproject.maxpat
