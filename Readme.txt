First of all I imported necessary libraries

Then I read the orignal image and converted it into RGB
 
Then My code takes 4 input values in the folloeing format.
Enter Number of Gallery Images :5
Enter Number of Query Images :5
Enter Height of Image :300
Enter Width of Image :300

After taking inputs I randomly crop and save images to make both the gallery and query folder

Then I used self defined function of computing SSD between every pair.

After this I compare images and choose the best match in gallery for each query image.

Then I plot pair of images.
