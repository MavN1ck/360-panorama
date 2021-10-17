This application takes Images along with the focal length of the lens in pixels and stitches them 

Libraries used:
* OpenCV 3.4.28 (very specific) 
* Matplotlib

# INPUT 
The input dir should have:
<br />* Some .png or .jpg images
<br />* A image_list.txt, file should contain:
<br />   * filename
<br />   * focal_length

<br />This is an example for image_list.txt:

<br /><br />Filename   focal_length
DSC_0184.jpg 830<br /> 
DSC_0185.jpg 830<br />
DSC_0186.jpg 830<br /> 
DSC_0187.jpg 830<br />
DSC_0171.jpg 830<br />
DSC_0172.jpg 830<br />
DSC_0173.jpg 830<br />
DSC_0174.jpg 830<br />
DSC_0175.jpg 830<br />
DSC_0176.jpg 830<br />
DSC_0177.jpg 830<br />


# Output
The program will output:
<br /> 1. Every stitched images, with filename 0.jpg, 1.jpg, 2.jpg, ...
<br /> 2. A aligned image aligned.jpg
<br /> 3. A cropped image cropped.jpg

# Usage
<br />$ python main.py <input img dir>
<br />$ python main.py ./images
