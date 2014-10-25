Escape201
=======

The following is the appendix to install Android Studio and to verify that it was installed correctly...

1. Check that your computer has at least 4 GB of RAM and has Windows XP or a newer operating system installed.  
     NOTE: Alternatively you can install on a Mac, but I was unable to test on a Mac so I will only cover for Windows.

2. Install Java RE and the Java JDK by going to the following link <https://ninite.com/java-jdk/>, downloading the executable and running it.

3. Once that finishes, go to <https://developer.android.com/sdk/installing/studio.html> and click on “Download Android Studio Beta”  then read through and accept the Terms and Conditions to start downloading the installation package for Android Studio.

4. Once the download finishes, run the executable and click next through the wizard that appears until you get to the last window in which you will uncheck “Start Android Studio” and then press Finish.

5. Find the installation location of Android Studion in your Start menu or Tiles screen. Right-click on the Android Studio icon and choose “Run as Administrator”.

6. If you installed Java and the JDK correctly, you should see a Welcome screen or you might see a screen asking if you wish to use the settings from a previous version of Android Studio, at this dialogue box just click Ok. 
NOTE: If you get an error relating to the SDK, then you will need to configure your class PATH to continue. To do this go to <http://javarevisited.blogspot.com/2013/02/windows-8-set-path-and-classpath-java-windows-7.html> and follow the steps provided.

7. Once you are at the “Welcome to Android Studio” screen, press the option labeled “Configure”.

8. On the next screen that appears, choose “SDK Manager” and wait for a new Window to appear.

9. In the new window, check all of the boxes that are under the grouping of Android 4.3 (API 18) as well as the Android Support

10. Repository, Android Support Library, and Google USB drive from the Extras folder, and then press install packages.

11. Now, review and accept the license for each category that appears and press “Install”

12. Once this process completes, close and then reopen Android Studio.

13. At this point, choose “Start a new project” and then press “Continue” until you get to the last screen at which point you will press “Finish”.

14. On this first use of Android Studio, many more files will be downloaded and you will need to wait for all of this to finish before continuing.

15. Once everything is downloaded, select Tools>Android>AVD Manager. Go to the Android Devices tab and click on “Nexus 4” to highlight it then press “Create AVD …”

16. On the next window, choose “ARM” for the CPU, choose “Skin with dynamic hardware controls” for Skin, and choose 512 for the RAM, and then press Ok and ok again.

17. Click on the newly created emulator and the press the “Start” button and then press the “Launch” button.

18. Once the emulator has booted and is at the Home screen, minimize it and run your code.

  If all goes well, it will install and start a simple program that displays “Hello World” on your emulator.
