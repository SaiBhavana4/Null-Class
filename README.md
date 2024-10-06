# Null-Class
# Internship Report for NullClass
Name: Mannava Sai Bhavana <br/>
Internship Duration: September 9, 2024 – October 9, 2024 <br/>
Mentor/Organization: NullClass <br/>
Role: Cybersecurity Intern <br/>
NullClass Username: SAI BHAVANA MANNAVA <br/>

# 1. Introduction <br/>
This report provides a detailed account of my internship experience at Null Class in September 2024, where I worked on significant cybersecurity tasks such as running linux commands in Termux, configuring Android device policies, and Decompiling APK files for security analysis. These activities greatly strengthened my technical proficiency and hands-on experts in mobile security. The report highlights my contributions and showcases the technical competencies I gained throughout the internship period <br/>
# 2. Background <br/>
The rapid evolution of mobile technologies has created both opportunities and challenges in the cybersecurity landscape. The tasks undertaken during my internship were essesntial for understanding and mitigating risks associated with the mobile device environments. By running linux commands in Termux, configuring device policies, and decompiling APK files, I gained a comprehensive understanding of mobile security, which plays a vital role in protecting sensitive data from potential threats. This report provides a detailed overview of the tasks and their significance in today’s digital security practices. <br/>
# 3. Learning Objectives <br/>
The primary learning Goals for this internship were: <br/>
Develop proficiency in using basic linux commands for navigating the termux environment. <br/>
Understanding the process of configuring security policies on Android devices to enhance user protection.<br/>
Gain hands-on experience in decompiling APK files to analyze mobile applications and identify security vulnerabilities. <br/>
# 4. Activities and Tasks <br/>
# Task 1: Run Basic Commands in Termux <br/>
Description: <br/>
The first task is focused on introducing users to basic linux commands within the termux environment. This process involved familiarizing users with directory navigation commands such as ls, pwd, and cd. These commands allow users to efficiently interact with the Termux file system and gain a foundational understanding of Linux environments. <br/>
Steps: <br/>
1.	ls (List Directory Contents) : Used to display the files and the folders in the current directory. <br/>
•	Command: ls <br/>
2.	pwd (Print Working Directory): Displays the absolute path of the current directory.<br/>
•	Command: pwd <br/>
3.	cd (Change Directory): Allows users to navigate to different directories. <br/>
•	Command: cd [directory-name] <br/>
4.	Termux Home Directory <br/>
•	Command: /data/data/com.termux/files/home <br/>
5.	Termux Internal Files <br/>
•	Command: /data/data/com.termux/files <br/>
6.	Android Internal Storage <br/>
•	Command: /storage/emulated/0 <br/>
7.	External SD Card <br/>
•	Command: /storage/XXXX-XXXX (if applicable) <br/>
By demonstrating these commands, users were able to navigate through file system effectively and gain an understanding of the Linux environment with Termux. <br/>
# Task 2: Configure Device Policies <br/>
Description: <br/>
This task involved guiding users through the process of configuring Android device policies. Device policies are crucial for ensuring that mobile devices operate within secure parameters, such as requiring a passcode, controlling Wi-Fi settings, and restricting applications. I walked users through each step of configuring these policies in a virtual Android device using Genymotion. <br/>
Steps: <br/>
1.	Passcode Requirements: Ensuring that a strong passcode is mandatory for unlocking the device. <br/>
•	Use Android’s DevicePolicyManager class to set up a policy that enforces a minimum passcode length and complexity. <br/>
2.	Wi-Fi Settings: Restricting Wi-Fi access to ensure that users only connect to secure networks. <br/>
•	Using the Android Network Policy configuration, apply restrictions on network types and allow only pre-configured networks. <br/>
3.	App Restrictions: Limiting the apps that can be installed or run on the device to prevent malicious apps. <br/>
•	Create a custom policy that blocks the installation of non-verified apps and restricts background app usage. <br/>
These steps provided users with practical experience in securing Android devices and configuring essential policies to protect sensitive data. <br/>
# Task 3: Decompile an APK File <br/>
Description:  <br/>
For this task, I instructed users on how to decompile APK files using tools such as JADX and APKTool. The objective was to extract the source code and resources from an APK file to analyze the application’s behavior and detect potential vulnerabilities.<br/>
Steps: <br/>
1.	Using APKTool: <br/>
•	Command: apktool d [apk-file.apk] <br/>
•	This decompiles the APK file into its raw resources and manifest files, allowing users to inspect the application’s structure. <br/>
2.	Using JADX: <br/>
•	Open the APK file in JADX, which decompiles the app’s bytecode into readable Java code.<br/>
•	Navigate through the decompiled source code to understand the functionality and spot any security issues.<br/>
3.	Analyzing the Manifest File: Review the permissions requested by the application to identify potential security risks, such as access to sensitive device resources. <br/>
By completing this task, users learned how to inspect APK files for malicious code and reverse-engineer applications for security purposes. <br/>
# 5. Skills and Competencies Developed <br/>
Throughout the internship, I developed a range of technical and soft skills that will be critical in my future career in cybersecurity. <br/>
1. Technical Skills: <br/>
•	Gained proficiency in navigating the Termux environment using Linux commands. <br/>
•	Acquired the ability to configure Android device policies to enhance security. <br/>
•	Learned how to decompile APK files and analyze their source code for vulnerabilities. <br/>
2. Soft Skills: <br/>
•	Improved my ability to communicate technical concepts clearly and effectively to users. <br/>
•	Enhanced my problem-solving skills, especially in troubleshooting mobile device configurations. <br/>
•	Developed documentation skills by writing detailed reports and guides for each task. <br/>
# 6. Feedback and Evidence <br/>
During my internship, I received positive feedback regarding the clarity and effectiveness of my instructional materials. My ability to guide users through complex technical tasks was particularly noted, especially in the areas of configuring device policies and decompiling APK files. This feedback underscored the significance of my contributions to enhancing the understanding of mobile security practices.

