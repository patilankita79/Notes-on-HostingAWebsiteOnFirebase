# Notes on hosting a website on Firebase
These are my notes on how to host a webpage or website on firebase. 
Notes contain steps to host a webiste on firebase which is a cloud service for database, authentication, etc. 
<hr>
<b>Author: </b>Ankita Patil
<hr>
<h2> Steps to host a webpage/website on firebase </h2> 
<h4>Step 1:</h4>
Create a firebase account
<h4>Step 2:</h4>
Go to console
<h4>Step 3:</h4>
Select the option => Add a project. 
<i>I have added a project named <b>ParticleJSEffect.</b></i>
<h4>Step 4:</h4>
In order to use firebase, you need to install node JS on your machine.
<h4>Step 5:</h4>
Now, install firebase on your machine. In command prompt, type the following commnad
<blockquote>$npm install -g firebase-tools</blockquote>
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/1_InstallFirebaseTools.png" />
<h4>Step 6:</h4>
Now, you have to login to the firebase. In the command prompt, type the following command<br/>
<blockquote>$firebase login</blockquote><br/>
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/2_FirebaseLogin.png" />
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/3_Authentication.jpg" /><br/>
Now, you have to authenticate with credentials and after authentication is successful, you are logged in to firebase successfully.
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/4_LoginSuccessful.png" />

<h4>Step 7:</h4>
Firebase looks for public folder, so put all the website files in public folder.
Make sure that main page of your website is index.html
Otherwise firebase will not recognize and won't host your website
<h4>Step 8:</h4>
Now, open the command prompt in the project directory OR change the directory to the location where project is stored. In the command prompt, type the following command. Following command initializes firebase in this particular folder<br/><br/>
<blockquote>$firebase init</blockquote><br/>
<img src ="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/5_Initialize.png" />
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/6.png" />
<h4>Step 9:</h4>
Since we want to host the website, select <b>Hosting</b> to configure among given choices.<br/>
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/7_SelectHosting.png" />
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/8.png" />
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/9.png" /><br/>
As we have all the related files of website in a folder named <b>public</b>, write public to the question asked.<br/>
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/10.png" />
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/11.png" />
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/12_InitializationComplete.png" />

<h4>Step 10:</h4>
After firebase initialization is complete,we have to deploy the project on firebase. In the command prompt, type the following command. This command deploys the website in the project folder which we created initially in the firebase.<br/><br/>
<blockquote>$firebase deploy</blockquote><br/>
<img src ="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/13_Deploy.png" />
After deployment, we get a hosting URL where our website is hosted.<br/>
<img src="https://github.com/patilankita79/Notes-on-HostingAWebsiteOnFirebase/blob/master/Screenshots/14_DeployComplete.png" />

<hr>
