# C++ Crack Detection code using Raspiberry Pi Camera  

C++ code based on OpenCV library capable of detecting cracks utilizing a Raspberry Pi 3, Pi Camera and Raspicam Library  

When compiling the .cpp file please use the following flags:  

g++ *** -o *** $(pkg-config --cflags --libs opencv) -I/usr/local/include -L/opt/vc/lib -lraspicam -lmmal -lmmal_core -lmmal_util -lraspicam_cv
