# JeremySorensen.github.io

To use the Big Wheel go to http://JeremySorensen.github.io

Use of the site is restricted to non commercial personal and church use.

You can also download the whole folder as a zip file from this github page (Scroll up and find the green "Clone or download" button, click it and then click "Download Zip). If you open index.html in a web browser it will work without an internet connection.

Choose which version you want and mirror your display onto a TV using HDMI, Apple TV or something.

This is a activity where kids tap the wheel (on the device screen) to spin it and it chooses how a song will be sung.
There are two versions, one which requires candy bars (full size Rolo packs and fun-size 3 Musketeers bars) and one that doesn't require any candy.

The ways to sing are:

 * Buzz Like a Bee
 * Stick Your Tongue Out
 * New First Letter - Start every word with the same letter, be careful which letter you choose. Don't use F, S, D or some other letters. J, W, Z, M should be good.
 * Stand On One Foot
 * Rub Belly, Pat Head
 * Teachers vs Kids - The teachers sing, then the kids, take a vote at the end (the kids always win because they have more votes)
 * Three Musketeers - The child picks two friends, the three of them sing in front and then they get fun-sized 3 Musketeers bars
 * Solo For Rolo - The child sings in front, then they get a pack of Rolos
 * Class Act - The whole class comes up and sings (no candy though)
 * Staccato
 * Soft
 * Fast
 No candy only:
 * Opera - sing like an opera singer
 * Every other word - One side of the room sings the even words, the other sings the odd ones. For more challenge everyone sings only the even, or only the odd words.
  
To change the words you have to edit the files, either candy.html or nocandy.html in Notepad (not word or something like that.)
  
Find this part
  
```
  
var words = ["Buzz Like a Bee", "Stick Your Tongue Out", "New First Letter",
             "Stand On One Foot", "Rub Belly, Pat Head", "Teachers vs Kids",
             "Three Musketeers", "Solo For Rolo", "Class Act",
             "Staccato", "Soft", "Fast"];
```

And change the items in Quotes. If you use the folder locally (see part above) that will just work. To make it available online, you will have to fork the project on Github. (Look up tutorials.) If you have a set of items you desparately want me to put online email me and I can put up a new version.             

The code is just a combination of several stack overflow posts, which are in the comments.

The code is Licensed under Apache 2 or MIT at your option. 
  

