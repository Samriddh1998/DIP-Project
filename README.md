# Image and Video Encryption using XOR logic
Made as a project for the cource ECN 316 Digital Image Processing

## Language requirement
python 3.0

## Package Requirement
cv2, pywt, numpy, time

## Sample images 
image_0.jpg, image_1.jpg, image_3.png, image_4.png can be used for testing
 
## For Image Encryption
 - Run - GenSecretKey.py
   - Modify the image you want to encrypt inside the program - line 10
   - Images **toBeEncrypted.png** and **secret_key.png** will be generated
 - Run - Encryption.py
   - Image **EncryptedImage.png** is generated
 - Run - Decryption.py
   - Image **DecryptedImage.png** is generated
    
## For Video Encryption 
 - makes sure **image secret_key_video.png** is present in the same folder as that of WebCameLive.py
 - Run - WebCameLive.py
  
The program Webcame.py generates images taken directly from the web cam. Press Spacebar to capture an image.
