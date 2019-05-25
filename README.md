# File-Uploads-to-Google-Drive-Using-OAuth-2.0
In this post we will be implementing How to Upload Files to Google Drive using OAuth authentication.

For this application we need to create a project in Google Developers Console and get your client id and client secret.

So just create a new project from the created projects.

![newproject](https://user-images.githubusercontent.com/50908984/58368945-91df1a80-7f11-11e9-92dc-468feae616e9.jpg)
![OAuthconsentScreen](https://user-images.githubusercontent.com/50908984/58368994-37928980-7f12-11e9-97cf-05f014328125.png)



After selecting the project just click on create credentials and create a brand new OAuth Client ID.


![Createcredentials](https://user-images.githubusercontent.com/50908984/58369000-46793c00-7f12-11e9-8121-590e7c16e486.jpg)


After selecting the project just click on create credentials and create a brand new OAuth Client ID


![Applicationtype](https://user-images.githubusercontent.com/50908984/58369004-5264fe00-7f12-11e9-8fb1-b3e5b02714be.jpg)

![Authorized](https://user-images.githubusercontent.com/50908984/58369009-5abd3900-7f12-11e9-9145-37da3cb76be0.jpg)



Click on the create button to generate the client id and client secret.


![Client id and secret](https://user-images.githubusercontent.com/50908984/58369019-67419180-7f12-11e9-8e4f-34172250e789.jpg)


Extract the downloaded project into WAMP/Apache24 server path. (C:\wamp\www) or (C:\Apache24\htdocs)


Extract GoogleDriveFileUpload.zip file. (C:\Apache24\htdocs\GoogleDriveFileUpload).


![location](https://user-images.githubusercontent.com/50908984/58369024-732d5380-7f12-11e9-9c01-f8f682832075.jpg)


Now run your Web app using Apache server (http://localhost/GoogleDriveFileUpload).

![weblocate](https://user-images.githubusercontent.com/50908984/58369034-7f191580-7f12-11e9-8c61-5d437b4999d7.jpg)

![indexpage](https://user-images.githubusercontent.com/50908984/58369036-86402380-7f12-11e9-92e9-aa0122ca9950.jpg)


Press “Upload Files to Drive” button and proceed. You'll ask permissions by Google Drive API for file management.

![b_Authorizedmail](https://user-images.githubusercontent.com/50908984/58369043-97893000-7f12-11e9-8d21-424fef4d4217.jpg)

![b_confirmMail](https://user-images.githubusercontent.com/50908984/58369045-9c4de400-7f12-11e9-8ce7-94a7aef701a2.jpg)



Then you can select file to Google Drive Using 'Choose files' button. 

![choosefile](https://user-images.githubusercontent.com/50908984/58369048-a8d23c80-7f12-11e9-885d-5a49f6f21cc9.jpg)


After select document you can upload file to Google Drive Using ‘Upload’ button

![upload process](https://user-images.githubusercontent.com/50908984/58369050-b4bdfe80-7f12-11e9-985a-0894a2e75801.jpg)


Finally you got the document in your google drive.

![drivelocate](https://user-images.githubusercontent.com/50908984/58369054-c0a9c080-7f12-11e9-97f1-59aa2350455a.jpg)
