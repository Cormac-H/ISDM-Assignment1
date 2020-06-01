## <div align='center'>ISDM Project Report - Group 8 </div>


### <div align='center'>Problem Definition</div>
-------------------------------------------------------------------------------

#### Project Outline
This report proposes a preliminary design for the implementation of a in-house call management center (CMC) information system. The development of this system is in response to pre-existing flaws in the current phone operations of a major travel agency. These flaws include the suitability of employees matched with customers, waiting time of customers, and sales time provided by employees. Our proposed system intends to provide functionality to match customers with employers most similar to their needs and socio-cultural background. By matching employees with suitable customers, not only is customer satisfaction expected to increase, but wait and sales times will sharply decrease when a customer can be targetted on a personal level. The proposed system intends to take advantage of existing company tools including the customer *'Profiler Tool'*, inbound *'Automatic Call Distributor'*, *Interactive Voice Response unit*,  and of course the existing database.

#### Key Stakeholders
Our team wishes to focus specifically on the 'Customer', 'Relationship Manager' (RM), and 'Product Owner' stakeholders for the design of an improved call system. In order to develop the new system, empathy maps have been developed to help us draw a deeper insight from the typical customer, employee, and of course the product owner. 
- Customer  
<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Customer%20Empathy%20Map.PNG?raw=true "Customer Empathy Map")
</img>
- Relationship Manager (RM)
<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Relationship%20Manager.PNG?raw=true "Relationship Manager Empathy Map")
</img>
- Product Owner
<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Product%20Owner%20Empathy%20Map.PNG?raw=true "Relationship Manager Empathy Map")
</img>
####  <div align='center'>Analysis of Stakeholder Point-of-Views </div>

##### Customer POV
- As a customer I need to be be dealt with by a human in a fast and efficient manner so that i dont feel frustrated waiting on hold or dealing with an automated response for too long.
- As a customer I need a range of holiday options available so that i can make the best decision for my future trips
- As a customer I need to talk to someone who is well informed about my likes and dislikes, so that i can feel confident having someone else arrange my holiday
- As a customer I need someone to help me make major travel decisions in a timely manner without feeling rushed, so that I do not feel overwhelmed by the booking process
- As a customer I need to have the option to withold personal information if i don't feel comfortable giving it out, so I can protect my privacy
- As a customer I need to know my personal information is stored securely by a company, and how it will be used, so that i can trust the agency service.
- As a customer I need to have my loyalty to the service acknowledged so that i can feel valued and respected to continue returning. 

##### Relationship Manager POV
- As an RM I need to my performance to be recognized and rewarded by the agency so that I'm encouraged to keep meeting expectations in my work
- As an RM I need to know some information about my customers before discussing holiday packages with them so that I can recommend appropriate deals and achieve low sales times
- As an RM I need my existing personal skills and experienced to be recognized by the agency so that I can use them to enhance my sales ability
- As an RM I need the option to not disclose unnecessary personal information to my company so that my privacy is respected
- As an RM I need to feel comfortable calling customers with limited experience or as a new employee, so that I can learn the ropes of selling well at my own pace
- As an RM I need low wait times for customers, so that they do not provide negative feedback on my call due to their wait rather the experience i personally provided.
- As an RM I need to be able to specialize in a subset of the packages offered, so that i can provide more attention to detail and feel confident selling the deals i know about to customers
- As an RM I need to have the option to expand my skillset or knowledge, and have these recognized by the agency so that i can feel motivated to improve as i work for longer.

##### Product Owner POV
- As a product owner I need to achieve high customer satisfaction, so that i can continue to run a successful business
- As a product owner I need my employees to feel motivated and happy to continue working for the company, so that I can maintain and achieve a loyal team of high performing staff
- As a product owner I need to learn and understand more about potential and existing customers, so i can create and find packages that suit our range of customers
- As a product owner I need to make sure full disclosure is provided when gatehring information about people, and sensitive information is obtained legally and stored securely, so that i can continue to ethically run the agency
- As a product owner I need to constantly seek to improve call handling, including wait and call costs for customers, so that my business can remain competitive.
- As a product owner I need to reward customer loyalty so that i can encourage repeat business
- As a product owner I need to reward employee performance so that i can keep my employees motivated and striving to improve.

