## Eye blink detection
A computer vision application that is capable of detecting and counting blinks in video streams using facial landmarks and OpenCV

To build our blink detector, we’ll be computing a metric called the eye aspect ratio (EAR), introduced by [Soukupová and Čech in their 2016 paper](http://vision.fe.uni-lj.si/cvww2016/proceedings/papers/05.pdf). The landmark positions, extracts a single scalar quantity – eye aspect ratio (EAR) – characterizing the eye opening in
each frame.
