---
title: "WikiART Face: Face Image Dataset from Art."
excerpt: "6K Face Images from Artwork via WikiART. <br/><p align="center"><img src='/files/projects_wikiart/wikiart_face.1.png' width='500' height='500'></p>"
collection: project
---

<p align="center">
<img src='/files/projects_wikiart/wikiart_face.1.png' width='500' height='500'><br>
<em>Figure 1. Samples from WikiART Face Image.</em>
</p>

Recent progress in computer vision proves that large generative models can model natural images with a decent quality
([BigGAN](https://arxiv.org/pdf/1809.11096.pdf),
[GLOW](https://arxiv.org/pdf/1807.03039v2.pdf), etc).
Nevertheless, there are still vast room to improve the generalization ability and the quality of the generated images,
so the community is keen to develop new approaches for better image modeling.
As an art fun rather than a machine learning researcher, I have a question 
"Can we model artworks with the generative models?", and if so, I believe those models should give us 
a different perspective of the art world. 
This is our core motivation of this project to have a general art image dataset to facilitate research in computation art.
In this project, we create two datasets ***WikiART Face*** and ***WikiART General***. 
To create our datasets, the original images are taken from [WikiART](https://www.wikiart.org/), which is an online visual art encyclopedia with
[wikiart-crawler](https://github.com/asahi417/wikiart-crawler).


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-lqy6{text-align:right;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Art Movements</th>
    <th class="tg-lqy6">Image Size</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Abstract Expressionism</td>
    <td class="tg-lqy6">22</td>
  </tr>
  <tr>
    <td class="tg-0lax">Baroque</td>
    <td class="tg-lqy6">17</td>
  </tr>
  <tr>
    <td class="tg-0lax">Ecole de Paris</td>
    <td class="tg-lqy6">228</td>
  </tr>
  <tr>
    <td class="tg-0lax">Expressionism</td>
    <td class="tg-lqy6">649</td>
  </tr>
  <tr>
    <td class="tg-0lax">Impressionism</td>
    <td class="tg-lqy6">1,166</td>
  </tr>
  <tr>
    <td class="tg-0lax">Naive Art (Primitivism)</td>
    <td class="tg-lqy6">72</td>
  </tr>
  <tr>
    <td class="tg-0lax">Neo Impressionism</td>
    <td class="tg-lqy6">41</td>
  </tr>
  <tr>
    <td class="tg-0lax">Neoclassicism</td>
    <td class="tg-lqy6">607</td>
  </tr>
  <tr>
    <td class="tg-0lax">Post Impressionism</td>
    <td class="tg-lqy6">474</td>
  </tr>
  <tr>
    <td class="tg-0lax">Pre-raphaelite Brotherhood</td>
    <td class="tg-lqy6">103</td>
  </tr>
  <tr>
    <td class="tg-0lax">Realism</td>
    <td class="tg-lqy6">1,625</td>
  </tr>
  <tr>
    <td class="tg-0lax">Rococo</td>
    <td class="tg-lqy6">1,030</td>
  </tr>
  <tr>
    <td class="tg-0lax">Romanticism</td>
    <td class="tg-lqy6">1,502</td>
  </tr>
  <tr>
    <td class="tg-0lax">Surrealism</td>
    <td class="tg-lqy6">78</td>
  </tr>
  <tr>
    <td class="tg-0lax">Symbolism</td>
    <td class="tg-lqy6">571</td>
  </tr>
  <tr>
    <td class="tg-0lax">All</td>
    <td class="tg-lqy6">6,095</td>
  </tr>
</tbody>
</table>

***WikiART Face Image*** is a dataset of face images from portraits via [WikiART](https://www.wikiart.org/), which is an online visual art encyclopedia.
Figure 1 shows sample images from the dataset.
Following [CelebA](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) dataset, we  


<p align="center">
<img src='/files/projects_wikiart/face_image_pipeline.png' width='500' height='500'><br>
<em>Figure 2. Pipeline Process.</em>
</p>


<p align="center">
<img src='/files/projects_wikiart/celeba.1.png' width='200' height='200'>
<img src='/files/projects_wikiart/wikiart_face.1.png' width='200' height='200'>
<br>
<em>Figure 2. Pipeline Process.</em>
</p>

<p align="center">
<img src='/files/projects_wikiart/celeba.0.png' width='500' height='500'><br>
<em>Figure 1. Samples from CelebA Dataset.</em>
</p>

## Wiki











