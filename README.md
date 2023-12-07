# Timetable Generation System (TTGS)

## School of Computer Science, MITWPU
### Academic Year 2023-24
### MCA Sem III
### Mini Project on Open-Source Development

**Project Team Member:**
- Name: Jigyasu Singh Chouhan
- Roll No: 39
- Class: SYMCA
- Batch: 2022-2024
- Email: SINGHJIGYASU53@GMAIL.COM

## Configuration Setup

**To run this project on your local server, follow the following
steps:**

-   Install Python 3.8 on your Computer from the official website.

-   Install Django on your computer by running this command

**pip install Django(For windows)**

-   Install Django Crispy Forms by running this command:

**pip install django-crispy-forms**

-   Install Django Multi select fields on your computer:

**pip install django-multiselectfield**

-   If you don’t have Git Bash/Git Bucket on your computer. Then install
    it first.

> Run this command on your git terminal

git clone
[“https://github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS”](“https:/github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS”)

-   After clonning the repository in your computer, run the command:

**cd ActivitySelectionTimetable**

-   Run this command to run server on your localhost:8000

**python manage.py runserver**


# Abstract

The Timetable Generation System (TTGS) is a web-based application designed to automate and optimize the creation of academic timetables for educational institutions. By leveraging the Genetic Algorithm, TTGS addresses the inefficiencies associated with manual scheduling, taking into account various constraints to efficiently allocate resources. The system aims to enhance the overall academic experience, optimize resource utilization, and save time for administrators.

TTGS is characterized by its user-friendly interface and scalability, offering a practical solution to streamline the complex process of timetable generation in educational settings. However, it is essential to acknowledge certain limitations, particularly related to the quality of input data and computational time for intricate scenarios.
 
The implementation of TTGS involves the use of Python, Django, andSQLite technologies. These tools contribute to the system's effectiveness in automating and optimizing the timetable generationprocess. As a result, TTGS stands as a valuable resource for educationa  institutions seeking to improve the efficiency and effectiveness of their scheduling practices.

# Introduction:
 The introduction of the Timetable Generation System (TTGS) signifies a response to the intricate scheduling demands encountered by educational institutions, particularly in the creation of academic timetables. This web-based application is crafted to alleviate the challenges associated with manual timetable generation, aiming to automate and optimize the process. The decision to embark on this project is motivated by the inefficiencies inherent in traditional manual scheduling methods and the complexities posed by various constraints in educational timetabling.TTGS aims to streamline the labor-intensive and error-prone nature of
manual timetable creation by leveraging the power of the Genetic Algorithm (GA). The GA serves as the cornerstone of the system, offering an efficient approach to generating conflict-free timetables while accommodating both hard and soft constraints. This introduction sets the stage for understanding the objectives of TTGS, addressing the need for automation, optimization, and improved resource allocation in academic scheduling.

# Development tool and technology

The Timetable Generation System (TTGS) is developed using acomprehensive set of tools and technologies tailored to meet the  specific requirements of the project. The core development tools include Python 3.8, Django 3.0, HTML5, CSS3, and JavaScript. These technologies
collectively form the foundation for both the user interface and the backend logic of the web-based application.

\- Python 3.8: The programming language chosen for its versatility and efficiency in handling complex algorithms, particularly the Genetic Algorithm used for timetable optimization.

\- Django 3.0: A high-level Python web framework selected to facilitate the development of a robust and scalable web application. Django streamlines the creation of the user interface and provides security
features.

\- HTML5 and CSS3: Utilized for designing the web-based user interface, ensuring a visually appealing and responsive experience for administrators interacting with the system.

\- JavaScript: Enhances the interactivity of the web interface, enabling dynamic and user-friendly functionalities.

These development tools collectively contribute to the efficiency, scalability, and user-friendliness of TTGS. Additionally, the use of these technologies aligns with industry best practices in web application development, ensuring a reliable and effective solution for
the complex task of academic timetable generation.

**Advantages: --**

The Timetable Generation System (TTGS) offers a range of advantages, enhancing the efficiency and effectiveness of academic scheduling foreducational institutions. These benefits underscore the value and impact of implementing TTGS:

1.  Efficiency: TTGS automates the otherwise time-consuming process of timetable creation, significantly reducing the manual effort andtime required for administrators.

2.  Optimization: Leveraging the Genetic Algorithm, TTGS optimizes timetables by minimizing conflicts and maximizing the efficient allocation of resources such as classrooms, teachers, and courses.

3.  User-Friendly Interface: The web-based interface of TTGS is designed with user-friendliness in mind, allowing administrators to easily input data, monitor progress, and download generated timetables.

4.  Flexibility: TTGS is adaptable to the diverse scheduling needs of various educational institutions, from schools to universities, roviding a flexible solution for different environments.

5.  Resource Utilization: Through optimization techniques, TTGS  maximizes the utilization of available resources, leading to cos   savings for educational institutions.

6.  Conflict Resolution: The system efficiently handles constraints,  minimizing scheduling conflicts and disputes, thus creating a more  streamlined and harmonious scheduling process.

**SOFTWARE DESIGN PATTERNS:**
In the development of the Timetable Generation System (TTGS), varioussoftware design patterns have been employed to enhance the structure,efficiency, and maintainability of the codebase. These design patternsserve as proven solutions to common software development challenges. Keysoftware design patterns integrated into TTGS include:

1.  **Genetic Algorithm Design Pattern:** This pattern is fundamental to  the optimization process within TTGS. The Genetic Algorithm,  inspired by natural selection, is applied to efficiently generate  conflict-free timetables by evolving and selecting optimal
    solutions.

These design patterns contribute to the modularity, scalability, andclarity of the TTGS codebase, facilitating the development of a robustand maintainable system. They encapsulate best practices in softwaredevelopment to ensure the effectiveness and adaptability of the
solution.

# Business processes of existing system:

**Business Processes of the Existing System:**

The current manual system of timetable creation in educationalinstitutions involves several labor-intensive and sequential businessprocesses. These processes are integral to the functioning of academicscheduling and include:

1.  **Data Collection:**

    -   Gathering information about courses, teachers, classrooms, and other relevant resources.

    -   Compiling teacher availability, class preferences, and any other  nstraints.

2.  **Constraint Analysis:**

    -   Analyzing and identifying constraints such as unique class timings, teacher availability, and classroom capacities.

    -   Manually checking and ensuring adherence to departmental  equirements and other scheduling constraints.

3.  **Scheduling Coordination:**

    -   Coordinating with various departments to align schedules with specific academic and administrative needs.

    -   Resolving conflicts manually, such as overlapping class  hedules or resource double-bookings.

4.  **Manual Timetable Creation:**

    -   Physically creating timetables based on the gathered data and constraints.

    -   Iterative manual adjustments to resolve conflicts and meet  heduling requirements.

5.  **Review and Approval:**

    -   Reviewing the manually created timetables for accuracy and compliance with institutional policies.

    -   Seeking approvals from relevant stakeholders, such as department heads or administrators.

6.  **Communication:**

    -   Communicating the finalized timetables to teachers, students, and other stakeholders.

    -   Handling requests for changes and making subsequent manual adjustments as needed.

7.  **Record Keeping:**

    -   Maintaining manual records of timetables, changes, and approvals for future reference

# Problems and constraints:

The existing manual system of timetable creation in educationalinstitutions faces several challenges and constraints that impact itsefficiency and effectiveness. Key problems and constraints include:

1.  **Time-Consuming Process:**

    -   **Problem:** Manual timetable creation is labor-intensive, requiring significant time and effort.

    -   **Constraint:** Administrators spend considerable time  avigating through complex scheduling tasks.

2.  **Error-Prone Scheduling:**

    -   **Problem:** Human errors in data entry and scheduling adjustments are common.

    -   **Constraint:** The manual process increases the likelihood of  conflicts, overlapping schedules, and inaccuracies.

3.  **Complex Constraints:**

    -   **Problem:** Academic timetables are subject to various  constraints, both hard and soft.

    -   **Constraint:** Manually handling intricate constraints, such as  nique class timings and teacher availability, can be  hallenging.

4.  **Resource Optimization Challenges:**

    -   **Problem:** Efficiently allocating resources like classrooms, teachers, and courses is complex.

    -   **Constraint:** The manual approach may not maximize resource  tilization, leading to suboptimal schedules.

5.  **Dependency on Human Judgment:**

    -   **Problem:** Timetable adjustments and conflict resolution depend heavily on human judgment.

    -   **Constraint:** Subjectivity in decision-making can lead to inconsistencies and disputes.

6.  **Communication and Coordination Issues:**

    -   **Problem:** Communicating timetable changes and resolving conflicts manually can be cumbersome.

    -   **Constraint:** Lack of real-time coordination may result indelays and miscommunications.

7.  **Limited Adaptability:**

    -   **Problem:** Manual systems are less adaptable to changes in student enrollment or faculty availability.

    -   **Constraint:** The system struggles to accommodate dynamic scheduling needs and unexpected events.

8.  **Record-Keeping Challenges:**

    -   **Problem:** Maintaining and archiving manual records oftimetables is prone to errors and may lack organization.

    -   **Constraint:** Retrieving historical data for analysis or   reference can be time-consuming.

#  Requirement specification:

The Timetable Generation System (TTGS) is designed to meet the followinkey requirements, addressing the challenges posed by the manualtimetable creation process in educational institutions:

1.  **Automation of Timetable Creation:**

    -   *Objective:* To automate the process of academic timetable  creation, reducing manual effort and streamlining the overall   scheduling workflow.

2.  **Optimization of Timetables:**

    -   *Objective:* To apply optimization techniques, specifically the Genetic Algorithm, to generate conflict-free timetables while  considering both hard and soft constraints.

3.  **User-Friendly Interface:**

    -   *Objective:* To provide a user-friendly web-based interface for administrators, facilitating easy data input, progress monitoring, and timetable downloads.


# Interface requirements:


The Timetable Generation System (TTGS) is designed with user interfacethat prioritize simplicity, functionality, and accessibility. The userinterfaces cater to the needs of administrators responsible for managingand creating academic timetables. The interface requirements include:

1.  Web-Based Interface:

    -   *Description:* The primary interface for TTGS is web-based, accessible through standard web browsers.

    -   *Objective:* To ensure ease of access and flexibility for  ministrators who can use the system from various devices  ithout the need for additional software installations.

2.  Intuitive Data Input Forms:

    -   *Description:* User-friendly forms for inputting data related to courses, teachers, classrooms, and scheduling constraints.

    -   *Objective:* To simplify the data input process, reducing thelikelihood of errors and enhancing the overall user experience.

3.  Real-Time Progress Monitoring Dashboard:

    -   *Description:* A dashboard displaying real-time progress in the   timetable generation process, including ongoing optimizationsand any conflicts being addressed.

    -   *Objective:* To provide administrators with a visual overview ofthe system's progress and status.






# Conclusion:

The Timetable Generation System (TTGS) addresses the challenges ofmanual timetable creation in educational institutions. By leveraging thepower of the Genetic Algorithm and utilizing web technologies, TTGSprovides an efficient and user-friendly solution to optimize resourceallocation and streamline the scheduling process.

# Reference and bibliography:

1\. \[GeeksforGeeks - Genetic Algorithms\](https://www.geeksforgeeks.org/genetic-algorithms/)

2\. \[Ander Fernandez - Genetic Algorithm in Python\](https://anderfernandez.com/en/blog/genetic-algorithm-in-python/)

3\. \[Towards Data Science - Using Genetic Algorithms to Schedule Timetables\](https://towardsdatascience.com/using-genetic-algorithms-to-schedule-timetables-27f132c9e280)
![Add-Professor](https://github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS/assets/52603806/e2d2bfc5-0594-4fbf-8e61-3722398cfd35)
![Add-Course](https://github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS/assets/52603806/34bc2820-cb2c-45a2-b650-1360ecabbbd7)
![Add-classroom](https://github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS/assets/52603806/07aa49fa-3344-4a49-95c4-bdeee67a2b4b)
![add-Class](https://github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS/assets/52603806/d3df0b91-ddb0-4371-a7d3-f44bdbe29c64)
![main-page](https://github.com/Jigyasusinghchouhan/Timetable-Generation-System-TTGS/assets/52603806/dd84e97f-0ba0-4269-ab8e-04f9104dc162)

