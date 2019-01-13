# GoogleImagesWebExtractor

This repository contains files necessary to extract google images from web search. 

The way is done is following:
1.Go to google and search images you want to download, go to "images".
2.Scroll down, and stop scrolling whenever you think the rest of the image below are irrelevent or not needed.
3.Open google web javascript console: On Windows and Linux: Ctrl + Shift + J. On Mac: Cmd + Option + J.
4.Copy every line of code of js_console.js into the google javascript console(you will get some errors, but do not worry, it's going to work out fine).
5.When you finish the last line of code a text file will be downloaded, and put this into your folder where you downloaded the two files
6.Go to terminal/command prompt, and go to the direcotry where you saved this two files(by cd command).
7.Enter "# python download_images.py --urls urls.txt --output images" (don't contain quotation marks, this will output the url images into a directory called "images", change the name of the directory as you want)
8.Wait and download is finished!
