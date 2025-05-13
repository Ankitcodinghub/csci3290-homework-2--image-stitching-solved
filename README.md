# csci3290-homework-2--image-stitching-solved
**TO GET THIS SOLUTION VISIT:** [CSCI3290 Homework 2 -Image Stitching Solved](https://www.ankitcodinghub.com/product/csci3290-homework-2-image-stitching-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92230&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI3290 Homework 2 -Image Stitching Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Image Stitching

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 Assignment description

Image stitching is a technique to combine a set of images into a larger image by registering, warping, resampling and blending them together. A popular application for image stitching is creation of panoramas. Generally speaking, there are two classes of methods for image stitching, direct methods and feature-based methods. In this assignment, we will implement a feature-based method. It contains three parts: i) feature detection and matching, ii) homography estimation and iii) blending.

2 Assignment details

2.1 Feature detection and matching

Given two input images, detect SIFT features from them. And then establish the feature correspondence between SIFT features in the two input images using Brute-Force matcher. In OpenCV, there is a tutorial for SIFT https://docs.opencv.org/3.4/da/df5/tutorial_py_sift_intro.html, and a tutorial for Brute-Force matcher https://docs.opencv.org/3.4/dc/dc3/tutorial_py_matcher.html.

This part is corresponding to extract and match feature function in the provided skeleton code:

def extract and match feature(img 1, img 2, ratio test=0.7): ”””

:param img 1: input image 1

:param img 2: input image 2

:param ratio test: ratio for the robustness test

:return list pairs matched keypoints: a list of pairs of matched points: [[[p1x,p1y] ,[p2x,p2y]]]

”””

list pairs matched keypoints = []

# to be completed ….

return list pairs matched keypoints You need to do the following things in this function:

1) extract SIFT feature from image 1 and image 2,

2) use a bruteforce search to find pairs of matched features: for each feature point in img 1, find its best matched feature point in img 2,

3) apply ratio test to select the set of robust matched points.

2.2 Homography estimation

The 2D image transformations (translation, rotation, scale, affine and perspective) can be represented as ho- mography. Therefore, we can estimate the best homography by the matched pairs of features. Also, we employ RANSAC algorithm to eliminate the ”bad” matches. This can make our program more robust. In this sec- tion,you need to implement the RANSAC algorithm to find a robust homography between two input images using the feature correspondence.

This part is corresponding to find homography ransac function in the provided skeleton code:

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
5 – Assignment 2: Image Stitching 2

</div>
</div>
<div class="layoutArea">
<div class="column">
def find homography ransac(list pairs matched keypoints , threshold ratio inliers=0.85,

threshold reprojection error=3, max num trial=1000):

”””

:param list pairs matched keypoints :

a list of pairs of matched points: [[[p1x,p1y],[p2x,p2y]] ,…] :param threshold ratio inliers :

threshold on the ratio of inliers over the total number of samples,

accept the estimated homography if ratio is higher than the threshold :param threshold reprojection error :

threshold of reprojection error (measured as euclidean distance, in

pixels) to determine whether a sample is inlier or outlier :param max num trial:

the maximum number of trials to take sample and do testing to find the best homography matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
: return best H : the best ”””

best H = None

# to be completed . . .

return best H

2.3 Blending

</div>
<div class="column">
found

</div>
<div class="column">
homography

</div>
<div class="column">
matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
Having the estimated homography, we can warp the second image to align with the first image and then blend them together to get a a single panorama image. For warping, we employ inverse warping and bilinear resampling.

This part is corresponding to warp blend image function in the provided skeleton code:

def warp blend image(img 1, H, img 2): ”””

:param img 1: the original first image

:param H: estimated homography

:param img 2: the original second image :return img panorama: resulting panorama image ”””

img panorama = None

# to be completed . . .

return img panorama

You need to do the following things in this function:

1) warp image img 2 using the homography H to align it with image img 1 (using inverse warping and bilinear resampling),

2) stitch image img 2 to image img 1 and apply average blending to blend the two images into a single panorama image.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
5 – Assignment 2: Image Stitching 3 3 Submission guidelines

3.1 Marks

* extract and match feature: 40 points * find homography ransac: 30 points

* warp blend image: 30 points

3.2 Put personal information in your source code

In all your source files, type your full name and student ID, just like:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>#
#
#
#
#
#
#
#
#
#
#
#
#
#
</pre>
</div>
<div class="column">
CSCI3290 Computational Imaging and Vision ∗ −−− Declaration −−− ∗

I declare that the assignment here submitted is original except for source material explicitly acknowledged. I also acknowledge that I am aware of University policy and regulations on honesty in academic work, and of the disciplinary guidelines and procedures applicable to breaches of such policy and regulations , as contained in the website http://www.cuhk.edu.hk/policy/academichonesty/ ∗

Assignment 2 Name :

Student ID : Email Addr :

</div>
</div>
</div>
