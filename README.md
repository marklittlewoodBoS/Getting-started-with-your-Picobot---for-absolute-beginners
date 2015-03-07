# Getting-started-with-your-Picobot---for-absolute-beginners
A newby guide to getting started with your PicoBot

This is a guide to help you get going with your PicoBot if you have NO programming experience whatsoever. (i.e. ME :-)) This is some of the things that I wished I knew when I was starting out. I have been learning to programme Arduino's for a few months and claim no competence. Just as well as I have none. 

As you are going to be a programmer now, as well as a maker, you might as well start by setting yourself up with a GitHub account. This is where almost all programmers keep their code so they can share it with others, make changes, manage different projects and all sorts of stuff. More importantly, it is where the sample programmes for the PicoBot are. The basic GitHub accounts, all you need for now, are free. An account will allow you to use the code provided simply and also make and save your own changes. You should also download the GitHub programme. (Pros call it 'Git')

ONE
Create an account in GitHub to use example code.

Go to https://github.com/ and Sign Up for a new account. (Miss this is you already have an account obviously!).

Now download Git.

The Windows version is here: https://windows.github.com/
The Mac version is here: https://mac.github.com/

Download a small .exe file and then install. The install process will download a larger (44Mb file). 

When this is installed, you can sign in using your user name and password then make changes to your code, access other people's code with their permission (or if it is public), and save code in a 'Repository' on your own computer. You can synchronise your repository with the online version of GitHub very simply.

Now to get going with the PicoBot. There are a few things you need to do to get your PicoBot to talk to your computer and do the amazing things you will no doubt end up telling it to do.

TWO
Download the Arduino IDE. 

This is the software that allows you to control the PicoBot and all sorts of other devices. You can download and install it here. http://arduino.cc/en/Main/Software Just download and install.

THREE
Install the Device Driver for the PicoBot. You can find it here: http://www.silabs.com/products/mcu/Pages/USBtoUARTBridgeVCPDrivers.aspx Download it, then unzip.

FOUR
Open the Arduino IDE and point the Arduino Interface at the Driver by going to Tools -> Drivers in the Arduino Interface then browsing to the unzipped file.

FIVE
Choosing the correct Board. You need to set up the Arduino Interface so it is communicating with the correct Board. In the Arduino Interface go to Tools -> Board and choose 'Arduino Uno'. It is important to choose the correct board as each one has slightly different characteristics and while some may work, the Picobot may not behave as expected. Sometimes choosing the wrong board will cause your PicoBot to turn into an evil robot with killer instincts though this is unlikely, it is more probable that it just won't work.

SIX
Download some Libraries - reference programmes that will make the PicoBot work. 

Start by getting Martin Bateman’s library. Go to https://github.com/batemanm/picobot and download this. In your Arduino IDE, go to Sketch -> Import Library -> Add Library. Navigate to the downloaded Zip file and you are done.

SEVEN
Choose some of the example programmes and copy and paste from GitHub https://github.com/4tronix/Picobot/tree/master/Software/Picobot/ into the Arduino RDE. Test, Upload, and off you go.