#### <div align='center'>System How-Might-We Analysis </div>

##### Customer HMW
- How might we make the service feel personalized for customers?
- How might we gather personal information in a way that is secure and not cumbersome for users to provide?
- How might we reward customer loyalty?
- How might we recognize customers who are friendly and approachable, and ones who are more difficult to sell to?
- How might we narrow down what holiday packages a customer would be interested in from our large selection?
- How might we reduce customer waiting times?
- How might we cater to customers who speak in different languages?
- How might we recommend packages to customers who already have a lot of knowledge about where they want to go?
- How might we make customers feel secure and confident in providing their personal information?

##### Relationship Manager HMW
- How might we reward RMs for working hard, reducing their sales times, demonstrating different skills, or having a diverse range of knowledge?
- How might we provide incentive for longtime RMs to continue working hard for the company
- How might we incorporate customer feedback into how RMs are evaluated?
- How might we elicit information from RMs in an ethical manner, and ensure their information is kept safe?
- How might we help new RMs adjust to using our system?
- How might we allow RMs to sell only packages they are comfortable with rather than the entire system.
- How might we let RMs take calls from customers who speak a similar language or are interested in the packages they know about.
- How might we allow inexperienced or underperforming RMs to improve their confidence on the phone?

##### Product Owner HMW
- How might we create a system that promotes business growth for the product owner?
- How might we guarantee an increase in customer and employee satisfaction?
- How might we present evaluative sales metrics to the product owner to track employee performance?
- How might we take advantage of the existing tools the product owner has provided?
- How might we reduce business expenses such as long call handling costs?

### <div align='center'> Project Approach </div>
-------------------------------------------------------------------------------
#### System Design & Brainstorming Stakeholder Needs
The system design has been designed to give the travel agency a competitive edge by facilitating repeat customers, business growth, and satisfied employees who can be rewarded and recognized for their high performance.

The system operates around an idea of 'skill matching' where a customer is met by an employee we believe can best fulfill their needs. Skills will be gathered for both customers and managers alike. The existing 'Profiler Tool' will be used to gather data for a customer based on their postcode and surname. For RMs, a 10 minute questionnaire will be made mandatory upon hiring. This will assess the age, sex, language proficiencies, prior experience, product knowledge, any relevant socio-cultural information that could be used to match with customers. When a customer makes an inbound call, this information will be used to get them an available RM who most similarly matches their background. RMs can further add to existing customer profiles, taking note of their preferences using keywords that match holiday package types. An RM can also provide a rating of how comfortable the customer was to deal with. Future RMs can view this information when dealing with the customer. 

All information elicited from both RMs and customers will be required to be stored in a secure database, with personal information not displayed to anyone and only used in calculations. Any user of the system will not be forced to provide information that is not directly necessary for a sale (e.g. name, payment info is needed to book a holiday). If a user opts out of providing information, these fields will be ignored and a heavier weighting will be given to performance metrics taken such as call durations.

When not receiving inbound calls, RMs will be expected to meet a reasonable weekly quota by making outbound calls, to encourage performance increase. Target lists (list of customers to call and pitch holiday packages to) will be generated for each RM based on their prior knowledge, personal performance, and socio-cultural background. Performance such as total sale time, customer wait time, and sale success will be gathered for all inbound and outgoing calls. Customers with very high performance will likely take the majority of inbound calls - the target list becomes a great way for newer employees to build up their experience and knowledge. Furthermore, the assessment of employee knowledge encourages people to specialize in knowledge of holiday types (cruises, interstate travel) or particular destinations. The product owner can encourage people to expand their current knowledge based on customer demands for new holidays, or train new employees to learn more about specific deals.

The system intends to use the company private automatic dialing branch to handle inbound calls. Customers who do not have an existing profile created will be asked some preliminary questions from the branch's Interactive Voice Response unit. These responses will be translated to assess their potential needs and interests before being matched with an RM using the skill matching concept explained before.

Performance assessments will be made from the following criteria for all employees:
- Call durations
- Call success
- Specific feedback given from customers to the company
- Existing knowledge
- Amount of and proficiency in skills/different languages  

