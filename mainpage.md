# Welcome to the Android Development Intern Project (2013) #

https://abb-interns-2013.googlecode.com/hg/photo%20(4).JPG
<br>
<hr />
<font color='Black' size='18' face='Eras Bold ITC'> Introduction </font> <font size='15' face='Eras Bold ITC'> </font>
<hr />
<h2>General Description</h2>

Currently the ABB (Totalflow) G4 Product line uses a PC Client based software (PCCU version 7.29) for local and remote configuration via serial and IP bases connections. The purpose of this project will be to develop an android application that will provide a subset of PCCU functions to a field person for access via an IP or Bluetooth connection.  This application will not provide all of PCCU functionality but only the features defined in the scope section of this document.<br>
<hr />
<h2>Product Perspective</h2>

The development of this product will resolve issues of field technicians ineffectively using time to connect to G4 devices via direct cable connection. The customer will solely benefit by the use of this product when doing any pipeline measurement readings locally and through the use of the android application with a Bluetooth dongle.<br>
<br>
The stakeholders for this product are internal. Research and Design must use this document for reference this document when tracing back to marketing requirements. The quality and support of the product must therefore be internal and explicitly documented.<br>
<hr />
<h2>Product Functions</h2>

The product takes measurement data from the ABB Totalflow G4 devices and displays the data on the user’s Android mobile device. The user will now be able to remain in their vehicle while taking measurement readings.<br>
<br>
The product shall be easy for any user to navigate to all of the main features providing the main functions below:<br>
<br>
•	Android User Interface<br>
<br>
•	Wireless Data Transfer<br>
<br>
•	Saving and Sharing Files<br>
<br>
<hr />
<h2>User Characteristics</h2>

Field Technicians taking any data measurements from G4 devices can use product. The primary method of use shall be for connecting to any G4 device that does not have a networked connection already established to transfer the data to the web server.<br>
<br>
Technicians need familiarity with G4 series including models: XFC, XRC, and uFlo<br>
<br>
Technicians need familiarity with Android OS including: Ice Cream Sandwich and Jelly Bean<br>
<br>
Technicians shall have basic understanding of establishing a Bluetooth connection between two devices. Documentation shall be provided with Bluetooth being purchased along with G4 device.<br>
<br>
Obstacles encountered may include: loss of Bluetooth connection due to out-pacing the effective range of the Bluetooth connection. Specialized skills may include: troubleshooting Bluetooth connectivity.<br>
<hr />
<h2>General Constraints</h2>

The product shall be designed using Android development environment, Android SKD. The necessary tools in the Android SDK allow for creation of the user interface to show the required measurements coming from the connection to G4 device. Interface shall be made between the application and Android Bluetooth settings.<br>
<br>
TCI Tool Kit shall be used as a resource for gathering information on the registers necessary to gather information from the G4 device. The code used in the G4 devices shall then be ported over to the Android SDK to replicate the process for the Android application.<br>
<br>
G4-µFlo Device shall be used to test the final product for gathering necessary information listed in the Overview of Requirements.<br>
<br>
Bluetooth dongle shall be used on the G4 devices to establish a connection to the Android device and application. Bluetooth adapter will either be provided as an option included with purchase of G4 device or part number shall be listed for Bluetooth dongle needed to perform connection to Android device and application.<br>
<br>
<hr />

Reviewing Code<br>
<br>
<a href='https://abb-interns-2013.googlecode.com/hg/Review%20Comments.xlsx'>Comments Excel Sheet</a>

<a href='https://abb-interns-2013.googlecode.com/hg/Totalflow%20Code%20Review%20Procedures%20and%20Checklist.docx'>Checklist Word Doc</a>

<hr />

MCU Android App<br>
<br>
<a href='https://abb-interns-2013.googlecode.com/hg-history/b48c54b5eb6680eae27f57840347d8d9d7707b5a/MCCU.apk'>APK Download</a>

<a href='https://abb-interns-2013.googlecode.com/hg-history/53412870f105049c864c8dcde4e03608e62610ba/README.txt'>README.txt</a>

<hr />

Having trouble using the Mercurial??<br>
<br>
<a href='http://mercurial.selenic.com/wiki/Tutorial'>http://mercurial.selenic.com/wiki/Tutorial</a>

<a href='http://stackoverflow.com/questions/1397357/hg-commit-nothing-happens'>http://stackoverflow.com/questions/1397357/hg-commit-nothing-happens</a>