One specific instance of recognition was related to my meticulous attention to detail when explaining the steps for APK decompilation. The comprehensive instructions I developed proved to be beneficial for others seeking to improve their analysis techniques, highlighting the value of clear and structured guidance in technical environments. This acknowledgment not only reinforced my commitment to producing high-quality documentation but also demonstrated the impact of thorough explanations on the learning process. <br/>
# 7. Challenges and Solutions<br/>
During the course of my internship, I encountered a few challenges, particularly when working with virtual Android devices. Configuring device policies on Genymotion required troubleshooting, as certain settings did not apply as expected.

To overcome this challenge, I thoroughly reviewed the Android developer documentation and cross-referenced it with community forums to find the correct approach for applying the policies in the virtual environment. This process not only solved the issue but also gave me a deeper understanding of Android’s DevicePolicyManager.

Another challenge was ensuring that users could decompile APK files without running into errors. By carefully researching the tools and providing additional resources, I was able to guide users through the process effectively.
# 8. Outcomes and impact <br/>
The tasks I completed during this internship have had a significant impact on my professional development. Through hands-on experience with mobile security, I gained valuable skills that will be directly applicable in my future career. Additionally, my contributions to the team’s security practices, particularly in configuring device policies and analyzing APK files, have improved the overall security posture of the project.

These tasks also enhanced my understanding of how mobile applications interact with the Android operating system and how device policies can be leveraged to enforce security measures.
# 9. Conclusion<br/>
My internship at Null Class provided me with invaluable experience in cybersecurity, particularly in mobile environments. The opportunity to work with Termux, Android device policies, and APK file analysis has strengthened my technical capabilities and broadened my understanding of mobile security. The skills and knowledge I gained during this internship will be instrumental in my future endeavors in the field of cybersecurity.

# 10. Appendix <br/>
Task 1: Run Basic Commands in Termux<br/>
![ls: List Directory](Task 1/ls(list directory).png) 

![pwd: print working directory](Task 1/pwd(print working directory).png)

![cd: change directory](Task 1/cd(change directory).png)

! We need permission to access the files (Task 1/To access file we need permission.png
)

![Termux Home Directory: /data/data/com.termux/files/home] Task 1/Termux Home Directory.png
