Student-Attendance-Monitoring-System-using-Face-Recognition


The objective of this project is to process live video-stream of students entering their classroom and generate the list of students attending the class. The system is coded in Python using OpenCv , Tkinter and MySQL.





## ⚙️ HOW THE SYSTEM WORKS?

This system works accordingly with a series of step explained below:

1. **LOGIN PAGE**:

First the admin will login using either default credentials **username=user@123** and **password=user@123** or can create a new account.

![Image](/Screenshots/Loginpage.png)

2. After entering right credentials welcome message appears.

![Image](/Screenshots/Welcomemessageappears.png)

3. Now the main page of face recognition attendance system appears

![Image](/Screenshots/Facerecognitionmainpage.png)

4. First Clicking on **Student Details** opens the page to register students and see their details. Students must have unique ID 

![Image](/Screenshots/Registeringstudents.png)

5. After saving details click on Take Image option to capture student's face . 100 samples will be taken.

![Image](/Screenshots/Capturingimage.png)

6. Next on the main page click on **Train Image** after that cick on Train Data to train samples for detection and recognition.

![Image](/Screenshots/Trainingdata.png)

7. Now click on **Take Attendance** to recognize face . If the computer recognizes the face details are shown otherwise 'Unknown Image' message is shown

![Image](/Screenshots/TakingAttendance.png)

8. Simultaneously, a csv file **attendance.csv** will be updated with the ID,Roll No, Name of the student ,Department, Date and Time at which his/her face was recognized.

![Image](/Screenshots/Attendancesaved.png)

9. On the main page click on **Attendance Report** and then import attendance.csv to view attendance report of students. Attendance can also be exported .

![Image](/Screenshots/Importingattendance.png)

![Image](/Screenshots/Attendanceimported.png)




## Built With

* [OpenCV](http://docs.opencv.org/3.1.0/) - Implementation of Algorithms
* [Tkinter](https://docs.python.org/2/library/tkinter.html) - GUI Implementation
* [MySQL](https://docs.oracle.com/en-us/iaas/mysql-database/doc/getting-started.html) - Database
* [HAAR-CASCADE CLASSIFIER](https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html)
* [LocalBinaryPatternHistogram (LBPH) recognizer](https://docs.opencv.org/master/df/d25/classcv_1_1face_1_1LBPHFaceRecognizer.html)
* [PIL](https://pillow.readthedocs.io/en/stable/)


**Following functionalities can be performed: <br>**
• Login <br>
• New User Account can also be created. <br>
• If forgotten the login credentials password can be changed <br>
• Register new students to the system. Students can be filtered by Name or Department<br>
• Take photo sample of them <br>
• Train the model <br>
• Take attendance by scanning face <br>
• View attendance report of all students by importing csv. Also attendance can be exported too. <br>


