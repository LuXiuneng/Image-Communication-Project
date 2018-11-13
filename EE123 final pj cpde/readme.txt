1.To transmit image, we first run preprocess.ipynb to processing the data. By carefully set the threshold, we would like to generate a test.bnr.gz file with no more than 9kB, which contains the information for reconstruction. 

2.Send the test.bnr.gz file to the raspi under the same dictionary of transmiter.ipynb

3.Then we run the transmiter.ipynb to modulate the test.bnr.gz file, make the corresponding packages, put them into a queue and transmit it.

4.At the same time, we run another code reveicer.ipynb on the receiver's rasperry-pi to receive the package and write as test_test.bnr.gz file for future processing.

5.Download test_test.bnr.gz to the same dictionary of postprocess.ipynb.

6.Finally, we run postprocess.ipynb to reconstruct the picture and compute the PSNR. 

**********************
try_2400_1.ipynb is an unsuccessful attempt for increasing the transmission rate to 2400 bit/s.

PS: PSNR of all the images are in newsend.ipynb, listed at the beginning. 