# radiosity
Matlab code for solving the radiosity equation for lighting in computer graphics virtual spaces. 

The code is related to the examples I show in the YouTube video https://youtu.be/krIVZvzlxUQ Note that the video language is Finnish but that it has English subtitles. 

Simplest example: empty room. First run "radiosity_emptyroom_Fcomp.m" in Matlab to create the geometric form factor matrix F, which will be saved to a file in the subfolder ./data/. Then you can run "radiosity_emptyroom_BW.m" to create a black-and-white image of a lit room, and "radiosity_emptyroom_color.m" for a color image. If you want more details (smaller patches), you can make n larger in "radiosity_emptyroom_Fcomp.m". Note that too large n value will cause your computer to run out of memory, so it is a good idea to increase n gradually. 
