# ZupProject
Repository Containing Zup Files
Project by Thomas Bessa Ferreira
Last Update: 09/16/2015

To open the project and make it work you should:
  1. Download the file ExploreMars.rar from GitHub repository wherever you want in your local folders
  2. Using the file decompressor of your choice and the option "Extract Here" you will have the folder ExploreMars (I highly recommend WinRAR seeing that I used it for compression: http://www.rarlab.com/download.htm)
  3. Open your Intellij IDEA (wich can be downloaded in the following link: https://www.jetbrains.com/idea/download/)
  4. Select the Import Project option from the initial screen.
  5. When the destination is asked make sure you find and select the folder ExploreMars
  6. Click the OK button
  7. Select the Option: Create project from existing sources. Click Next.
  8. Set up a project name. I will recommend here that you keep the Import Wizard suggestion wich will probably be "ExploreMars".
  9. A window will Pop-Up saying that .idea already exists. Choose Yes to replace it.
  10. Click Next in the following window. Make sure you don't unmark the selected directory in the box.
  11. The library importation section will be empty so just click next.
  12. Module importation section from the wizard will have one marked folder. Just click next here.
  13. A window will Pop-Up saying that .iml already exist. Choose Overwrite and replace it for a new one.
  14. Next window will be SDK selection. I highly recommend that you select "jdk1.7.0_75" since this is the one I worked with. After selecting it click Next.
  15. Click Finish and the project will be opened.
  16. By navigating in the project tab you will find a folder named src. Open it.
  17. Within it there may be three files: Main, Rover, RoverTest.
  18. You can take some time to examinate the code of each file if you want it.
  19. When you decide to move on, double click the RoverTest to see its code.
  20. Due to importantion some of the code is messed up. Nothing to be alarmed. To fix it you only need to click on the code wherever it is written @Test. Make sure the blinking bar wich represents the insertion cursor is anywhere on the word Test.
  21. By pressing ALT+Enter on your keyboard a context menu will appear showing some options.
  22. Look for the one wich contains a red light bulb and the text: Add JUnit to classpath. Select it by clicking on it.
  23. You will know you did the right thing if the "@Test" changes its color.
  24. Now back to the project folder src, where you first saw the file RoverTest.
  25. Click with the rigth button over this one file (RoverTest).
  26. A context menu will appear. Choose the option Run 'RoverTest'.
  27. After a little time a subdivision of the IDE will appear showing the following statment: "Process finished with exit code 0"
  28. This indicates that all tests ended up well, showing the expected result.
  29. Any other doubts contact me. thomas.bessa@gmail.com
