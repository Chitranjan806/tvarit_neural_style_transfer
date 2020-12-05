## tvarit_neural_style_transfer

<b>Topic: Neural Style Transfer</b>
</br>
The project is a part of Tvarit GmbH Virtual AI-powered Hackathon, held on 28th November 2020.
<br>
Underlying Concept: Use of Convolutional Neural Networks for Neural Style Transfer.
</br>
<b>Problem Statement: Develop a codebase to perform Neural Style Transfer given a content image and a style image</b>
</br>

Concepts used : CNN, VGG-19, PyTorch
</br>

We have taken a Content Image and a reference Style Image, the aim is to Stylize the Content Image w.r.t to the Style Image. 
</hr> 

#### Important parameters -
**Style Weight : 10,000 <br>
Content Weight : 1 <br>
Optimizer used : LBFGs**

#### Outcome(s) -
For an Example, Below we have taken a content-image (taj.jpg) and a style-image (wave.jpg) and thus a new output-image (stylized.jpg) is generated using both.
<p>Content Image</p>
<img src="/images/taj.jpg" title="Content Image" width="400" height="400"/>

<p>Style Image</p>
<img src="/images/style.jpg" title="Style Image" width="400" height="400"/>

<p>Output Image</p>
<img src="/images/output.PNG" title="Style Image" width="400" height="400"/>
