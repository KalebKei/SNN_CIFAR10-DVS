This folder contains the neuromorphic vision dataset named as 'CIFAR10-DVS' obtained by displaying the moving images of the CIFAR-10 dataset(http://www.cs.toronto.edu/~kriz/cifar.html) on a LCD monitor. The dataset is used for event-driven scene classification and pattern recognition. These recordings can be displayed using the jAER software (http://sourceforge.net/p/jaer/wiki/Home) using filters DVS128.
For easy data reading, the original dataset is transformed from aedat 2.0 format to aedat 4.0 format by using iniVation software.

The high-sensitivity DVS used in our recording system reported in:
P. Lichtsteiner, C. Posch, and T. Delbruck, ��A 128��128 120 dB 15 m/s latency asynchronous temporal contrast vision sensor,�� IEEE J. Solid-State Circuits, vol. 43, no. 2, pp. 566-576, Feb. 2008

A single 128x128 pixel DVS sensor was placed in front of a 24" LCD monitor. Images of CIFAR-10 were upscaled to 512 * 512 through bicubic interpolation, and displayed on the LCD monitor with circulating smooth movement. A total of 10,000 event-stream recordings in 10 classes(airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck) with 1000 recordings per classes were obtained. 


