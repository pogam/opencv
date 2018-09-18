set(the_description "Video Analysis")
#ocv_define_module(video opencv_imgproc WRAP java python js)
ocv_define_module(video opencv_imgproc opencv_highgui OPTIONAL opencv_calib3d WRAP java python js)
