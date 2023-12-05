# Maven_project1
"Maven Project - To build an artifact as a result of a Maven Build Life-Cycle Process"

Steps to be followed =================================================>>>>

Step-1: Open the CMD Command prompmt on your local system

Step-2: Go to any Drive(Directory) , ex -C:\Users\shahnawaz Yousuf> d: (enter) 

Step-3: Enter the command: mvn archetype:generate (enter)

Step-4: Type the same number at the last whatever in your system you get as result. ex; 2089 : 2089 (enter) 

Step-5: Type 8 (enter)

Step-6: groupId: online.nawazinfotech (or com.amazon or anything) (enter)

Step-7: artifactId: webapp (or anything like: xyz) (enter)

Step-8: version' 1.0-SNAPSHOT: : (enter)

Step-9: package' online.nawazinfotech: : (enter)

Step-10: Type: Y/y (enter)

Result : BUILD SUCCESS

Step-11: Change the directory : cd webapp (enter)

Step-12: Now go to Window D/ Drive : Check here for new Maven File i,e. "webapp" => Open the file => Open the "pom" file => Change the maven.compiler.source - 1.8 & maven.compiler.target - 1.8 and and add the <configurations> and save.

Now Go to cmd prompt: Run the command- mvn compile (enter) => run command- mvn package (enter)

Step-13: Change the directory : cd target (enter) => run the command - java -jar webapp-1.0-SNAPSHOT.jar (enter)

Step-14: O/P = Hello Maven (or, "Hello World" - as per the src => App file)

Here the Project gets complete as you created the jar artifact file (webapp-1.0-SNAPSHOT.jar) and able to access it.

<<<===CONGRATULATIONS You have successfully done this mini Maven-Project===>>>

Note1:- "If you want to change the Display content (i,e. "Hello World" to "Hello Maven") can do it by simply following the steps:-

Step-1: Go to D:\webapp\src\main\java\online\nawazinfotech: file and edit the content as you want and save.

Step-2: Repeat the above steps from Step-11 to Step-14.

Note2:- Here some supported pictures also attached for better understanding and references:

<img width="840" alt="mvn-1" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/b76f9f0f-15c1-41b9-abe6-b2069dc5f3d3">
<img width="561" alt="mvn-9" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/807c74a3-1bbc-4e0e-885f-59fbae09300d">
<img width="686" alt="mvn-2" src="https://g<img width="166" alt="mvn-3" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/f767a557-b58b-49b6-ae9b-f9f09fc3a70d">
ithub.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/75caca7b-5059-4614-af82-44deed96eb1a">
<img width="426" alt="mvn-4" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/b9f88b6d-a887-44ec-9674-88138edec6ab">
<img width="446" alt="mvn-10" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/f9cf0260-7cee-46c4-8b03-cedd4e477787">
<img width="791" alt="mvn-11" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/41a5b9bc-e445-4432-b187-55b6fbd60bf9">
<img width="358" alt="mvn-12" src="https://github.com/Shahnawaz-yousuf/Maven_project1/assets/146080117/585dbb4d-3335-4c04-b1b0-49edfb67a79b">
