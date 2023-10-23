# Shiny Server Installation Instructions 
The application can be installed either within the BIBBOX environment or as a stand-alone solution. Installation instructions can be found within the BIBBOX, followed by setup instructions required once the application has been successfully installed.

## Installation within in the BIBBOX

Once you've selected the desired App for your BIBBOX instance, you can choose from the available versions, as shown in the following figure.

![Screenshot01](assets/install-screen-00.png)

Clicking "Install App" will open a new window, as illustrated in the following figure. Here, you can define the necessary entries. Some fields come pre-filled with suggested options, and if left unchanged, these default values will be used as the entries.

![Screenshot02](assets/install-screen-dialog.png)

After confirming by clicking "Install," the App will be installed as a BIBBOX instance. Once the installation is complete, you only need to follow a few steps to use the App for the first time, which are described below.

## Setup after BIBBOX or stand-alone installation

### Start Shiny

Be patient this can take some time.

When opening you should be greeted by a welcome page:
![Screenshot01](assets/install-screen-01.png)

#### Sample applications
You have a couple of sample applications available to get a feeling for shiny. Just add one of the following extension to your URL:
  * /sample-apps/hello/
  * /01_hello/
  * /03-reactivity/
  * /04_mpg/
  * /05_sliders/
  * /06_tabsets/
  * /07_widgets/
  * /08_html/
  * /09_upload/
  * /10_download/
  * /11_timer/

#### Deploy own applictaion

To deploy your own apps you have to place them in the `data/shinyapps` directory or on the bibbox the `/opt/bibbox/instances/YOUR-SHINY-SERVER-ID/data/shinyapps` directory.

## After the installation
Have a nice ride with the Admins youngtimer.

![FINAL](assets/install-screen-final.jpg)
