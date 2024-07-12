# Computer Vision Challenge 2022

This is the repository for the the final project of the computer vision lecture, ministered at TUM in the summer semester of 2022.

## Current status

The app just has a dummy GUI that asks the promps the user for a image and displays on the app main window. Done with MATLAB App Designer.

## Next steps?

### UI
1. After reading halfway through the paper, it seems to me (Leonardo) that we need to enable the user to interactively input two elements: a vanishing point and a background plane. It seems that it is also necessary to make the user input different objects in the foreground, but I'm not sure. However, this seems to be easy after we've done the two aforementioned steps.
2. After the image is uploaded, we want to enter an interactive mode, in which the user can perform the steps mentioned in 1.

### Main algorithm

1. Better understand the paper and the details of the method.

## How to push/compare the app with the current one

The "MATLAB App Designer" outputs a binary file *.mlapp, which we cannot directly compare using git. Please also export the app as a *.m file, naming it main.m before you push it. Let's also not push our changes directly into the main branch. Create an alternative branch and make a pull request, so other people from the team can take a look at it to see if things are good before we substitute existing work.

## Calculating the vanishing points and depth of the image

https://owenjow.xyz/graphics/1948/

## Specify ROI as Binary Mask
Creating Mask: https://www.mathworks.com/help/images/specify-roi-as-binary-mask.html?s_tid=blogs_rc_6
Draw Rectangle: https://www.mathworks.com/help/images/ref/drawrectangle.html
