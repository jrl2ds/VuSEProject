# SMS Catalog 

The goal of my project shall be to create a texting app that offers the ability to obtain more information about the course catalog from a student. 
Students can submit major names or course titles to the Course catalog, and they will get respones that can offer useful information such as course
descrpitions, major requirements, and more. 

This project stems from the requirement that it be offered via text messaging. This shall all be done via text interface, and the user can simply text the server
to obtain the information they are looking for. There are a variety of extra goals for the project, including making it easier for the user to find out info about
their courses, to obtain info about course requirements when the internet or a pdf reader isn't visible, and making it easy to store a record of the information 
they care about most, by checking their texts. 

Possible additions include pulling information from rate my professor, allowing profiles that might save user data about courses taken, and providing info about
when a course might be offered, or when it was previously offered. This information will likely require a database that is contsructed from Vanderbilt's YES page, 
which because it doens't offer an API, will likely require offline construction of the database. 


# Questions:
1.	How do you currently figure out information about the completion requirements of a given major?
2.	How do you plan what classes you’re going to take in an upcoming semester? 
3.	If you wanted info about the requirements of a given minor or second major, where would you find those requirements?
4.	How accurate would you say you’ve found information professors have provided to be, in regards to major requirements?
5.	How do you figure out, what a given course you might be interested in or required to take, is about? 
6.	Do you feel your current method of obtaining information about your major requirements is effective or convenient?
7.	Do you feel your current method of obtaining information about course descriptions is effective or convenient?
8.	When you were a prospective student, or before you entered Vanderbilt and had access to YES, did you find this information easy to obtain? 
9.	What kind of additional features would you like to see added to the current tools you use to evaluate classes?
10.	What would be your ideal way of obtaining this information about your major requirements?

# Answers: 
## Question 1:
F: He goes through a strenuous process of figuring out where. I’m a chemical engineer, so there’s no good website that tells me what the graduation requirements are. I usually just contact my advisor, or comb through the website. Once you find the info though, it’s easy. 

M: I go to the undergraduate catalog and look up the course requirements. I often would check it when I was making plans for my double major. Sometimes I use the degree audit on YES. 

A: I’m not completely sure how I go about it for each time. I know the math requirements are on the math website, and I suppose I would look at the website of a respective major for those requirements, although I’ve found them to be out of date or hard to obtain sometimes. I know YES can let you do that, but only for your current major. 

## Question 2:
F: Generally, I base it off the graduation requirements that I find from the pdf I found on the chem E website, or I go to my advisor. I also check what classes are open when I try to register. I tend to check minors as well.

M: I tend to coordinate info from what classes I’ve taken, recommendation of my fellow students and professors, courses open in the upcoming semester from the course catalog, requirements of my major, I usually have to eliminate a few prospective classes as a result of scheduling conflict, since a lot of classes are only offered at some times. I also talk to my advisor

A: One annoying thing about this, is that we have no way of knowing what classes will be open when I try to register. They are 

## Question 3:
F: It depends, I honestly don’t know. I’d probably google it, or contact a professor.

M: From the undergraduate catalog, or degree audit

A: I’m not entirely sure. Probably from the website for the major I’m interested in, maybe it’s somewhere in yes, and there is the catalog. 

## Question 4:
F:  Very accurate. Well actually, it depends on the advisor. In my personal experience, I had an advisor who wasn’t the best, and he didn’t provide good information, or vague information, but then I got a good advisor who provides very detailed info and different avenues of approach to meeting all my requirements

M: I’ve found it to be inaccurate. My advisor kinda sucks, and has a poor idea of what my majors requirements are, and has absolutely no idea the requirements or difficulty of adding a given minor or other major.

A: My advisor gives accurate info about my requirements, although it is limited in scope to my major, and usually doesn’t have all the details about what a course is like. My advisor actually had no idea what some of the classes I took were about.

## Question 5:
F: Usually I would have to go to the YES page, that uhh, has all the course listings, and find the individual or specific course, and find information that correlates from that. 

M: I would look it up in the Course Catalog, ask other students about the class, maybe ask my advisor, and look up the description in the YES page.

A: I would probably look it up on yes, going to course registration to find out information about the course. One annoying this is about how we can’t get syllabus’s. 

## Question 6:
F: Nah. It is not convenient. I would expect it to all be within the same platform. Say for instance, when I go onto the course catalog (He is referring to Yes Course Registration), I would see a list of all the courses I have taken, or need to take. (Notably, YES does provide this info)

M: It’s only convenient for your current major, it’s very inconvenient for figuring out requirements of other majors or other minors

A: No it’s not convenient, although it is effective. There is a lot of information out there, and most of it is easy to find, it’s just time consuming to cross reference over several websites. 

## Question 7:
F: it’s fine. Student registration is done moderately right, you just have to type in the course number, and you get the info about it. 

M: Not really. It would be easier if the information about what courses are was available when I was learning about the need to take those courses, not having to cross reference different websites

A: It’s convenient enough, YES gives me descriptions of courses that are open next semester. 

## Question 8:
F: oh no, absolutely not. It was very difficult to get information about it before I had access to yes. It was literally impossible, I have no idea where to find that info. 

M: Somewhat, I used the Course Catalog, and I think Vanderbilt might have sent me some of the info.

A: It was a lot harder, as I didn’t have YES, so I had no idea what courses were offered. 

## Question 9:
F: Ratemyprofessor is very very nice, to have it where I can use it with course information, so I can figure out what professors are best for a course. 

M: A more robust way of planning out classes over the semesters. It ca be hard to tell what classes are offered which semesters, without simply being told in advance. This can make graduating on time difficult.

A: Easier to use, I already have most of the features I need. 

## Question 10:
F:  On the Yes Catalog page? 

