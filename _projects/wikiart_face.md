---
title: "WikiART Face: Face Image Dataset from Portraits"
excerpt: "6K Face images from portraits via WikiART. <br/> <img src='/files/projects_wikiart/wikiart_face.header.png' width='500' height='500'>"
collection: project
---

<p align="center">
<img src='/files/projects_wikiart/wikiart_face.header.png' width='500' height='500'><br>
<em>Figure 1: Samples from WikiART Face Image.</em>
</p>

Recent progress in computer vision proves that large generative models can model natural images with a decent quality
([BigGAN](https://arxiv.org/pdf/1809.11096.pdf),
[GLOW](https://arxiv.org/pdf/1807.03039v2.pdf), etc).
Nevertheless, there are still vast room to improve the generalization ability and the quality of the generated images,
so the community is keen to develop new approaches for better image modeling.
As an art fun rather than a machine learning researcher, I have a question 
"Can we model artworks with the generative models?", and if so, I believe those models should give us 
different perspectives of artworks. 
This is our core motivation of this project to have a general art image dataset to facilitate research in computation art.
In this project, we create two art image datasets [WikiART Face & WikiART General](https://github.com/asahi417/wikiart-image-dataset). 
All the original artwork images are taken from [WikiART](https://www.wikiart.org/), which is an online visual art encyclopedia, with
[wikiart-crawler](https://github.com/asahi417/wikiart-image-dataset#wikiart-crawler).

<p align="center">
<img src='/files/projects_wikiart/face_image_pipeline.png' width='750' height='750'><br>
<em>Figure 2: Pipeline Process.</em>
</p>

***WikiART Face*** is a dataset of face images produced on top of portrait images.
Figure 1 shows sample images from the dataset.
WikiART Face is a collection of face from paintings.
Inspired by the largest human-face image set [CelebA](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html), 
we process all the portraits from WikiART with the pipeline described in Figure 2, that results in 6,095 images across
various art movements.
Following figures present samples from some art movements.

<p align="center">
<img src='/files/projects_wikiart/wikiart_face_ecole-de-paris.png' width='500' height='500'><br>
<em>Figure 3: Samples from WikiART Face Image (from Ecele de Paris).</em>
<br>
<img src='/files/projects_wikiart/wikiart_face_impressionism.png' width='500' height='500'><br>
<em>Figure 4: Samples from WikiART Face Image (from Impressionism).</em>
<br>
<img src='/files/projects_wikiart/wikiart_face_pre-raphaelite-brotherhood.png' width='500' height='500'><br>
<em>Figure 5: Samples from WikiART Face Image (from Pre-Raphaelite Brotherhood*).</em>
<br>
<img src='/files/projects_wikiart/wikiart_face_rococo.png' width='500' height='500'><br>
<em>Figure 6: Samples from WikiART Face Image (from Rococo).</em>
</p>

Table 1 shows the data size breakdown per each art movement.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:10px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:10px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-lqy6{text-align:right;vertical-align:top}
</style>
<table class="tg">
  <caption>Table 1: Data Statistics.</caption>
<thead>
  <tr>
    <th class="tg-baqh">Art Movements</th>
    <th class="tg-lqy6">Image Size</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">Abstract Expressionism</td>
    <td class="tg-lqy6">22</td>
  </tr>
  <tr>
    <td class="tg-baqh">Baroque</td>
    <td class="tg-lqy6">17</td>
  </tr>
  <tr>
    <td class="tg-baqh">Ecole de Paris</td>
    <td class="tg-lqy6">228</td>
  </tr>
  <tr>
    <td class="tg-baqh">Expressionism</td>
    <td class="tg-lqy6">649</td>
  </tr>
  <tr>
    <td class="tg-baqh">Impressionism</td>
    <td class="tg-lqy6">1,166</td>
  </tr>
  <tr>
    <td class="tg-baqh">Naive Art (Primitivism)</td>
    <td class="tg-lqy6">72</td>
  </tr>
  <tr>
    <td class="tg-baqh">Neo Impressionism</td>
    <td class="tg-lqy6">41</td>
  </tr>
  <tr>
    <td class="tg-baqh">Neoclassicism</td>
    <td class="tg-lqy6">607</td>
  </tr>
  <tr>
    <td class="tg-baqh">Post Impressionism</td>
    <td class="tg-lqy6">474</td>
  </tr>
  <tr>
    <td class="tg-baqh">Pre-raphaelite Brotherhood</td>
    <td class="tg-lqy6">103</td>
  </tr>
  <tr>
    <td class="tg-baqh">Realism</td>
    <td class="tg-lqy6">1,625</td>
  </tr>
  <tr>
    <td class="tg-baqh">Rococo</td>
    <td class="tg-lqy6">1,030</td>
  </tr>
  <tr>
    <td class="tg-baqh">Romanticism</td>
    <td class="tg-lqy6">1,502</td>
  </tr>
  <tr>
    <td class="tg-baqh">Surrealism</td>
    <td class="tg-lqy6">78</td>
  </tr>
  <tr>
    <td class="tg-baqh">Symbolism</td>
    <td class="tg-lqy6">571</td>
  </tr>
  <tr>
    <td class="tg-baqh">All</td>
    <td class="tg-lqy6">6,095</td>
  </tr>
</tbody>
</table>

***WikiART General*** is a dataset of general artwork images taken from WikiART.
For further information including links to download the datasets, please refer our [github repository](https://github.com/asahi417/wikiart-image-dataset).


