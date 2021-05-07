# Text_Cipher

### To implement this we considered a scenario in which a **Admin** take the **Student Details** and stored the details into their system in Encrypted form. <br />
1. Prerequisite to run this java program (also contain GUI):<br />
   **a.** OS Mac, Windows or Linux (The demonstration shown below is on MacOS BigSur version 11.3). <br />
   **b.** To provide the support of GUI (Graphical User Interface), here I used **Java Servlet** in **Eclipse IDE**. <br />
   **c.** Using **JDK version 13** and **Tomcate version 8.5** to implement the Java Servlet or provides a web server environment in which Java code can run. <br />
   **d.** Here we used AES (Advanced Encryption Standard) for encryption, AES algorithm is a symmetrical block cipher algorithm that takes plain text in blocks of 128 bits and converts them to ciphertext using keys of 128, 192, and 256 bits (we used key lenght of 16 bytes which is 128 bits for Encryption). <br />
   
   **Note:** The directory or file structure is used acrroding to the MacOS, you can change it according to your system within the source code.
2. First we have to create a **Servlet Project** (You also Create a Simple Java project which have all the dependencies or jar according to **Servlet**) and implement the folder or file structure as shown below:

    ![Screenshot 2021-05-07 at 12 54 47 PM](https://user-images.githubusercontent.com/46700867/117413392-8b49e200-af33-11eb-91ab-3a181a8018ae.png)

   **Note:** You will find all the files such as *"AES.java"*, *"Login.java"*, *"New_Entry.java"*, *"EnterDetails.html"*, *"Login_page.html"*, and *"OutPut.jsp"* within this repositry having the same folder and file structure as mentioned in the above image.

3. Now run the *"Login_page.html"* file on the server (Make Sure that your **Tomcat Server** is in running state at localhost), as shown below:

    ![Screenshot 2021-05-07 at 2 20 52 PM](https://user-images.githubusercontent.com/46700867/117424468-71160100-af3f-11eb-85f0-5cdcc79134ae.png)

    You can enter anything in **User Name** and **Password** field because its not set for a particular user:
    
    ![Screenshot 2021-05-07 at 2 17 08 PM](https://user-images.githubusercontent.com/46700867/117424562-85f29480-af3f-11eb-89ad-2fef165c0bde.png)
    
    Then click on the **Login** button to continue the process, as shown below:
    
    ![Screenshot 2021-05-07 at 2 26 55 PM](https://user-images.githubusercontent.com/46700867/117425286-48dad200-af40-11eb-97ac-a695743a7b04.png)

4. Now, you will redirect to the **Enter Details** page, where you have to enter all the required information and click on the **Submit** button, as shown below:

    ![Screenshot 2021-05-07 at 2 29 41 PM](https://user-images.githubusercontent.com/46700867/117425698-abcc6900-af40-11eb-8f78-5ec1e39a00b2.png)

5. Here you will see that the encrypted details are shown via *"Output.jsp"* file in the end of the program, as shown below:

    ![Screenshot 2021-05-07 at 2 31 49 PM](https://user-images.githubusercontent.com/46700867/117425950-f77f1280-af40-11eb-8cad-1d1a730a0213.png)
    
    Here is the **console** output shows that the file of the User is created and contains all the information in encrypted form (in white highlighted text):
    
    ![Screenshot 2021-05-07 at 2 34 39 PM](https://user-images.githubusercontent.com/46700867/117426293-5cd30380-af41-11eb-9272-2d41a47eec1d.png)

    **Note:** If the file is already exist then it will show a message *"File already exists."*
    
 6. Then created file is stored in the directory which mentioned in *"New_Entry.java"* and naming structure of the file is *"FName + "_" + LName + ".txt"*, as shown below:

    ![Screenshot 2021-05-07 at 2 41 56 PM](https://user-images.githubusercontent.com/46700867/117427167-627d1900-af42-11eb-8bf5-d40e56bb6cf7.png)

    Here you can also see the content of the file which are in encrypted form:
    
    ![Screenshot 2021-05-07 at 2 42 57 PM](https://user-images.githubusercontent.com/46700867/117427291-85a7c880-af42-11eb-88d6-36a50cb5e92e.png)
