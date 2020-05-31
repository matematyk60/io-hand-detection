 ##usage
 
 script `generate_object_detector` trains simple object detector using images in `my_hands` directory and `my_hands.xml` dataset. 
 
 After training an object detector it verifies it's accuracy agaist test dataset `my_hands_test.xml`
 
 Generated detector is saved in `detector.svm` file.
 
 Run script test_generated_object_detector to view your webcam stream. Detected hands should be marked with a blue rectangle.
 