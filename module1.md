---
layout: module
title: Module 1&#58; Setup the project
---

### Create a new Project
1. Create a PhoneGap project using either the PhoneGap CLI or the PhoneGap Desktop Application you learned in the first workshop. For example:

        phonegap create pgworkshop com.yourname.workshop PGWorkshop 
      
2. Navigate into the newly created project folder:

        cd pgworkshop        

### Replace Contents
1. The final application project we'll be using is located [here](https://github.com/hollyschinsky/pocket-guide). It contains a **solutions** folder
with the final module code per step to reference. If you want to work along, a starter project beginning with module 1 is available [here](https://github.com/hollyschinsky/pg-workshop). 
Download the zip file for the [starter project](https://github.com/hollyschinsky/pg-workshop/archive/master.zip) or clone it with git:

        git clone https://github.com/hollyschinsky/pg-workshop

1. Now copy the **www**, **config.xml** and **pgbot-love.png** files from the starter project into your newly created project root and overwrite the files currently there.

  The **config.xml** file has some settings which will automatically install the project plugin dependencies, but you could optionally add them manually. The **pgbot-love.png** 
  is the default icon for this application referenced in config.xml.

  >If the network connection allows for downloading the [full project and solutions](https://github.com/hollyschinsky/pocket-guide/archive/master.zip) then you could alternatively copy over
  the contents of **solutions/www1** into your project **www** folder, ensuring the folder name stays **www**. Then copy the config.xml and pgbot-love.png from the root
  into your project root and replace the current config.xml.

### Run the Initial Application
1. Serve and pair with the PhoneGap Developer App from the PhoneGap CLI or PhoneGap Desktop: 
  
   - **From PhoneGap CLI**            
     1. Run `$ phonegap serve`
     2. Connect to the URL reported from the `serve` command in the PhoneGap Developer app on a mobile device
 
     
   - **From PhoneGap Desktop**
     1. Click the play **>** button if your project is not active 
     2. Connect to the URL reported from PhoneGap Desktop in the PhoneGap Developer app on a mobile device
            
   - **Advanced Option:** those with proper local setup can run on device/emulator with PhoneGap CLI with one of the following:
        
            $ phonegap run ios
            $ phonegap run ios --device
            $ phonegap run android             
            $ phonegap run android --device               
      
      > This option requires a mobile SDK setup. If you have Mac and Xcode you should be able to use iOS, but Android requires [additional SDK installation and setup](http://developer.android.com/sdk). 

       **NOTE:** If you don't have the PhoneGap Developer App, you can still run the app in your browser by opening the index.html file in the browser, you will just have limited 
       functionality.    

2. Ensure you see the application load with a listing of Amsterdam's most popular locations. Try typing in a few characters to see the filtering
 on the name.    
    
    <img class="screenshot-lg" src="images/main-view.jpg"/>
 
  **Note:** We'll be adding additional features as we go along so not everything will be functional at this point.

> Part-by-Part solutions are available in the [repo](http://github.com/hollyschinsky/pocket-guide/solutions) folder for each lesson. The number of the lesson
corresponds to the folder and represents the completed lesson for that module. 


<div class="row" style="margin-top:40px;">
<div class="col-sm-12">
<a href="index.html" class="btn btn-default"><i class="glyphicon glyphicon-chevron-left"></i> Previous</a>
<a href="module2.html" class="btn btn-default pull-right">Next <i class="glyphicon
glyphicon-chevron-right"></i></a>
</div>
</div>
