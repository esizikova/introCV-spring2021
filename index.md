<p align="center">
  <img src="https://www.di.ens.fr/willow/research/inpainting/images/new_000228/new_000228.jpg" width="175">
  <img src="https://www.di.ens.fr/willow/research/inpainting/images/new_000228/new_000228_outline.jpg" width="175">
  <img src="https://www.di.ens.fr/willow/research/inpainting/images/new_000228/new_000228_res_comb.jpg" width="175">
 <br>
  Source: <a href="https://www.di.ens.fr/willow/research/inpainting/">Willow</a>
</p>

Course webpage for the NYU Spring 2021 Course: Introduction to Computer Vision. This course is aims to cover a broad topics in computer vision, and is *not* primarily a deep learning course. We will covert topics in traditional computer vision such as camera geometry, image formation, segmentation, object recognition, classification, and detection (see [Syllabus](#Syllabus)).

Special Topics in Data Science, DS-GA 3001.004/.005

### Logistics

* DS-GA 3001.004 (Lecture) \
Wednesdays 1pm-2:40pm  \
**Location**: Global Center for Academic & Spiritual Life, 238 Thompson Street (GCASL 461)   \
**Zoom Link**: please log in to NYU classes to get a meeting ID \
\
Please join the lecture in person or on Zoom. Slides will be available after the class. (see [Schedule](#Schedule)).

* DS-GA 3001.005 (Lab) \
Thursdays from 12pm-12:50pm \
**Location**: Silver Center for Arts & Science, 100 Washington Sq East (SILV_101A) \
**Zoom Link**: please log in to NYU classes to get a meeting ID \
\
Labs will be used to cover additional materials or to work through practical exercises with the TA. 

* **Office Hours**: \
Jean Ponce: Tuesday, 2-3pm (please email for appointment) \
Elena Sizikova: Monday, 11-12pm (please email for appointment)


* **Piazza Link**: https://piazza.com/nyu/spring2021/dsga3001004  \
Please try first to post any questions about course logistics and material, HWs and final project on Piazza. We also highly encourage you to help each other out (but please do not reveal answers). For additional questions, please email course staff.


### Instructors

<a href="https://www.di.ens.fr/~ponce/">Jean Ponce</a> (jean.ponce@inria.fr)  
<a href="https://esizikova.github.io">Elena Sizikova</a> (es5223@nyu.edu)

### TAs
Aryaa Singh (as13538@nyu.edu)  
Manjusha Mishra (mam1974@nyu.edu)

### Grading

Four programming assignments (60% of the grade) + final project (40% of the
grade). Assignments should be submitted using the NYU class site.

* **Excercise 1** on camera calibration ([zip file](/homeworks/homework1.zip)).
Due on Feb. 21.
* **Excercise 2** on Canny edge detector ([zip file](/homeworks/homework2.zip)). Skeleton code [link](https://drive.google.com/file/d/1lRKhITglm_vktU0WlqYlQQm3RPoqmGMc/view?usp=sharing). 
Due on Mar. 14.
* **Excercise 3** on mean shift ([zip file](/homeworks/homework3.zip)). Skeleton code [link](https://drive.google.com/file/d/1m_8YV-0VFTrUgsCEkpwjXU8tkH6XGdVt/view?usp=sharing). 
Due on Apr. 4.
* **Excercise 4** on neural networks ([ipynb notebook](/homeworks/homework4.ipynb)). 
Due on May 2.
* **Final project:** list of suggested papers is available [here](https://docs.google.com/document/d/1_YFp39tF3h811AzrQ32mbQgN4nSp7aA2fjZfQhVNiYE/edit?usp=sharing). Send an email to Elena to validate a project by Mar. 7 at the latest. 

<a name="Syllabus"></a>
### Syllabus 
  * Introduction
  * Camera geometry and calibration
  * Filtering and feature detection
  * Radiometry and color
  * Texture and image segmentation
  * Stereopsis
  * Structure from motion and 3D models from images
  * Object recognition - historical perspective
  * CNNs for object classification and detection
  * 3D CNNs, Applications in Medical Imaging
  * Weakly-supervised and unsupervised approaches to image and video interpretation 

### References:
We do not require purchase of any textbooks and the course will be self-contained. You may wish to consult the resources below for additional material formalization. 

* D.A. Forsyth and J. Ponce, “Computer Vision: A Modern Approach”, second edition, Pearson, 2011. (<a href="https://www.pearson.com/us/higher-education/program/Forsyth-Computer-Vision-A-Modern-Approach-2nd-Edition/PGM111082.html">Link</a>)
* R. Szeliski, “Computer Vision: Algorithms and Applications”. (<a href="http://szeliski.org/Book/">PDF</a>)
* R. Hartley and A. Zisserman, “Multiple View Geometry in Computer Vision”, Cambridge University Press, 2004. (<a href="https://www.robots.ox.ac.uk/~vgg/hzbook/">Link</a>)
 
<a name="Schedule"></a>
### Schedule:

*Note*: lecture slides will be posted after each lecture.

| Date  | Lecture               | Topic | Link                                                                                          |
| ----- | ------------------------ | ------| --------------------------------------------------------------------------------------------- |
| 01/28 | Lab: Course Intro     | Introduction, Logistics       | Intro <a href="https://drive.google.com/file/d/1Tn1-kEBtDKbnQCyahhFCGyQ_ZPqXs9zq/view?usp=sharing"> [PPTX]</a> <a href="https://drive.google.com/file/d/1WyqvvL7qyhyHG6OMiZJ9uOeRICCZhIPy/view?usp=sharing">[PDF]</a> <br> Logistics <a href="https://drive.google.com/file/d/1n2UFZy5v2akBCH0Xkv4K0fCFvQPIt2Kl/view?usp=sharing">[Key]</a> <a href="https://drive.google.com/file/d/16oKZnB7DGok3E3HPI23wQg8UdmtGhqFL/view?usp=sharing">[PDF]</a> |
| 02/03 | Lecture 1             | Examples of vision tasks, camera geometry and calibration      | Lecture <a href="https://drive.google.com/file/d/1vHtN0QPGRr1YbBcqi0kSofE9SVefGuRs/view?usp=sharing">[PPT]</a> <a href="https://drive.google.com/file/d/1eGjNkZq4UCdzKP3Ifl0wVK5pP094MGBg/view?usp=sharing">[PDF]</a> |
| 02/04 | Lab                   | A detour of sensing country, intrinsic and extrinsic parameters      | Lecture <a href="https://drive.google.com/file/d/1GGoqXj0TlIVn_tC1FOTDzkw2RKhhTB37/view?usp=sharing">[PPT]</a> <a href="https://drive.google.com/file/d/154dobxwH7lTyGUTtXSc_TNq3t4mNB-SH/view?usp=sharing">[PDF]</a>|
| 02/10 | Lecture 2             | Linear calibration, analytic photogrammetry, filtering       | Lecture Part 1<br> <a href="https://drive.google.com/file/d/1xspkXD5geGu678MyRcoj-uw3_rVKAUSd/view?usp=sharing">[PPT]</a> <a href="https://drive.google.com/file/d/1bDMESVZjGGiFeKb3omJ_Jv9Uead-8fIB/view?usp=sharing">[PDF]</a>  <br> Lecture Part 2 <br><a href="https://drive.google.com/file/d/1nlbCGGx30MtSIKie96gzq2LfLM-F_OUh/view?usp=sharing">[Key]</a> <a href="https://drive.google.com/file/d/1al1F7Nkdtpo_F6oTKaefFWeRlVhWCXao/view?usp=sharing">[PDF]</a>  |
| 02/11 | Lab                   | Image Stitching Exercise      | <a href="https://colab.research.google.com/drive/1EjXhlIKafUG28vDwkZOEhCd-jhoa1nKP?usp=sharing">Notebook Link</a> |
| 02/17 | Lecture 3             | Edge detection, keypoints and features, RANSAC, Hough transform      | Lecture <a href="https://drive.google.com/file/d/1XgXNqb0h5HGlchNuVbfTUfNKzGLbspO2/view?usp=sharing">[Key]</a> <a href="https://drive.google.com/file/d/1173gZKWAig-eDq59YP6wNP073snDGMVT/view?usp=sharing">[PDF]</a> |
| 02/21 | Exercise 1 DUE        |                                                                                                |
| 02/24 | Lecture 4             | Texture, Segmentation      | Lecture <a href="https://drive.google.com/file/d/1_Q7P2JOPAO3zxcge8b4xXn01dOJb9UUe/view?usp=sharing">[Key]</a> <a href="https://drive.google.com/file/d/1CeUNx0fao7zdFUGr4oyXNrJw9J2KVdrG/view?usp=sharing">[PDF]</a>  |
| 02/25 | Lab                   | Edge Detection using Sobel Operator      | <a href="https://colab.research.google.com/drive/1IvwUBgjDR9DSstSRP7YplUybcbty3Khq?usp=sharing">Notebook Link</a> |
| 03/03 | Lecture 5             | Radiometry and Color, Part 1     | Lecture <a href="https://drive.google.com/file/d/1Ak_lO6MIjctbXI8oEYvv_P0nnl0-W9n3/view?usp=sharing">[PPT]</a> <a href="https://drive.google.com/file/d/1dLV-IzLYop_kLZZ5Ibm5KXgQVkB9o4TH/view?usp=sharing">[PDF]</a>  |
| 03/04 | Lab                   | Radiometry and Color, Part 2      | Lecture <a href="https://drive.google.com/file/d/1Rj90i1CE0vVN53drYeOXpCeNCi6SsngR/view?usp=sharing"> [PPT]</a> <a href="https://drive.google.com/file/d/1zGS_FkE5YDvlUx5GhVKlsXrEtiBj7ZUi/view?usp=sharing"> [PDF]</a> |
| 03/10 | Lecture 6             | Color      | Lecture <a href="https://drive.google.com/file/d/1-SNFft1mLRAZusyz7hcrHaHPj4GSi37c/view?usp=sharing">[PPTX]</a> <a href="https://drive.google.com/file/d/1I0J09P7b1tgZrRqVgqaSBo0HddvLXXRq/view?usp=sharing">[PDF]</a> |
| 03/11 | Lab                   | Canny Edge Detection Skeleton Code      | <a href="https://drive.google.com/file/d/1lRKhITglm_vktU0WlqYlQQm3RPoqmGMc/view?usp=sharing">Lab</a> |
| 03/14 | Exercise 2 DUE        |                                                                                               | |
| 03/17 | Lecture 7             | Stereopsis, Epipolar Geometry, Essential and Fundamental Matrices      | Lecture <a href="https://drive.google.com/file/d/1b273t0a56YJNFnhRsT7WH_go1UhQDO9c/view?usp=sharing">[PPT]</a> <a href="https://drive.google.com/file/d/1YoyS0ra90qJqtLFHlEgrCfCq_38bZDMP/view?usp=sharing">[PDF]</a> |
| 03/18 | Lab                   |      |  |
| 03/24 | Lecture 8             | Eight-point Algorithm, Correlation-based stereo, more sophisticated methods     | Lecture <a href="https://drive.google.com/file/d/1LvHL7QmTddhSJ3WU3n37MTWGb4wCndTg/view?usp=sharing">[Key]</a> <a href="https://drive.google.com/file/d/1aB8usdbFCGkV7LBS6qmBRFYjBybJVM9Q/view?usp=sharing">[PDF]</a>  |
| 03/25 | Lab                   |      |  |
| 03/31 | Lecture 9                   |      |  |
| 04/01 | Lab                   |      |  |
| 04/04 | Exercise 3 DUE        |                                                                                               | |
| 04/07 | Lecture 10                   |      |  |
| 04/08 | Lab                   |      |  |
| 04/14 | Lecture 11                   |      |  |
| 04/15 | Lab                   |      |  |
| 04/21 | Lecture 12                   |      |  |
| 04/22 | Lab                   |      |  |
| 04/28 | Lecture 13                   |      |  |
| 04/29 | Lab                   |      |  |
| 05/02 | Exercise 4 DUE        |                                                                                               | |
| 05/05 | Lecture 14                   |      |  |
| 05/06 | Lab                   |      |  |


### Acknowledgements
Much of the material for this course relies on the Computer Vision course given at ENS Paris by Mathieu Aubry, Karteek Alahari, Ivan Laptev, and Josef Sivic. Many of the slides are taken from James Hays, Svetlana Lazebnik, and Derek Hoeim. Website was originally designed by Matthew Trager.
