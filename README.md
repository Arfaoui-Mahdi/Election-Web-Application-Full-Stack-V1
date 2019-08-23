# Election-Web-Application-Full-Stack-V1
this version need some adds and some modifications, like implementing the h2 DB into a static normal database , add activity and electoral progam/list and a back-end micro-service to calculate the score of each candidate. 

Video Link : https://drive.google.com/open?id=1UPR1cVtvaH434-NbiCgU-EXUOiVaftbf \n
*
sorry for the sound quality and for me saying a lot of "euuuuuuuuh" xD
*
NOTE :
-src.zip is the angular src u just need to replace into you angular project repository
-src-spring.zip is the spring project src u need to replace it tooo


Steps :
- go https://start.spring.io/ and choose : maven project - java(version 11 in options) - 2.1.8 snapshot - and add as dependecies (JPA - web - DebTools - Spring Security - H2 )
-download the zip , unzipp it , open eclipse or STS (Spring Tool Suite 4 "IDE" for spring framework) 
-go to file->import->existing maven project  and put the unzipped folder directory wher a "pom.xml" exists
-open and let the IDE downloads the dependencies and setup you wrokspace 
-replace the src folder 
-launch the application 
*
*
*
*
- run ng serve in a terminal where the angular project exists 
and run the whole project.
*
*
****PS: if u had any probleme in establishing the spring project , try redirect to the project foler , open a terminal , type "mvn install" than "mvn eclipse:eclipse" 
make sure to install maven***

***********TASK TO ACCOMPLISH***********

-implementing to a static DB
-adding score microservice
-adding electoral program and electoral entities


**********PS***********
i was going ti implement JWT framework for more security capability but we could do it after we accomplish the important tasks

THANKS