Sales assessments will be made from the following criteria for all customers who have a profile generated:
- Number of repeat calls
- Specific feedback given from employees to the company
- Number of available packages that match their interests

All assessments will be used to calculate a skill score (1-10) for RMs and a customer score (1-10) for customers. This data will be used to further assist the skill matching algorithms for inbound calls and target list generation. For inbound calls, final suitability criteria will match high scoring employees with high scoring customers. In addition this score will be adjusted based on criteria an employee has matching with the customer, for example the same cultural background, language spoken, or a customer interest in packages the RM is familiar with. For target list generation, all employees will be given a list of customers ranked my their customer score, with higher scores at the top. This ensures RMs do not have an unfair skill score decrease when talking to many difficult customers in a row. Higher ranking RMs will receive a smaller target list, as they will spend more of their time occupied with inbound calls. Lower ranking RMs can increase their skill score by performing well during outbound calls.

#### Assumptions and Clarifications
In order to design the system certain assumptions have been made about the existing agency call system, and the future one.

1. The system will have access to all existing company data
    + All existing employee information will be gathered and updated so it is appropriate for a skill assessment
    + All user information will be gathered and reassessed by the Profiler Tool to create a new user profile
    
2. The system will have access to all existing tools
    + Profiler Tool
    + Automatic call routing and distribution branch
    + Interactive Voice Response unit
    + All tools can be integrated with the skill matching system to connect customers with RMs
3. Holiday packages are extremely varied and contain a range of booking types and styles
    + It is assumed that 'package' simply refers to multiple services the agency can provide through a single purchase
    + This may refer to different destinations, modes of transport, styles of accomodation, activities that can be booked on holiday etc.
    + Packages can be of different sizes
        * A customer may want to book a just accomodation
        * A customer may need accomodation, several activities, multiple flights
4. Packages can be tailored based on what a customer would specifically prefer
    + If a customer wishes to travel using a particular mode of transport or seek a specific style of accomodation this can be changed
    + The travel agency has the capacity to negotiate and change the packages receieved from 3rd parties
5. The travel agency has a substantial client base already
    + The nature of the system is that it moderately reliant on a range of both inbound and outbound calls
    + The system may fail if the agency launches without a reasonable amount of regular business available
6. Information can be reasonably elicited from customers
    + Data extracted from postcodes, surnames and user profiles can be reasonably obtained
    + The purpose of skill matching is to present a customer with an RM that most aptly reflects their needs
    + This purpose of quality customer service is defeated if it is cumbersome for a user to enter a lot of profile information
7. A substantial amount of RMs already exist within the company
    + Similar reason to assumption 6
    + A main objective of the system is to increase customer satisfaction
    + Customers who make inbound calls from the new system will be disatisfied with long wait times for an RM, and the purpose of the system will be undermined
8. Customers are comfortable providing personal information
    + Not all customers may feel comfortable having information about their socio-cultural background being gathered
    + The system will need to inform users how they intend to store their data securely and use it with the software
    + A score can be granted to a customer irrespective of whether they provide this personal information
    + Scores can instead be generated from their holiday likes/dislikes, repeat calls, and other sales metrics
9. Information about holiday packages will be categorized
    + It is assumed that information about holiday packages can be categorized by features such as destination or type of trip
    + This way an RM can choose to specialize their knowledge, for example a particular destination they have a lot of information on
10. Data is stored securely, all phone lines and profile tools have safe security protocols
    + The system requires the elicitation of sensitive information from its users and should be stored securely
    + Only information relevant to an RM will be displayed, such as a customer's potential interests or their total skill score (an arbitrary number)
    + All meaningful and personal information will be need to be stored securely in a back-end database for skill-matching calculation
11. All employees, new and existing, will need to complete a 10-minute questionnaire to gather their skills
    + Employees will need to be able to share the skills and knowledge that they feel comfortable with
    + All information should be relevant to what might help them make sales
    + All information asked of an RM should follow legal guidelines about what an employer can ask an employee to provide
    + If information cannot be gathered from an employee, their score will be generated purely from their performance metrics
12. The product owner, or other workplace supervisors, are able to assess the validity of all RM profiles
    + Each profile should be assessed to ensure skills and knowledge gathered are reasonable and accurate for employees
    + This makes sure employees do not provide fake details to receieve a higher skill rating
    + A product owner may want to provide existing performance details for employees who performed particularly well or poorly before the new system
        * This way valued employees will not have to work from the bottom up to achieve a high skill score.
