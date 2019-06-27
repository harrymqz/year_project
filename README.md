# This is the ROS year project

This exercise will cover the following features:

1. Create your <PROJECT> package and customize the package.xml
2. Create a file with parameter year equals to 2018
3. Create a launch file that loads that parameter in the namespace /masteruvic (if you run rosparam list, you should get /masteruvic/year, if you run rosparam get /masteruvic/year you should get 2018)
4. Add an rviz node to the launch file
5. Include the file usb_cam-test.launch from the package usb_cam
6. What are the arguments of usb_cam-test.launch?
- video_device
- image_width
- image_height
- pixel_format
- camera_frame_id
- io_method