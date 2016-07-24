# LessonQ-A
----------------------------------------------------------------------------------------------------------------------------------
First activity
----------------------------------------------------------------------------------------------------------------------------------
1. Explain the principles of statistical quality control. What are the tools used for this purpose? Explain the principle of a control chart.
	Statistical quality control is the application of statistical methods (specifically control charts and acceptance sampling) to quality control. The seven basic tools of quality are cause-and-effect diagram (also known as the "fishbone" or Ishikawa diagram), check sheet, control chart, histogram, Pareto chart, Scatter diagram, and Stratification. Control charts in statistical process control are tools used to determine if a manufacturing or business process is in a state of statistical control. Typically control charts are used for time-series data, though they can be used for data that have logical comparability, however the type of chart used to do this requires consideration.
2. Explain the concept of lean principles.
	The five-step thought process for guiding the implementation of lean techniques: 
•	Specify value from the standpoint of the end customer by product family.
•	Identify all the steps in the value stream for each product family, eliminating whenever possible those steps that do not create value.
•	Make the value-creating steps occur in tight sequence so the product will flow smoothly toward the customer.
•	As flow is introduced, let customers pull value from the next upstream activity.
•	As value is specified, value streams are identified, wasted steps are removed, and flow and pull are introduced, begin the process again and continue it until a state of perfection is reached in which perfect value is created with no waste.

3. What is an “Ishikawa” diagram? When should the Ishikawa diagram be used? Provide a procedure to construct an Ishikawa diagram.
	Ishikawa diagrams are causal diagrams created by Kaoru Ishikawa that show the causes of a specific event. Common uses of the Ishikawa diagram are product design and quality defect prevention to identify potential factors causing an overall effect. How to create Ishikawa diagram:
•	Create a head, which lists the problem or issue to be studied.
•	Create a backbone for the fish (straight line which leads to the head).
•	Identify at least four “causes” that contribute to the problem. Connect these four causes with arrows to the spine. These will create the first bones of the fish.
•	Brainstorm around each “cause” to document those things that contributed to the cause. Use the 5 Whys or another questioning process such as the 4P’s (Policies, Procedures, People and Plant) to keep the conversation focused.
•	Continue breaking down each cause until the root causes have been identified.

4. What is total quality management (TQM)? What is the difference between TQM and TQC?
Total quality management (TQM) consists of organization-wide efforts to install and make permanent a climate in which an organization continuously improves its ability to deliver high-quality products and services to customers. The difference between total quality management and total quality control is that TQM expresses about continuous improvement in the processes while TQC is about maintaining the quality standards throughout the process

5. Explain the differences between validation and verification.
	Validation is the assurance that a product, service, or system meets the needs of the customer and other identified stakeholders. It often involves acceptance and suitability with external customers. Verification is the evaluation of whether or not a product, service, or system complies with a regulation, requirement, specification, or imposed condition. It is often an internal process.

6. Explain the differences between failure, error, and fault.
  Failure is the inability of a system or component to perform its required functions within specified performance requirements. Error is a discrepancy between a computed, observed, or measured value or condition and the true, specified, or theoretically correct value or condition. Fault is an incorrect step, process, or data definition in a computer program which causes the program to perform in an unintended or unanticipated manner.

7. What is a test case? What are the objectives of testing?
  A test case is a set of conditions under which a tester will determine whether an application, software system or one of its features is working as it was originally established for it to do. The major objectives of Software testing are as follows:
•	Finding defects which may get created by the programmer while developing the software.
•	Gaining confidence in and providing information about the level of quality.
•	To prevent defects.
•	To make sure that the end result meets the business and user requirements.
•	To ensure that it satisfies the BRS that is Business Requirement Specification and SRS that is System Requirement Specifications.
•	To gain the confidence of the customers by providing them a quality product.

8. Explain the concepts of unit, integration, system, acceptance, and regression testing.
	Unit testing is performed by developers before the setup is handed over to the testing team to isolate each part of the program and show that individual parts are correct in terms of requirements and functionality. Integration testing is the testing of combined parts of an application to determine if they function correctly. System testing tests the system as a whole. Once all the components are integrated, the application as a whole is tested rigorously to see that it meets the specified Quality Standards. Acceptance testing is arguably the most important type of testing, as it is conducted by the Quality Assurance Team who will gauge whether the application meets the intended specifications and satisfies the client’s requirement. Regression testing is performed to verify that a fixed bug hasn't resulted in another functionality or business rule violation.

