# SettingUpFrameworkFromScratch
SETTING UP FRAMEWORK FROM SCRATCH USING SPECFLOW & SELENIUM WITH VISUAL STUDIO IDE
C#
1.	DOWNLOAD AND INSTALL VISUAL STUDIO
2.	INTERGRATE SPECFLOW EXTENSION WITH VISUAL STUDIO IDE
3.	CREATE NEW TEST PROJECT
4.	CREATE FOLDER STRUCTURE
5.	ADD NUGGET PAKAGES
6.	CREATE FIRST FEATURE FILE & STEP DEFINITION
ii. CREATE YOUR PAGE OBJECT
iii. CREATE YOUR UTILITIES
7.	WRITE YOUR CODES & RUN YOUR TEST
STEP 1- DOWNLOAD AND INSTALLING VISUAL STUDIO
GO TO https://visualstudio.microsoft.com/
CLICK ON DOWNLOAD FOR WINDOWS
AND CLICK ON COMMUNITY 2017(ITS A FREE VERSION)
 
IT SHOULD START TO DOWNLOAD
DURING THE INSTALLATION IT WILL ASK YOU WHAT TI INSTALL
CHECK THE .NET DESKTOP DEVELOPMENT
THEN ISTALLATION CONTINUE
THEN IT WILL ASK YOU TO RESTART YOUR SYSTEM
STEP 2- INTERGRATE SPECFLOW EXTENSION WITH VISUAL STUDIO IDE
(For SpecFlow to properly work on VS2017, we need to add the SpecFlow as an extension to VS)
On Visual Studio
Select Tools
Select Extensions and updates
 
From the menu in visual Studio
Click/switch to online on the left
Enter “SpecFlow” in the search in the search field on the top right
Click download to start “downloading” the extension
 
NOTE- THIS IS VERY IMPORTANT AS YOU ONLY DO IT ONCE FOR YOUR VISUAL STUDIO. IF YOU HAVE A NEW LAPTOP YOU WILL HAVE TO DO IT AGAIN WHEN YOU INSTALL VISUAL STUDIO
Then restart your system
STEP 3-CREATE NEW TEST PROJECT
Click File
Click New
Click Project
 
Select Test
Select Unit test project
 
Enter the name of the Project i.e Testing
Browse to store the Project in a folder
Check create directory for solution to create a folder for the solution
Click ok
And your solution will be created
STEP 4-CREATE FOLDER STRUCTURE
Right click on the Project- Testing (Note-the solution)
Select Add
Select New folder
 
Create the following folders:
1.	Features
2.	PageObjects
3.	StepDefinitions
4.	Utilities
• Features- (This is where SpecFlow feature files will be stored)
• PageObjects-(This will store different classes for each of the page that you will be inspecting)
• StepDefinitions-( From you Feature file you will creating some steps. You steps will gi into Step definition folder)
• Utilites- (Called helper classes will contain any class or file that is not in the three above will be stored here)
STEP 5- ADD NUGGET PAKAGES
Right click on Solution
Click on manage Nugget packages
 
Click on Browse
In the search box ,search for the packages i.e SpecFlow
Select SpecFlow and click install.
Add the following required 11 packages;
• Nunit
• NUnit.Console
• NUnit3TestAdapter
• SpecFlow (Version- 2.4.1)
• SpecFlow.Nunit(Version- 2.4.1)
• Selenium.WebDriver
• Selenium.Support
• Selenium.WebDriver.IEDriver
• Selenium.Firefox.WebDriver
• Selenium.WeDriver.ChromeDriver
Arrow down will show a package has been installed
STEP 6.1-CREATE FIRST FEATURE FILE & STEP DEFINITION
• Right click on Features
• Click on Add New Item
Select SpecFlow on the left and select SpecFlow Feature file(if you don’t see it that mean you have not integrate SpecFlow with your Visual Studio. What you need to do back to STEP 2 to integrate Specflow.)
 
• Write the name of your Test i.e Registration and click add
• Your Feature file will displayed with examples of what is expected
• Delete the steps and write your own steps and scenario using (GIVEN,WHEN,AND,THEN).
• Right click on any of the purple step and click Generate Step Definition
 
It should display this window
 
Click generate and save it in Step Definition folder under your project. The steps will change from purple to black or white.
 
The steps will show on the right under step definition folder
 
STEP 6.2- CREATE YOUR PAGE OBJECT
• Right click on PageObject
• Click on Add New Item
• Click on code on the left
• And select Class
 
• Rename Class to your project name e.g. TestingPage
• And click Add
 
You should see the screen below
 
STEP 6.3- CREATE YOUR UTILITIES(HOOKS)
• Right click on Utilities
• Click on Add New Item
• Click on Specflow on the left
• And select Specflow Hook (Event Binding)
• And click Add
 
 
You should see the screen below
 
WRITE YOUR CODES & RUN YOUR TEST

