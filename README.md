The aim of this project is to automatically evaluate the score of hits at a target board which has been shot
at by a laser gun. The score evaluation is made by processing the captured images of the target board while
shooting is on progress. Images of the target board are taken by a camera and processed by an embedded
microprocessor. Based on the information obtained via processing of images, the microprocessor
immediately informs the user about his/her overall score. A prototype shooting board was built and shooting
by a laser gun and the ensuing evaluation were realized in real time. Unlike the projects in the literature, the
camera is not located on the gun. It is placed at the back of the target board in a box. Python software language
is used for the implementation of image processing operations.

The designed shooting evaluator can be used both in military and civil applications. The military can
use it to train their soldiers and police officers using equipment that is not expensive compared to simulations
with real ammunition. Before experiencing a real gun, the user can train his reflexes with this shooting
evaluator. Civilians can also use it as a shooting game or even train themselves for personal hobbies like
hunting.

Companies in funfairs can use it to entertain customers. As a result, the developed prototype can be
employed wherever the user wants it to be employed.


The camera to be employed for the proposed shooting evaluator system can be chosen to be fairly
low-cost. Two factors are considered when deciding on the hardware parts; i.e. being low-cost and being
commercially available.
The hardware module of the proposed system consists of the following components:
• Camera: Raspberry Pi-Camera V1.3
• Laser Pointer: Red laser pointer which is usually employed in air guns for aiming
• Single Board Computer: Raspberry Pi Module
• Monitor: 7 Inches LCD Screen for Raspberry Pi


Open Source Computer Vision (Open CV) is an open source computer vision and machine learning
software library. OpenCV is built to provide a common infrastructure for computer vision applications and
to accelerate the use of machine perception in the commercial products [7].

Pycharm is an integrated development environment (IDE) used in computer programming, specifically
for the Python language. It was developed by the Czech company JetBrains.

Numpy is the fundamental package for scientific computing in Python. It is a Python library that
provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and
an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation,
sorting, selecting, discrete Fourier transform, basic linear algebra, basic statistical operations, and stochastic
simulations [8].

Matplotlib is a Python library used to create 2D graphs and plots using Python scripts. It has a module
named “pyplot” which enables plotting using various line styles, fonts, and axis formatting. Matplotlib
supports a wide variety of graphs and plots such as histogram, bar charts, power spectra, error charts etc. It
is used along with Numpy to provide an environment that is an effective open source alternative for Matlab