13. Targetted lists can be adjusted and tailored for specific employees
    + High performing employees will naturally receieve more matches from inbound calls, and should be able to receieve a smaller target list of outbound weekly calls
    + Newer employees should have a targetted list of a larger amount of employees, ranked my their customer scores
        * This means as an employee grows their performance they will deal will customers who are predicted to be harder to sell to based on their customer score
14. All information is obtained legally
    + Customers and employees provide appropriate consent whenever information about them is gathered
    + Despite skill scores all customers are dealth with
        * While a customer with a lower customer score is likely to be dealt with after a customer with a higher score, the system should not engage in any discriminatory practises on the basis of socio-cultural background
        * RM hiring should include a diverse socio-cultural background of employees, so customers are not heavily prioritized based on these factors.
    + Customer postcodes and surnames for target lists have been obtained from 3rd party data services, or from existing users.
15. An RM skill score can be calculated using the following:
    + Average call duration
    + Average sale success
    + Specific positive or negative feedback the company receives about an employee
    + Languages known
    + Personal skills known that are recognized as of value to the company
    + Amount of holiday packages that fall under their recognized package knowledge
16. A customer score can be calculated using the following:
    + Average call duration
    + Average sale success
    + Total calls made to company
    + Amount of holiday packages recognized as relevant to their elected preferences
    + Average budget range
17. A final skill match will be obtained using the following:
    + RMs with a higher skill score will be considered higher performing
        * They will receieve more inbound calls, and customers on their target list will be more challenging to sell to
    + Customers with a higher customer score will be considered easy-going, flexible, and easier to make a sale with
        + They will receive more outgoing calls, and be prioritized when making an inbound call
    + RMs will be given a temporary suitability score for each inbound call
        * That score will be calculated from the number of matching criteria they have with the customer calling
        * Factors include age, sex and cultural background 
18. RMs can add information about specific users to influence their score
    + The Profiler Tool will elicit information purely from a customer's postcode and address
    + RMs can input additional fields including a user's likes and dislikes using keywords that match with holiday packages
    + RMs can also include a rating of a customer to include in their profile, so friendly customers who are easy to sell to will be prioritized.
19. The Interactive Voice Response unit can accept customer feedback
    + Upon ending a call, the unit can request a customer leave a recording of their feedback of their experience
    + Information will be gathered and influence an RM's skill score
20. Information can automatically be gathered by the Interactive Voice Reponse unit, and stored in a database.
    + Keywords can be elicited when a customer is prompted to give feedback or indicate why they are calling
    + This can be used to add to a customer's profile, or an RM's skill score and directly added to the database
    + It would be very inefficient to manually record this data and hurt business growth.
21. Scripts will be automatically generated for each outbound call
    + A script will be created based on the profile of the customer being called
    + Scripts will not be enforced for employees to encourage spontaneity and a unique service for each customer
    + Scripts will be designed for newer/inexperienced employees to have prompts for their calls

### <div align='center'> Workproducts </div>
-------------------------------------------------------------------------------

#### User Stories
Product owner:
* As a product owner, I want an information system that will improve the call put through rate, so that are service can satisfy more customers with a lower cost.
* As a product owner, I want the information system to aid RMs through scripted sales techniques, so that junior RMs can feel more confident selling.
* As a product owner, I want the information system to match each RM to customers that are looking for specific packages that the RM specialises in so that the customer is provided the best service possible.
* As a product owner, I want the information system to correctly adjust for each customer according to the RMs specialised skills and expertise so that custoemrs are served efficiently and effectively.
* As a product owner, I want the information system to effectively develop a customer target list for each RM so that they can make outbound calls to relevant customers.
* As a product owner, I want the information system to direct customers to an interactive voice response during busy times so that they can then subsequently be directed to the first available relevant RM.

