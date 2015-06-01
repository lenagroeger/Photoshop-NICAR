# Photoshop-NICAR

In this session, we'll learn:

1. How to automate tasks using **Actions**
2. How to create **Droplets** for Actions you use regularly
3. How to make **Animated Gifs** using the Timeline
4. How to use the **Perspective tool**

[Download files here](https://drive.google.com/file/d/0ByZb_bUVlqwjdkgzSnRGRk40Sm8/view?usp=sharing)

##Actions##
Do you find yourself repeating many of the same tasks again and again? You're working too hard. Make an action! In this example, we'll set up an action that converts a bunch of large files (of Oscar-nominated movie poster images) into a smaller size of 200px wide and 72px/in resolution.

1. Open an image in the OSCARS > Best Picture folder: **File > Open...**   ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster1.jpg)
2. Open the Actions pallette: **Window > Actions**   ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster2.jpg)
3. From the dropdown, select **New Action...** (Alternatively, click on the little icon that looks like a Post-It note to create a new action)  ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster3.jpg)


4. Give it a name. Let's say "200px wide", and click "Record" ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster4.jpg)

5. Select **Image > Image Size...**
<br> ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster5.jpg)
6. Set the resolution to 72px and the width to 200px.
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster6.jpg)
7. Still recording, go to File > Save As, and save to new folder (I've called it Best Picture New). You can also do File > Save for Web.
<br>
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster8.jpg)
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster7.jpg)

7. At the bottom of the Actions window, hit "Stop" to stop recording.
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress10.jpg)

8. Close the image without saving your changes.
9. To run your script, open **File > Automate > Batch...**  ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster9.jpg)

10. First we need to pick which action to apply. Since we want to use the 200px action we just created, under "Play" make sure the Action "200px" is selected.
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster10.jpg)
11. Now we need to choose which folder of images we want to apply this action to, and where we want our new images to be saved. Choose your Source folder
(Best Picture) and Destination folder (Best Picture New).
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster11.jpg)

12. Finally, make sure the "Override Action 'Save As' Command" is checked. This will make sure each file gets saved as it's own filename (and not all filed get saved as GRANDBUDAPEST.jpg)
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster13.jpg)

13. Hit "OK", sit back and relax. Your photos will be ready momentarily. When the flickering Photoshop images settle, you should end up with your "Best Picture New" folder full of smaller sized images!
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster12.jpg)

14. *NOTE* If you end up with an image full of empty folders or are seeing a "Save Image As" popup box when you try to apply the action, you may have missed the "Save As" step. [This might help.](http://graphicdesign.stackexchange.com/questions/6842/automatically-saving-in-a-batch-action)


##Droplets##
Droplets make Actions even simpler to use by making them executuable with a simple Drag and Drop.

1. Select **File > Automate > Create Droplet...**
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster13b.jpg)

2. The Droplet menu is much like the Batch menu. Select a location for the Droplet icon to appear, and a folder in which you'd like your files to save (I just saved my droplet to the Desktop, and picked the same Destination folder, Best Picture New.)
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster14.jpg)

3. You should end up with a little icon like this on your Desktop. (Older versions of Photoshop used to have an actual droplet icon, no idea why they replaced it with an arrow.)
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster14b.jpg)

3. Now, instead of going the all the trouble of selecting Batch from the Automate menu, just drag your Best Picture folder on top of the droplet icon. That's it! You're done!
![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/poster15.jpg)


##Droplets 2##
Now let's apply our droplet-making skills to solve a real-life problem that you may encounter if you cover politics. I want every single member of congress's photo, but not in color – in black and white. There are 879 photos, so manually opening up each photo in Photoshop is out of the question. What to do?

1. First, we need all the images. Download them here (note, this only includes the first 23 photos, if you really want all 879 get them here). You should get a folder filled with images like this:
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress1.jpg)

2. Now, open one up in Photoshop.
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress2.jpg)

3. Create a new action, I'm calling mine B&W. Click Record.
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress4.jpg)

4. Go to Image > Mode > Grayscale, and click OK. You should now have a black and white photo!
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress6.jpg)

6. Just for fun, let's add one more step to make the photo sepia colored. Go to Image > Mode > Duotone, and select "Duotone" from the Dropdown.
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress7.jpg)

7. Click on the white box and select a new color (I am choosing Orange)
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress8.jpg)

8. You might need to give this new color a name, but when you hit OK it should have given your photo a nice sepia effect!
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress9.jpg)

9. Now let's save it. File > Save for Web, and save it to a new folder (I called it Congress Photos New)

10. Stop recording this action by hitting the "Stop" button
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress10.jpg)

11. Now let's go straight to making a droplet. **File > Automate > Create Droplet...**

12. I'll save this droplet as "B&W" to the Desktop, and select "Congress Photos New" as my destination folder.
*    ![](https://github.com/lenagroeger/Photoshop-NICAR/blob/master/screengrabs/congress11.jpg)

13. Now I'll drag my Congress Photos folder onto the droplet, and wait for my computer to do all the work! You should end up with a 879 newly sepia-fied images. Hurray!

##Animated Gifs##
Do you have an interactive graphic you'd like to promote on the front page? Animated Gifs are a great way to draw attention to interactive work.

1. Start with a series of images or screenshots from your interactive.
2. Open one of the images in Photoshop.
3. Drag and drop your other images onto the stage. This will bring them into your file as separate layers.
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/GifLayers.png)
4. Select **Window > Timeline** from the toolbar. This will open a new panel in Photoshop.
5. From the Timeline panel, select "Create Frame Animation" from the dropdown, then click the dropdown.
6. This will pull one layer into the timeline window.
7. From the dropdown in the upper right of the Timeline window, select "Make Frames from Layers"
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/FramesFromLayers.png)
8. Make sure your frames are in the correct sequence, then set the duration for which you'd like each to display
*    ![](https://github.com/chriscanipe/Photoshop-NICAR/blob/master/screengrabs/SetFrameDurations.png)
9. Select **File > Save for Web**
10. Select Gif as your save format. At the bottom of the window, you'll also be able to set the number of times you'd like the animation to loop. For a homepage promo, it might not be appropriate to loop infinitely. Let's set it to loop 3 times.
11. Save and you're done. Woot!
([The source files here are from this WSJ interactive:](http://graphics.wsj.com/ukraine-rebel-maps/))

##Perspective Tool##
We also covered the perspective tool through a tutorial I borrowed entirely from Proublica's Lena Groeger, so rather than try to replicate it,I'm jsut going to link to her tutorial here:
[Reorienting documents and images using the Perspective Tool (Exercise #2)](http://lenagroeger.s3.amazonaws.com/cuny-spring14/photoshop.html)
