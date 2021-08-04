TITLE : MUSIC PLAYER 
INTRODUCTION
In this project, we have created a Music Player Application in Python using the Tkinter and Pygame module.
In our daily life, we see every person has a hobby and that is listening to music. So in order to listen to music, they all need a Music player(hardware or software) where they can play their favorite songs. And we have to install this music player on our computer, based the Operating system i.e Windows, Macintosh, Android, Linux, etc. Then we can listen to our favorite songs.
Now we have created a Music Player using Python code from scratch.
Libraries used for Music Player Application:
The Libraries we used in our code :
1. Tkinter
We had already told you in the title of this page that we are going to use the Tkinter library, which is a standard library for GUI creation. The Tkinter library is most popular and very easy to use and it comes with many widgets (these widgets helps in the creation of nice-looking GUI Applications).
Also, Tkinter is a very light-weight module and it is helpful in creating cross-platform applications(so the same code can easily work on Windows, macOS, and Linux)
To use all the functions of Tkinter you need to import it in your code and the command for the same is:
 
2. Pygame module
Pygame is a Python module that works with computer graphics and sound libraries and designed with the power of playing with different multimedia formats like audio, video, etc. While creating our Music Player application, we will be using Pygame's mixer.music module for providing different functionality to our music player application that is usually related to the manipulation of the song tracks.
Command used to install pygame is:
 
3. OS module
There is no need to install this module explicitly, as it comes with the standard library of Python. This module provides different functions for interaction with the Operating System. In this tutorial, we are going to use the OS module for fetching the playlist of songs from the specified directory and make it available to the music player application.
To use this module in your code you need to import its and command for the same is as follows:
 
After importing Libraries and modules, now it's time to create a basic window where we will add our UI elements .
MusicPlayer Class
The functions defined in the MusicPlayer class are:
1.The addsongs() Function
 
2.The deletesong() Function
 
3.The playonline() Function
 
4.The Play() Function
 
5.The Pause()  Function
 
6.The Stop() Function
 
7. The Resume() Function
 
8. The Previous() Function
 
9. The Next() Function
 
10. The Root Window 
 

Buttons in the Music Player
1.Play Button
2.Pause Button
3.Stop Button
4.Resume Button
5.Previous Button
6.Next Button
On clicking on a particular button , the command will take place accordingly.
So this was all about building the Music Player Application using Tkinter.
