# AMMI_BootCamp_Week_1
This repository contains all jobs for week 1 of bootcamp. The main paper is <a href= 'https://arxiv.org/pdf/1703.01365.pdf'> Axiomatic Attribution for Deep Networks </a>.

The main idea behind this paper is to identify how much an inputs feature (pixels, for example) contribute to the prediction of a given input data (image for example). This is very important for the model interpretability. The method that we use is <b> Integrated gradient</b>.

In <a href= 'https://arxiv.org/pdf/1703.01365.pdf'> Axiomatic Attribution for Deep Networks </a>, the implementations were done on:
<ol>
  <li> <b> An Object Recognition Network </b> </li>
  <li> <b> Diabetic Retinopathy Prediction </b> </li>
  <li> <b> Question Classification </b> </li>
  <li> <b> Neural Machine Translation </b> </li>
  <li> <b> Chemistry Models </b> </li> 
</ol>

Whereas, up to now my experimentations stay on <b> An Object Recognition Network </b>. I keep working on all these use cases.


The original image is:

<img src='70bfca4555cca92e.jpg' width= 50%>

The interpolated images are:

<img src='interpolated_images.png' width= 50% height= 70%>

<b> Experimentation results: </b> The left and right figures represent </b> gradient method </b> result and <b> Integrated Gradient method </b> results respectively. As you can see, <b> Integrated Gradient method </b> works better than <b> Gradient method </b>, because it the Integrated Gradient image seems the original image. See the Attention mask image et Attention mask + original image.

<img src='ig_result.png' width= 40% height= 40% align="right">

<img src='grad.png' width= 40%  height= 40% align="left"> 