M: Probably a central place that would tell me about the different course requirements I have, how many I’ve completed, and the courses in the upcoming semester that could contribute to them.

A: An app-like calendar that had tabs for all the different options would be nice. 




   # Requirements
 
 The 
 
   # Development Approach
   
## Overview
The development approach shall start with the continued collection of user feedback on the potential features that could be implemented within the application. At no point does this feedback end, a process of continual engagement of customers and potential users can provide important information about the strategic direction of case submission. 


This application is based on having sources of data, namely accurate information about major requirements, course offerings, course details, and potentially rate-my-professor information. Some of this data can be dynamically fetched when requested, some of this data may require the creation of a database that the application query.

The process through which we will create the application shall proceed as follows:

1. Collect user feedback on application requirements, and construct, based on the feedback, a general purpose set of 'features' that can be provided to the user. The current features are: Providing major requirements when requested. Providing minor requirements when requested. Providing a course-description when requested. Provide a list of times a class is offered, when requested. Provide teacher information when requested.

2. The project is a text-based application. The first requirement of the application will be to offer a convenient text application. Generally speaking, the application should be able to receive text messages at a stable and consistent number, and respond with messages. Getting this core functionality working is the first step in the development process. This has two primary subparts:
  A. Setting up server that can receive incoming messages
  B. Setting up code on server to respond to incoming messages, cognizant of the content of the incoming messages.In general, the code will likely respond with a generic message that informs the user that the given command wasn't understood, and provides the knowledge that sending "help" will respond with a list of queries and their proper format. 

3. The code will be based on a modular framework, where each "feature" is "handled" by a specific method. The current plan for this framework will be to build a primary parser, that accepts a given message, parses the input to understand what feature is being called upon, and then offloads the work onto a specific handler for the feature. By modularizing each feature, the code can be built sequentially, and improved. The initial framework that can parse a message based on it's input will be the first code desigend and implemented, and then each feature can be added to the code progressively, with more information being added to the parser, and a new handler method and related database being constructed. The first method to be constructed will likely be the "help" message, and an "unknown command" message that will respond with basic details on what the code does, and informs the user of the format for the help command. The help command will list all the available features and the input format. We will not automatically provide this info on every received unknown command, as the help message may become long when many features are added.

It is intended that the intial process of designing and implementing the basic structure of the code should not take long. It is not overly complicated, and relies upon the bulk of the work being done in modular features. The first few features may also take longer to implement, however much of the code, structure and design of early features will be repeated in later features, allowing for drastic reduction in the time-cost of features added after the first. I estimate 1 hour maximum for the design of the framework, as well as roughly 30 minutes to 1 hour for the design and architecting phase of each feature. Each feature should reasonably have a 1-2 hour implementation viewpoint, including the database construction. In the case of unexpected technical difficulties in implementaiton and deployment, both of which are steps that require coding and operating with frameworks the developer may not be used to, added time must be added for obtaining the information neccesary to implement or deploy.   


## Information Gathering, Empathy Surverys
As discussed above, the first part of the process is implementing empathy surveys, to gain information from potential users about the problems they face, the solutions that could be provided, and the information that might be gleaned from the users. A great focus for empathy surverys include corner cases, identification of neccesary features, and what GUI or input format might be most useful for students. Interviewing professors, or incoming students may also provide greater feedback about what resources or features might be useful outside the initial intended scope.

## Design and Architecting
As noticed above, the intention is to build a relatively modular code base. The central content of the code is a parser that diverts incoming messages into a handler: The specified handler will be based on the content of the incoming messages. Various examples include: help, course-data, major-requirements, unknown commands. The parser ensures the information is of a format that the appropriate handler can utilize. 
Each modular handler, and it's associated database must first be designed and architected. By establishing clear guidelines as for the input content of a message, and the expected output, the general design of the handler can be implemented. The database format can also be implemented, and constructed. Throughoughly designing the code before implementing allows for improved efficiency: designing the database may impose certain restrictions on the operation of the handler method, and so designing and architecting the entire feature before implementation will reduce the need to rewrite code as the plans for the flow of information change.

## Implementation
After building a thorough design, based on user feedback, the overall framework, and the individual modular features will be directly implemented. A handler method will be contructed, the parser will be modified so that the handler is called whenever an appropriate input is found. The handler is then implemented, based on the intended design, so that it can properly process the data and provide the information expected of it. The database will then be created so that the method can work as intended. The help message must also be updated so that the new feature is provided on the list of commands.

## Testing
After implementation of each feature, and before final product delivery, testing must occur. Thorhough testing is neccesary to ensure an appropriate product is delivered, and that operates as intended. Since this is a texting application, manual testing of the application will be the most useful tool, ensuring that the application can accept inputed data, parse it appropriately, pass it to the correct handler, and give back the information that is expected. If there are issues, implemntaton shall be redone to fix specific issues, and it may be possible that more empathy surveys and designing is neccesary to update the feature to a purpose more appropriate to users. It is critical this is done before deployment to ensure an operational product. 

## Deployment
The product will be deployed once the product meets customer specifications and works as intended. The product will be deployed via AWS. If updates are performed after a deployment build, those updates must meet an exceptionally high standard of testing before a redeployment, to ensure user functonality isn't reduced and only improved upon any redeployment of an updated. 

## Maintence
This step is critical for the continued success of the project. Advanced user feedback from the deployment build, as well as the possibility of deprecation of an external service or required changes to the specification, may result in the need for improvements, updates or changes made to the code. This can resolve issues that weren't identified in the testing stage, and it can allow for added and more advanced functionality to be added. New features may go through an enhanced version of the entire process: empathy surveys may be more impactful now that it's fine-tuned to simply what to add or change about an existing application, and this may allow the product to be altered to add better or new features. The code must adapt to changing requirements or features. 
