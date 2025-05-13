# ece253-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [ECE253 Homework 2 Solved](https://www.ankitcodinghub.com/product/ece253-homework-2-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92176&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE253 Homework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Problem 1. Adaptive Histogram Equalization

It is often found in image processing and related fields that real world data is unsuitable for direct use. This warrants the inclusion of pre-processing steps before any other operations are performed. An example of this is histogram equalization (HE) and its extension adaptive histogram equalization (AHE).

The goal of this problem is to implement a function for AHE as described in Chapter 1 of Adaptive Histogram Equalization – A Parallel Implementation1. The function has the following specifications:

<ol>
<li>(i) &nbsp;The desired function AHE() takes two inputs: the image im and the contextual region size win size.</li>
<li>(ii) &nbsp;Using the pseudocode in Algorithm 1 as a reference, compute the enhanced image after AHE.</li>
<li>(iii) &nbsp;You may use loops if necessary. You should not make use of any inbuilt Python functions for
AHE or HE.
</li>
<li>(iv) &nbsp;The function returns one output: the enhanced image after AHE.</li>
</ol>
Algorithm 1 Pseudocode for Adaptive Histogram Equalization of an Image

*Pre-requirement : Pad the image im on all 4 sides by mirroring intensity values so that the contextual region for edge pixels remains valid. This can be done in Python using numpy.pad() with the ‘symmetric’ argument.

function ahe(im, win size)

</div>
</div>
<div class="layoutArea">
<div class="column">
1: 2: 3: 4: 5: 6: 7: 8:

9:

</div>
<div class="column">
for each pixel (x, y) in image im do rank ← 0

contextual region∗ ← (win size × win size) window centered around (x, y) for each (i,j) in contextual region do

if im(x, y) &gt; im(i, j) then rank ← rank + 1

output(x, y) ← rank × 255/(win size × win size) return output

</div>
</div>
<div class="layoutArea">
<div class="column">
Evaluate your function on the image beach.png for win size = 33, 65, and 129. In your report, include the original image, the 3 images after AHE, and the image after simple HE (you may use Python inbuilt function for this final HE image only). Make sure to resize all images to ensure they do not take up too much space. Additionally, include your answers (no more than three sentences each) to the following questions:

<ul>
<li>How does the original image qualitatively compare to the images after AHE and HE respec- tively?</li>
<li>Which strategy (AHE or HE) works best for beach.png and why? Is this true for any image in general?
1You can find this article here.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Problem 2. Binary Morphology

In this problem, you will be separating out various objects in binary images using morphology, followed by connected component analysis to gather more information about objects of interest.

<ol>
<li>(i) &nbsp;For the binary image circles lines.jpg, your aim is to separate out the circles in the image, and calculate certain attributes corresponding to these circles.
<ul>
<li>The first step is to remove the lines from the image. This can be achieved by perform- ing the opening operation with an appropriate structuring element. You may find the following functions to be of use.

Python: skimage.morphology.opening()

Feel free to try other functions as well for this question.
</li>
<li>Once we have a binary image with just the circles, the individual regions need to be labeled to represent distinct objects in the image i.e. connected component labeling. This can be done in

Python using scipy.ndimage.measurements.label().

Feel free to try other functions as well for this question.
</li>
<li>We now have access to individual regions in the image, each of which can be analyzed separately. For each labeled circular region, calculate its centroid and area. Tabulate these values for each connected component. You may use loops for this part of the problem.
Note : This step must be performed entirely by your code without making use of Python’s inbuilt functions (like regionprops()) for connected component analysis. You can still use simple utility functions like sum(), mean(), find() etc.
</li>
</ul>
</li>
<li>(ii) &nbsp;In this part, we are interested in performing similar operations on the binary image lines.jpg. Your aim now is to separate out the vertical lines from the horizontal ones in the image, and then calculate certain attributes corresponding to these vertical lines.
<ul>
<li>In a similar manner to part (i) above, use the opening operation with a suitable struc- turing element to remove the horizontal lines in the image. (Remove the diagonal line as well).</li>
<li>Next, perform connected component labeling on the resulting image to identify and label each unique vertical line.</li>
<li>Finally, for each labeled region, calculate the length (the longer dimension) and the centroid. Tabulate these values for each connected component. You may use loops for this part of the problem.

Note : This step must be performed entirely by your code without making use of Python’s inbuilt functions (like regionprops()) for connected component analysis. You can still use simple utility functions like sum(), mean(), find() etc.

