# GoogleImagesWebExtractor

This repository contains files necessary to extract google images from web search. 

The way it is done is the following:

1.Download the two files(use git clone)

2.Go to google and search images you want to download.

3.Scroll down, and stop scrolling whenever you think the rest of the image below are irrelevent or not needed.

4.Open google web javascript console: On Windows and Linux: Ctrl + Shift + J. On Mac: Cmd + Option + J.

5.Copy every line of code of js_console.js into the google javascript console(you will get some errors, but do not worry, it's going to work out fine).

6.When you finish the last line of code, a text file will be downloaded, and then put this file into your folder where you downloaded the two files provided in this repository

7.Go to terminal/command prompt, and go to the direcotry where you downloaded these two files(by cd command).

8.Enter "python3 download_images.py --urls urls.txt --output images" (don't contain quotation marks, this will output the url images into a directory called "images", change the name of the directory as you want)

9.Wait and download is finished!