Relationship Managers:
* As a relationship manager, I want my call performance with previous customers evaluated by their efficiency and effectiveness, so that i can improve my ability as a sales-person.
* As a relationship manager, I want the information system to match myself to customers with a similar demographic and skillset, so that I can best demonstrate and apply my existing knowledge when pitching holidays.
* As a relationship manager, I want greater automation in assessing which customers I should be calling and who should contact me, so that customer's I receieve share an interest in packages i am knowledgable about.
* As a relationship manager, I want assistance from the call system when speaking to potential customers, so that I can feel comfortable talking to difficult customers and navigating difficult business negotiations.
* As a relationship manager, I want the customer to be guided through a waiting process when the lines are busy, so that the customers we serve are not frustrated by the agency process before doing business with us.

Customer:
- As a customer, I want my loyalty to the travel agency to be recognized, so that i have incentive to continue returning to the service.
- As a customer, I want the specifics of my holiday plans understood and incorporated into existing holiday packages, so that I have a reason to use the travel agency as opposed to booking my own holiday.
- As a customer, I want to feel that I have received value for money when purchasing holiday deals, so that i am confident the package i receieve was best for my interests and needs.
- As a customer, I want to be able to speak with an RM of a similar socio-cultural demographic, so that I can feel more comfortable and confident discussing important business decisions.
- As a customer, I want to be made aware of how my personal or sensitive information will be used by calling system, so that I can feel comfortable disclosing this to the agency. 

#### User Story Map
User story map is simply a visual representation of the above user stories. Colors indicate the priority given to each task. Placement (left or right) indicates the likely difficulty to implement each user story as a feature.
<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/User%20Story%20Map.jpeg?raw=true "User Story Map")
</img>

#### <div align='center'> Use Case Diagrams </div>

##### RM: Making an outgoing call
This use case covers a Relationship Manager performing an outgoing call. This use case assumes the RM has not yet received their target list and one is generated for them.

<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Outbound%20Use%20Case.png?raw=true "Outbound Use Case")
</img>

##### Customer: Making an inbound call
This use case covers a customer making an inbound call to the travel agency. This additionally covers a case where the customer is completely new to the system, and checks for wait times.

<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Inbound%20Call%20Use%20Case.png?raw=true "Inbound Use Case")
</img>

##### RM: Hiring a new RM
This use case addresses the data collection processes that occur when a new RM is hired, and logs their information with the system. The use case does not include any work or performance conducted by the RM, only introducing them to the system.

<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/RM%20Hired%20Use%20Case.png?raw=true "RM Hired Use Case")
</img>

#### <div align='center'> Activity Diagrams </div>

##### RM: Making an outbound call
In this activity diagram, the scenario of an RM performing an outbound call is shown. It is assumed that the RM has not yet receieved their weekly list of potential customers. It is also assumed that the customers the RM is calling have already had their user profiles generated. The scenario ends with the call being received and does not include receiving feedback or evaluating the call.

<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Outbound%20Call%20Activity%20Diagram.png?raw=true "Inbound Call Activity Diagram")
</img>

##### Customer: Making an inbound call
The following activity diagram visualizes the scenario of a customer performing an inbound call the system. An optional case of a customer being new to the system is included. Note: To find an RM to talk to the customer the system calculates the interests and scores of the customer, interests and scores of the RM, then finds a set of RMs that are of reasonable match to the customer and ranks them by their estimated wait times. A customer will be connected to the first RM in this shortlist of suitable candidates.

<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/Inbound%20Call%20Activity%20Diagram.png?raw=true "Inbound Call Activity Diagram")
</img>

#### <div align='center'> Class Diagram </div>

Below is a class diagram modelling all major system entities. Data will be stored for any customer or RM interacting with the system. Information about calls will be stored to assess RM performance. Information about skills and holidays will be used to assign skills and knowledge to RM profles, and previously booked holidays to Customers.

<img style="float: center;">

