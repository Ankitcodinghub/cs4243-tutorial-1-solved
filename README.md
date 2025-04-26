# cs4243-tutorial-1-solved
**TO GET THIS SOLUTION VISIT:** [CS4243 Tutorial 1 Solved](https://www.ankitcodinghub.com/product/cs4243-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127071&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4243 Tutorial 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Theoretical:

Q1: Consider images of size 12×12 with pixel values ranging from 0 to 15. For the following image histograms, estimate the mapped intensity values after histogram equalization.

Figure 1

Original Intensity Intensity after histogram equalization

(a) (b) (c) (d) (e)

0

1

2

3

4

5

6

7

8

9

10

11

12

13

14

15

Q2: Consider the source image shown in (a) and the filter kernel shown in (b). What is the resulting value at positions (0,0), (2,2) and (4,3) if you were to apply cross-correlation, convolution, and 3×3 median filtering, with the use of zero-padding on the borders? Positions are denoted as (row,column) in the unpadded image.

Pixel position Output pixel intensity

cross-

correlation convolution median filtering

(0,0)

(2,2)

(4,3)

(a) source image (b) kernel

Figure 2

Coding (see CS4243-Tutorial-01.ipynb):

• Install basic python packages: imutils, opencv-python, scikit-image

• Load and display House.jpg

• Visualize the (R,G,B) channels; visualize the normalized colour and intensity images

• Convert RGB image into HSV colour space and visualize the (H,S,V) channels

• Resize an image such that the dimensions are 2X, 0.5X and 0.05X the original size

• For Capture.jpeg

o Visualize the image histogram

o Access a pixel value: what is the pixel intensity of (100,800) o Access a window of data: crop out the stadium

• Write your own algorithm for histogram stretching and equalization. Visualize the resulting histograms and compare with the built-in cv2.equalizeHist .

• Smooth image Synthetic.png with a box filter of size 5 and a Gaussian kernel of size 5 and a sigma of size 3.

• Smooth image Building.png with a box filter of size 30 and a Gaussian kernel of size 30 and a sigma of size 10.

• Apply 2D Laplace filter as described in L3 slide 25 to images Synthetic.jpg and Sharpen.jpeg and the smoothed versions from above

Past Quiz Questions:

• AY2021_Quiz1

• AY2122_Quiz1: Q1 to Q4
