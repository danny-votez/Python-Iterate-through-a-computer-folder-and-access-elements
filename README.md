# Python-Iterate-through-a-computer-folder-and-access-elements
This case illustrates the iteration through a computer folder and print out the names of images, ending with various specified image formats.

<pre>
<code>
# In this illustration, we create a Python program that iterates through a folder
# The aim is to read and find files of certain type, and print out their names
# This example will illustrate .png, .jpeg, and .jfif files

import os
directory = 'C:/Users/danne/Pictures'

for filename in os.listdir(directory):
    if filename.endswith(".png"):
        print(filename)
    elif filename.endswith(".PNG"):
        print(filename)
    elif (filename.endswith(".jpeg")):
        print(filename)
    elif filename.endswith(".jpg"):
        print(filename)
    elif filename.endswith(".jfif"):
        print(filename)

</code>
</pre>



============ HERE ARE SAMPLE RESULTS ============

<pre>
<code>
"""
=============SAMPLE OUTPUT ================
03uofpeople-degree-jumbo.jpg
112.png
1_BC0BMHY9BVxgd4lD3riwDQ.jpeg
1_CdcBI65zoa5X6kAw52qGDA.png
220px-Abraham_Maslow.jpg
279012797.jpg
3c1b0394431041.5e7e73ba1c55e.jpg
439144.jpg
439176.jpg
6444317_0.jpg
Abraham+Maslow.jpg
Access Granted.jpeg
Access Granted11.jpeg
Acq-Hire.jpg
africa_en-feature-your-new-home-office-243706024.jpg
AI.jpg
Ambition.jpg
Ayn Rand.png
B8TEa5VCYAAzs_G.jpg
be.jpg
Benz.jfif
Blue Sofa.jpg
Ci7z5_HW0AE7yiH.jfif
Computing.jpg
Cute.jpg
ddddd.PNG
Denial.jpg
Do or Do Not,,,,,,There is No Try.jpg
download (1).png
download.jpg
download.png
Dream.jpg
Due_2PYV4AA_6Bm.jpg
Dyer and Blair.PNG
Elizabeth Holmes Theranos.jpg
Eooh1N0XIAAsEsk.jpg
Eqj55a3XAAAUUxg.jfif
Eqj55DEXcAAIsIQ.jfif
EqkwzFlXAAIGRBN.jfif
Grand Canyon University.PNG
Hack.jpeg
il_570xN.1156048984_dci3.jpg
images (1).jfif
IMG-20191231-WA0000.jpg
IT'S NEVER TOO LATE..PNG
Keanu-Reeves.jpg
knows-chemistry-knows-phy-knows-nothing-_cersei-18819801.png
L01DS106-CANCUN.jpg
Language Creators.jpg
LeBron James.png
Lee Seedol.jfif
lehman-brothers-008.jpg
Lil Wayne.jpg
Linus Code.jpg
Linus.jpg
linustorvalds3-2x.jpg
maxresdefault.jpg
Microsoft Diary.PNG
Nes .jpg
Nes.jpg
New One.png
pain.jpg
Palm Exotica.jfif
Passport Image IMG_5035 2020.jpg
Python Code.jpeg
quote_296.jpg
Thomas Edison.jpg
Togo 2019.jpg
Togo2019.jpg
troy 4.jpg
tumblr_ml9o7eznyS1rohqbfo1_500.jpg
uber-marketing-strategy2-1.jpg
Unlocked.jpeg
unnamed.jpg
Upstairs.jpg
versace-praised-for-banning-use-of-kangaroo-skin.jpg
Wall-Street-Bull-China-Hustle.jpg
We Are All Being Played.jpg
Workstation.jpg
"""
</code>
</pre>
  
