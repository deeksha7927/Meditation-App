<div align='center'>
  <h2>Meditation Web app</h2>
  </div>
 


<h3>Description</h3>
  
  </div>
 Practicing meditation through a meditation app helps you tune into your body and stay in the present moment with exercises and expert advice. Being mindful through meditation has been shown to help improve your focus on tasks in everyday life as well as process new information. Using an app as a guide while you meditate can also help you build up your meditation skill set, which may in turn help you access a calm, focused state in your day-to-day life more easily. This app have the advantage of providing intuitive tools, like trackers, that can help keep you accountable and improve over time and background video.
 </div>



 <h3>The GAN</h3>
 <div align="center">
  A. Generator
Our generator ( represented as  G  ) will take in grayscale image  x  and produce a RGB image  G(x) . Note,  x  will be a tensor of shape  ( batch size , 120 , 120 , 1 )  and the output  G(x)  will have a shape  ( batch size , 120 , 120 , 3 ) .Our generator will have a encoder-decoder structure, similar to the UNet architecture. Additionally, we use Dilated convolutions to have a larger receptive field.


B. Discriminator
The discriminator model, represented as  D , will take in the real image  y  ( from the training data ) and the generated image  G(x)  ( from the generator ) to output two probabilities.We train the discriminator in such a manner that is able to differentiate the real images and the generated images. So, we train the model such that  y  produces a output of  1.0  and  G(x)  produces an output of  0.0 .
   
 
 
