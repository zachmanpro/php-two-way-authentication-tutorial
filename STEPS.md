TUTORIAL STEPS
--------------

1. Create a composer ready project

    ```
    $ mkdir two-way-authentication-tutorial
    $ cd two-way-authentication-tutorial
    $ composer init
    ``` 
    
2. Install the Clickatell PHP lib

    ```
    $ composer require arcturial/clickatell
    ```
   
3. Create folders for our files, lets get organized

    ```
    $ # our php classes
    $ mkdir src
    $ # our html and asset files
    $ mkdir public
    ```

4. Create forms for login and to enter the pin sent to the mobile number. I used twitter bootstrap for this, you can use whatever you like here.

    1. Create success and error page.

5. Create the index file for the simple logic flow.

6. Create new Authentication Class, keeping it simple for tutorial. This should go in our src folder.

    1. Create simple method stub (you'll do more in here for you actual project) called "authenticate" that takes a username and password and return a mobile number if successful otherwise false.
 
    2. Create a simple method to send the text message (sms) called sendPin. Save the pin in the session.

    3. Create a simple method to compare the user entered pin with the generated pin called checkPin.

7. Combine all the login using the methods in the index file.
  