Things to turn in:

• Part (i) &amp; (ii) : The original image, the image after opening, the image after connected com-

ponent labeling (plot with colorbar), and a table with the desired values for each component. 3
</li>
</ul>
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
<ul>
<li>The structuring element type and size that was used to perform the opening operation (for both parts).</li>
<li>Code for the problem.
Problem 3. Lloyd-Max Quantizer

For this part of the homework, we study the Lloyd-Max quantizer. Before you get started, carefully study pages 602-603 of the book2. Then, proceed to implement the following:

<ol>
<li>(i) &nbsp;Write a function that takes as inputs a greyscale 8-bit (uint8) image, a scalar s ∈ [1, 7] and performs uniform quantization over the entire range [0, 255] so that the output is quantized to an s-bit image. You may use loops for this part if necessary.</li>
<li>(ii) &nbsp;The Python script lloyd python.py is found in the shared homework files. It performs Lloyd Max quantization (optimal quantization in the squared error sense). You can use this function as:
<pre>     partition, codebook = lloyds(training_set, initcodebook)
</pre>
The input training set is a vector of training data (which is used as an empirical measure of the probability mass function), so you will have to flatten your image (in other words, reshape the image from [M,N] to [M*N, 1].

For the images lena512.tif and diver.tif, calculate the MSE values for s ∈ [1,7] using both your uniform quantizer and the Lloyd-Max quantizer (you may use loops for the Lloyd-Max quantizer as well). Plot the results (MSE versus number of bits). Show one plot for lena512.tif (with both uniform and Lloyd-Max quantization) and another plot for diver.tif. Compare the results for the different quantizers/images and explain them. That is, why does one quantizer outperform the other, and why is the performance gap larger for one image than for the other?

Do not make use of in-built Python functions to calculate the MSE.
</li>
<li>(iii) &nbsp;Now use global histogram equalization on lena512.tif and on diver.tif to generate two new images.
Repeat part (ii) for these two new images. Compare them with the previous set of plots. What has happened to the gap in MSE between the two quantization approaches and why?
</li>
<li>(iv) &nbsp;Why is the MSE of the 7-bit Lloyd-Max quantizer zero or near zero for the equalized im- ages? One might have thought that equalization is not to the advantage of the Lloyd-Max quantizer, because equalizing the histogram should be flattening the distribution, making it more uniform, which should be to the advantage of the uniform quantizer. Explain this phenomenon.</li>
</ol>
2Included in the data folder.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Problem 4. Quantization with Dithering

In this problem you will explore the impact of Dithering for image quantization. Specifically, you will be implementing uniform quantization and the algorithm you will be using for dithering is called Floyd-Steinberg.

<ol>
<li>(i) &nbsp;You will first implement a function that performs uniform quantization with different number of color bands. The function must quantize the image to 10 levels. You can handle each color dimension independently.</li>
<li>(ii) &nbsp;Then you will implement the Floyd-Steinberg shown in algorithm (2) dithering algorithm to study the effects of dithering in each quantized image. The find closest palette color() function simply finds the nearest color value according to 10-level quantization. You can handle each color dimension independently.</li>
</ol>
Complete the above two steps on geisel.jpg and answer the questions below. You must include the result of both parts in your report.

1. What differences do you see between the two images?

2. Can you explain what caused these differences?

Algorithm 2 Floyd-Steinberg Dithering

<ol>
<li>1: &nbsp;function fsd(im)</li>
<li>2: &nbsp;for each y from top to bottom do</li>
<li>3: &nbsp;for each x from left to right do</li>
<li>4: &nbsp;old pixel ← im[x][y]</li>
<li>5: &nbsp;new pixel ← find closest palette color()</li>
<li>6: &nbsp;im[x][y] ← new pixel</li>
<li>7: &nbsp;quant error ← old pixel − new pixel</li>
<li>8: &nbsp;im[x + 1][y] ← im[x + 1][y ] + quant error × 7 / 16</li>
<li>9: &nbsp;im[x – 1][y + 1] ← im[x – 1][y + 1] + quant error × 3 / 16</li>
<li>10: &nbsp;im[x ][y + 1] ← im[x ][y + 1] + quant error × 5 / 16</li>
<li>11: &nbsp;im[x + 1][y + 1] ← im[x + 1][y + 1] + quant error × 1 / 16</li>
<li>12: &nbsp;return im</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