9. What are the different sources from which test cases can be selected?
•	Requirement and Functional Specifications
•	Source Code
•	Input and output Domain
•	Operational Profile
•	Fault Model
  o	Error Guessing
  o	Fault Seeding
  o	Mutation Analysis

10. What is the difference between fault injection and fault simulation?
  Fault injection is a technique for improving the coverage of a test by introducing faults to test code paths, in particular error handling code paths that might otherwise rarely be followed. Fault simulation guides the TPG process, measures the effectiveness of the test patterns, and generates fault dictionaries.

11. Explain the differences between structural and functional testing.
	 Structural testing is considered white-box testing because knowledge of the internal logic of the system is used to develop test cases. Structural testing includes path testing, code coverage testing and analysis, logic testing, nested loop testing, and similar techniques. Unit testing, string or integration testing, load testing, stress testing, and performance testing are considered structural. Functional testing addresses the overall behavior of the program by testing transaction flows, input validation, and functional completeness. Functional testing is considered black-box testing because no knowledge of the internal logic of the system is used to develop test cases. System testing, regression testing, and user acceptance testing are types of functional testing. 

12. What are the strengths and weaknesses of automated testing and manual testing?
	Strengths of automated testing:
•	Runs tests quickly and effectively
•	Can be cost effective
•	More interesting
•	Everyone can see results
Weaknesses of automated testing:
•	Tools can be expensive
•	Tools still take time
•	Tools have limitations

Strengths of manual testing:
•	Short-term cost is lower
•	More likely to find real user issues
•	Manual testing is flexible

Weaknesses of manual testing:
•	Certain tasks are difficult to do manually
•	Not stimulating
•	Can’t reuse manual tests
 
---------------------------------------------------------------------------------------------------------------------------------
Second activity
---------------------------------------------------------------------------------------------------------------------------------
1. Study the Yourdon [2] concept of a design walkthrough and the IBM concept [1] of a design inspection. Discuss the similarities and the differences between them.
  The definition of walkthrough by Edward Yourdon is that it is a review where the author leads the team through a
manual or simulated execution of the product using predefined scenarios. The definition of inspection by Michael Fagan is that it is a step-by-step peer group review of a work product, with each step checked against predetermined criteria.

2. A software engineering group is developing a mission-critical software system that will launch laser-guided missiles to its destinations. This is a new kind of product that was never built by the company. As a quality assurance manager, which code review methodology—walkthrough or inspection—would you recommend? Justify your answer.
  I would choose an inspection code review methodology. Because since the group is developing a mission-critical software system, the method should be done with careful consideration of each members in the group which concerns about the quality of the product. Lots of preparations should be needed and overviews should be done in planning so that the inspections are held properly.

3. What size of a review team would you recommend for the project in exercise 2, and why? What are the different roles of each member of the review team? What groups should send representatives to participate in code review?
  Four. The Author, the Moderator, the Reviewer, and the Reader. The Author explains the background, motivation, and goals for the review. The Moderator sets the pace of this meeting and makes sure everyone is performing their role and not ruining anything with personal attacks. If the reviewer sees something amiss, they can engage in a little "spot pair-programming" as the author writes the fix while the reviewer hovers. The Reader presents the Materials because it was his job to "read for comprehension" since often someone else's misunderstanding indicates a fault in the Materials.

4. Suppose that the C programming language is chosen in the project in exercise 2. Recommend a detailed code review checklist to the review team
  

5. In addition to code review, what other static unit testing techniques would you recommend for the project in exercise 3? Justify your answer.


6. Describe the special role of a recordkeeper.
  The recordkeeper documents the problems found during the review process and the follow-up actions suggested. The person should be different than the author and the moderator.

7. Discuss the importance of code review rework and validation.
  Code Review is important because it is to create collective ownership of the software’s progress through knowledge transfer by inspecting the source code as a team. The standardization of code and formatting leads to a more accurate source code as a byproduct, but the overall goal is to keep the team involved in planning the later phases of development. Validation is important because by validating the current process, we are usually able to discover workarounds that no one knew was there, allowing us to find the root cause of an inefficient process much faster.
