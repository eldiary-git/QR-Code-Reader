# QR-Code-Reader
the project aim to read and generate data from the QR Codes and get details about users, sorting them to ( Authorized ) or ( non Authorized ) users.

**Install Dependencies
*** to run the project you need to install all the Dependencies first:

- pip install numpy

- pip install pyzbar


**Some Code Tips:

- Using ( decode ) from pyzbar to detect and decode the QR code.

- (( cv2.putText )) to get the generated text from the QR code 

- force the output text to be consistant even if the QR code angle  changed by using ( barcode.rect with 0 and 1 values )

- creating datalist file to check if the user “ from the QR code “ authorized or not then read the file and use (splitlines() ) to add space between every line.

- sorting the authorizing results and give the red color for the ( non authorized ) and the green color for the ( authorized ) users.