![](https://github.com/Cormac-H/ISDM-Assignment1/blob/master/System%20Class%20Diagram.png?raw=true "System Class Diagram")
</img>

#### <div align='center'> Collaboration Diagrams </div>
- Use to mark off issues
    + Collaborative diagrams

###  <div align='center'> Competitive Advantages </div>
-------------------------------------------------------------------------------
Potential benefits of our new system:

Installing a multilayered information system will fundamentally transform the entire operations of the call centre, with increased levels of automation this will lead to business processes becoming more efficient and effective with less human error and a significant cost reduction. Furthermore, the newly formed information system will provide the call centre with a point of difference allowing them to gain a major step on their competitors. 

The implementation of the system will allow the Call Management Centre to attain a competitive Advantage through:

+ Automated call flows of both inward outwards allow for a more efficient time and cost reduction method

+ Improved matchmaking system for customers allow a more precise and time efficient process eliminating potential confusion and increasing the chances of a sale

+ Enhanced efficiency will occur through the system’s unique ability to target and identify potential buyers through a database      

+ Less reliance on human error through greater levels of automation will reduce costs exemplified through the inward call system whereby it reduces the call handling time

+ Improved customer experience through busy call times where they’ll be directed to a virtual response team which can assist them in any questions, they may potentially have

+ Increased revenue through the system’s ability to personalise the sale towards the customer

+ Opportunity for the business to grow and expand due to the increased revenues and cut in costs 


Adverse effects for business if our system fails:

The main risk if the system project fails is the amount of capital that would be lost due to implementing and maintaining the system on a daily basis. The risk of a failure of system would put the business into a dire financial situation. The initial investment of installing the system would be a sunk cost. Additionally, the multitude of resources and money used to educate the staff on how to operate the complex system as well as the intricacies of the technology that comes with it would be a lost investment as well. The business will have to return to the prior method they were using which in turn will lead to a less efficient more costly operating system furhter crippling the business. Furthermore, if the system fails the business will suffer as a whole from a brand and reputation perspective where current and future customers may be against the idea of using this particular travel company as they’ll be put off by the current negative situation the firm is in.

### <div align='center'>Project Methodology </div>
-------------------------------------------------------------------------------
Two main project methodologies have been followed for this system design, namely Design Thinking and Scrum. Design thinking has been used to outline and elicit clear stakeholder requirements of the system to establish and define a problem. Scrum and Scrum activities have then been used to develop working models based on this problem definition. It is highly recommended any team that continues with implementation of this system uses Scrum or another form of Agile methodology.

#### Design Thinking
The reason for a Design Thinking approach for preliminary system design was that a clear problem definition was not present before beginning. An advantage of Design Thinking was that it allowed us to output consistent work products and efficiently elicit stakeholder needs before system implementation. The following is an explanation and justification of how and why our team executed the stages of design thinking in our project:
- Empathize:
    + This process involved the identification of key stakeholders of the system, and creating empathy maps for these users
    + An application of empathy mapping has allowed our team to gain a detailed insight into current users and the product owner of the system to generate ideas about what should change, what the system needs, and what should stay
    + Before idea generation began this step included problem generation, where each problem stakeholders were facing presented a possibility for a solution
- Define
    + This stage of design thinking allowed us to create a clear problem definition based of the elicited user needs and their perspectives
    + POV and HMW statements have been created in order to list existing issues, goals, desires, needs, and feelings of stakeholders and turn these into statements for solution generation

The justification for stages 1 and 2 of Design Thinking was that the business is inherently customer centric, and requires a methodology and artefacts which respect this. It allowed us to systematically identify user needs and allow us to create a system that listens to the demands of its customers as well as the employees in contact with them. Clear pain points have been identified by the end of HMW statements, and these Design thinking stages allow for these to be removed in the customer's journey. All inferences taken have been logical extensions of stakeholder desires, and create a strong framework for the following stages.
- Ideate
    + Ideation has helped to form appropriate design solutions to the problems defined and empathized with in early stages
    + This was created during system analysis and brainstorming
    + A clear layout for the system was created where solutions to the problems were met and integrating as part of a functional call system
    + HMW statements can be viewed alongside the solution to follow side by side in how the system meets stakeholder needs
- Prototype
    + For the purposes of this project development, implementation will not be included
    + The prototyping stage has included the development of workproducts based on the system design generated through ideation.
    + A systematic transition from developing user stories about the system, to creating use cases, to drawing higher level activity, class, and collaborative diagrams can be made

The justification for stages 3 and 4 of Design Thinking are that they were a natural transition into developing tangible products based on elicited user needs. By creating a clear system design and preliminary models, the system is open to consistent evaluation to ensure models are still accurately reflecting user needs. Prototyping allows users to remain involved in the design process, and allow developers and users alike to understand the implementation of the system through user centric models and analysis models. 

- Testing 
    + As only workmodels will be produced for this project, testing will be achieved through consistent evaluation from stakeholders involved
    + This will include consistent self-evaluation from our team to ensure the project design remains customer centric and actively responds to concerns from users
    + This will include regular input from the product owner 

Testing is a necessity for any design methodology in order to achieve end success from the system. 

#### Scrum

The use of scrum as an agile methodology proved successful and useful in creating an end result that was effective and efficient. The use of scrum activities (sometimes known as events) allowed the team to remain on-track with necessary tasks. The activities used include product backlog, the sprints, sprint planning, sprint execution and daily scrums. Two post-sprint activities were also utilised, commonly known as artefacts, including the sprint review and the spring retrospctive.

   * The product backlog artefact was utilised by the team to ensure all existing features, features needing repair/fixing, improvements to be made and to ensure that these items can be deleted, added and/or changed as required. Using product backlog as a key activity allowed the team to stay on top of items and features that may have issues present or improvements that are required to be made.

   * Sprints were another key activity that was vital in creating a successful end product, and ensuring that the team stayed on track within the time frame allotted. The sprints were conducted on a monthly basis and in each sprint went for 30 days. Within each sprint, the team aimed to have tangible work to show the progress of the development of the in-house call management centre (CMC). 

   * Sprint planning was also vital activities in the use of the agile methodology scrum. The main use of sprint planning was to ensure all team members were in agreement about the goals that were to be achieved within the upcoming sprint. The team was then able to distinguish which items were more important than others, and what order to complete items in the product backlog.

   * The sprint execution activity was utilised by the team following the sprint planning, and enabled the team to perform all necessary tasks in order to get the features finished in the best way possible. Members of the team decided in which way they could best achieve the sprint goals, and hence worked to achieve the goal within the execution period.

   * The final main activity of the scrum agile methodology used was the daily scrum. Whilst meetings were not always daily, the team aimed to have 'daily' scrums as frequently as possible in order to talk about what each member has accomplished since the previous scrum meeting, what they were planning to work on before the next daily scrum, and any obstacles that potentially were preventing a team member from completing their designated tasks.

   * The sprint review proved vital in ensuring the product backlog was analysed and changed in needed, and to ensure that incremental progress was being made. These meetings were important in furthering the collaborative nature of the scrum agile methodology, and to ensure subsequent sprint plans had value inputs from the previous sprints. 

   * The sprint retrospective event was yet another activity/event that was highly important for the team to ensure plans were made for continuous improvement to be made during the next sprint. This sprint retrospective was conducted following the sprint reviews, but before the following sprint planning session. During these retrospective meetings, the team discussed such things as things that went well, things that should be improved upon, and what the team feels is a viable improvement for the following sprint.


- Justification of scrum:

Scrum was a successful and advantageous agile methodology to use for this project as it allowed the team to work collaboritively to develop both diagrams and working models that successfully showcase a preliminary design for the implementation of an in-house call management center (CMC) for the travel company. Engaging in such activities as 15-minute scrum meetings allowed the team to not only saave time, but also ensure that the necessary progress was being made throughout the process of this task. Scrum meetings also allowed the team better understand what tasks and activities were proving more difficult and/or what problems were blocking a team member from completing a task. When these blocks and issues arose, it was easier to deal with them in the weekly scrum meetings as all team members could contribute their ideas for potential solutions. Furthermore, through the use of scrum roles including a scrum master, team members and product owner, it was easy to implement scrum activities and tasks which allowed for seamless advancements on the development of the in-house CMC. Utilising scrum activities, in particular sprints, allowed the team to successfully stick to the required time-frame of the development process and helped ensure tasks were completed at the correct inervals. Another reason scrum proved a highly effective and efficient methodology was the ability for it to encourage continuous improvement. Team members were able to use retrospect to understand and accept what went well in the sprint, and what didn't work as well, or where problems may have potentially arisen. The team continuously improved over the course of the development process through using such tools as transparency, inspection and adaptation which allowed for a greater overall final result. Overall, the ability for scrum as a methodology to provide a freely-adaptable and uniquely flexible structure to ensure the end result was achieved as efficiently, effectively and with the greatest possible success.
