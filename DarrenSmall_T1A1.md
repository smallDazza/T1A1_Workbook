# T1A1 Workbook Assignment
# Adding additional Features:
##  Testing  the branch

### Question 1 Answers: 
~~~
The following markup languages are used in web development:
 - HTML : HyperText Markup Language is used to create website pages. HTML defines the layout, structure and content displayed by defining different elements or tags in specific locations to render the appearance of text, images, multimedia or links to other files to display in a web browser. An element is placed by starting with a tag name (case sensitive) inside of an opening pair of "<" *name* ">", then the element content to display (not in all cases), and ended with the same tag name closed by a pair of "</" *name* ">". Some important must have element tags are `<html></html>, <head></head>, <title></title>, <body></body>` . Others are `<header>, <footer>, <p>, <img>, <article>, <section>, <div>, <ul>, <ol>, <li>.`

 - XML : EXtensible Markup Language is used to store and transfer data.It is different to HTML in that the document creator can define the tags and structure. XML tags are customised for the purposes of the document being sent, but are enclosed in the same opening and closing angle brackets. The XML language is a standardised format so all different types of applications can interpret the same data.

 - XHTML : EXtensible HyperText Markup Language is a combination between both HTML & XML. It combines the presentation functions of HTML but with the strict standardised rules of XML. The XHTML syntax is very strict, and each page needs to include one of 3 types of DTD (Document Type Definition) declarations. These XHTML element tags are mandatory in a document:  <!DOCTYPE> , `<html></html>`, a "xmlns" attribute must be in the `<html>` tag, `<head></head>, <title></title>, <body></body>`. The XHTML elements must also be in lowercase, properly nested and always closed.

References:
Radic, Z., 2019. Markup Languages: What They’re All About. [Online] 
Available at: https://wpamelia.com/markup-languages/
docs, m. w., 2024. HTML. [Online] 
Available at: https://developer.mozilla.org/en-US/docs/Glossary/HTML
w3schools.com, 2024. HTML Tutorial. [Online] 
Available at: https://www.w3schools.com/
~~~

### Questions 2 Answers:
~~~ 
- packets : A packet is a unit of data that is grouped together and sent over a network or the internet. Each packet has the information it needs to get to its destination like receivers IP address, senders IP address, how many packets the message or file is broken into and the number of each packet.

- IP addresses (IPv4 and IPv6)  : IP addresses are used to identify the computers / devices of both sending and receiving over a network or the internet. IPv4 IP addresses use a 32bit format and broken into 4 parts, example: 172.0.68.109. IPv6 uses 128 bit format, also include letters and use colons to separate segments, example: fe80::26f0:1ffe:b96c:93b9%12.

- Routers and Routing :  A router is a device that connects computers / devices over networks and the internet. It determines and sends the data on the best possible path by analysing the network metrics.
  - Routing is the process of selecting the best possible path for data to flow over a network or the internet. This helps reducing network failure by controlling the flow and congestion on a network.

- Domains and DNS : A domain is the host name or address of a website that users type in their browser url area to visit that website.
  - DNS is short for Domain Name System which essentially translates website domain names into IP addresses. It is a global network of servers that acts like a giant directory to convert domain names into IP addresses & vice versa.

- Explain how each technology has contributed to the development of the internet: Each technology has vastly increased the development of the internet. As computers, mobile phones and all other types of devices have better technology with applications to access the internet, all these devices will be assigned IP addresses. This continually increases the amount of data packets being sent & received, which  will always result in the need for better routers & technology. The more devices are accessing more & more domain names, will also result in the need for better DNS servers. 

References:
Yasar, K., 2023. Definition: Network packet. [Online] 
Available at: https://www.techtarget.com/searchnetworking/definition/packet
Yasar, K., 2023. IP address (Internet Protocol address). [Online] 
Available at: https://www.techtarget.com/whatis/definition/IP-address-Internet-Protocol-Address
AWS, 2023. What is Routing?. [Online] 
Available at: https://aws.amazon.com/what-is/routing/
AWS, 2023. What is DNS?. [Online] 
Available at: https://aws.amazon.com/route53/what-is-dns/
Lutkevich, B., 2023. domain name system (DNS). [Online] 
Available at: https://www.techtarget.com/searchnetworking/definition/domain-name-system

 ~~~

 ### Questions 3 Answers (50 - 150 words for each technology):
 ~~~
- TCP : TCP stands for Transmission Control Protocol and is a standard protocol for ensuring successful communication deliveries between devices over a network or the internet. The TCP resides in the transport OSI layer and its role in communications between devices is to ensure the establishment of a connection and that all data has been delivered correctly. It does this by working in collaboration with Internet Protocol rules.
  TCP delivery has continually been developing between client & server since its creation back in the early 1970's. It was first designed for the US department of defence and then in the 1980's helped with the development of the internet to be a world wide network. One way TCP works between Server and client devices by a web server setting up a connection when asked by the HTTP layer, then the TCP stack will divide the file into numbered packets to be delivered and send them to the IP layer for delivery. 
  The TCP layer in the client device will wait and confirm all numbered packets have been received correctly, then assembles all the packets back into the file and send it to the application required.

- HTTP and HTTPS  : Hypertext Transfer Protocol is a set of communication rules between client & server. This protocol is the communications foundation of the internet for browsers and servers, but data transmitted is unencrypted. So in the 1990's a more secure protocol of http was developed called https = Hypertext Transfer Protocol Secure. The http is an application layer protocol that interprets different types of requests and responses between client & server. When wanting to view data from a website the client http protocol will send a series of "GET" requests to the server to ask for all the information it needs to load the webpage. To send information to the server (like a form), the client http protocol will send a "PUT" request.
  The server will also send back coded responses to these requests, some examples are: 400 = Bad Request, 404 = Resource Not Found.
  Https works in the same way but adds an extra layer of security by combining requests & responses with SSL & TLS certificates. These are shared by the client and server before exchanging data to verify a trusted connection.

- Web Browsers (requests, rendering and developer tools)  : Web Browsers are an application software for accessing and viewing websites over the internet. Using the http / https protocols between a client and server to receive the information requested, the browser will then compile the web documents to render them in html which is used to design web pages and display to the user the web sites content. Web browser features can include: a home page, URL address bar, navigation buttons, bookmark options, history of visited websites and refresh button.
Current web browsers will also include developer tools. These are tools that allow users to inspect & debug the rendered web sites html , css and javascript properties. Developers will use these to help in building better websites, diagnosing any problems and measuring its performance all in real time as they view / build the web page.

References:
Kinza Yasar, B. L., 2021. Definition: Transmission Control Protocol (TCP). [Online] 
Available at: https://www.techtarget.com/searchnetworking/definition/TCP
AWS, 2024. What’s the difference between HTTP and HTTPS?. [Online] 
Available at: https://aws.amazon.com/compare/the-difference-between-https-and-http/
GeeksforGeeks, 2024. Web Browser. [Online] 
Available at: https://www.geeksforgeeks.org/web-browser/
Rouse, M., 2023. Transmission Control Protocol. [Online] 
Available at: https://www.techopedia.com/definition/5773/transmission-control-protocol-tcp
Rouse, M., 2023. Web Browser. [Online] 
Available at: https://www.techopedia.com/definition/288/web-browser
Okta, 2023. HTTP vs. HTTPS: Definition, Comparison & Security Implications. [Online] 
Available at: https://www.okta.com/au/identity-101/http-vs-https/

 ~~~

 ### Question 4 Answers :
 ~~~
 - Interpreters / Compilers Features & Differences:
    - Interpreters: 
        - An interpreter is a computer program that reads source code in a high-level language like Python, Javascript and Ruby, and executes it line by line while the program is running. Because it converts into a lower-level language (machine code) in a sequential process, they generally tend to be slower than compilers.
        - But Interpreters are better for debugging code, because as it runs each line sequentially until a error occurs, they can easily be identified and fixed.
        - Memory required is less than a compiler.
        - If interrupted at any point, must restart from the beginning.
        - Relatively more flexible.

    - Compilers: 
        - A compiler is a program that executes a high-level language such as C, C++ and Java, into a lower-level language (machine code), in whole for the entire program. The resulting compiled code of the entire program can be executed directly by a computers OS, which is done by producing the output as an executable program file.
        - Compilers will operate quicker than interpreters.
        - After compiling the entire program code it will return any errors. This makes it much harder to locate and fix them.
        - Larger in size compared to interpreters.
        - Not flexible.

References:
Omer, M., 2023. Compilers vs. Interpreters: How They Work?. [Online] 
Available at: https://www.linkedin.com/pulse/compilers-vs-interpreters-how-work-monzer-omer
The Computing Teacher, 2020. Compiler / Interpreter Difference. [Online] 
Available at: https://www.thecomputingteacher.com/csc/index.php/programming/206-compiler-and-interpreter
Ben Sassi, R, 2023. Compiler vs Interpreter. [Online]
Available at: https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter

 ~~~

### Question 5 Answers :
~~~
Compare 2 Programming Languages.
- Benefits.
  - Python: 
  - The Python language has a simple syntax and format which makes it easier to learn and faster to write code, which for developers will increase their productivity in programming projects. It is also known for its ready to use modules, packages and libraries that can be imported into any Python files or projects. Compared to JS, Python considers everything as an object and supports mutability and it has multiple varieties of numeric data types. It is free and open source with a large world-wide community of followers for help and support.

  - Javascript:
  - The Javascript language is used for user functionality in web development and is preferred in this area for its high-performance speed and real time interactions compared to Python. It can be used for both the front-end & back-end sides of applications and also has a multi-threading feature making it highly scalable for application growth. Another benefit is it and can easily integrate with other languages like Python.

- Drawbacks.
  - Python:
  - Python execution speed can be relatively slower because it does it on a line by line basis which also contributes to greater memory usage. It is also much less scalable if application growth is required because it uses a global interpreter lock that runs only one thread at a time. Another drawback for Python is it is not suitable for mobile development as there is no mobile native support.
  
  - Javascript:
  - Javascript language syntax uses a variety of different symbols, making it harder to read and learn. It also has a limited set of numeric data types, objects and arrays are immutable and does not have many in built modules. Some other drawbacks for Javascript code are it can be visible to anyone and debugging errors are more complicated as may only appear at runtime.

References:
Infosystem, H., 2024. Python vs JavaScript: An In-Depth Comparison. [Online] 
Available at: https://www.linkedin.com/pulse/python-vs-javascript-in-depth-comparison-hyperlinkinfosystem-xcmkf
Jonna, V., 2024. Advantages and Disadvantages of Javascript. [Online] 
Available at: https://ellow.io/advantages-and-disadvantages-of-javascript/
Szkaradek, T., 2022. Pros and Cons of Python. [Online] 
Available at: https://thecodest.co/blog/pros-and-cons-of-python/
~~~

### Question 6 Answers :
~~~

Hi Alex,
  Thankyou for reaching out via email and yes we can definitely provide website services the SAM is wanting to encourage people to visit. I will
briefly explain who we are , what we do and our thoughts on how we can provide a dynamic website for the SAM.
  We are 'Awesome Websites Australia' and we have been building, evaluating and supporting company & community websites for over 15 years. We are based in
Sydney but have many clients all around the country and overseas. We have all the technologies and tools required to facilitate this, which allows us to be very cost effective and provide a full stack service from beginning to end so you can put your mind at rest that everything is covered. These services include:
  a.  Our customer service team will liaise with you directly and in person to specifically gather the SAM requirements, information needed and images to be used.
  b.  Our design team uses their own wire framing program, colour palettes matching, understanding of design standards to facilitate people with disabilities.
  c.  The development team will build the website in house, using the best practice standards for html, css and javascript.
  d.  We can do all the legal registrations needed, deploy live to the internet and update whenever required. All our teams are trained and will abide by the Australian regulations for privacy & security of company and personal information.  
  Please visit our website to view the types of clients and websites we have worked with: www.awesomewebsitesaustralia.com.au/

  Our staff have briefly put together some ideas for the SAM website, which will give you an idea of their expertise :
  1.  Home Page - the first landing page to show who the SAM is with dynamic images of your best pieces from around the world.
                - this will include a navigation bar with links to other pages such as : Featured Items , From Around The World , Our Location , Contact Us.
  2.  Featured Items Page - we think this page will be dedicated to the museums featured items or most popular pieces. This page is designed to draw the public's interest for those special famous items to see and can be continually updated as newer items come in or older items move out of interest.
  3.  From Around The World Page - this page can have a dynamic map of the world where users can be involved and interact with a 'Select A Country' map, which then opens a page displaying the Items the museum has from this country with information explaining the history, artist etc about each piece.
  4.  Our Location Page - this page will have the SAM location address with a Google maps area & location pin displayed. Different modes of transport to visit can also be shown for the public to know how easy it is to find the SAM. EG: If Train, then disembark at central station & catch bus T102 for 4 stops.
  5.  Contact Us Page - this will have all the SAM's contact details and social media links.

Any other features you think would be required like ticket sales, donations or newsletter registration and delivery can be discussed in the future.

I hope this explains and meets your expectations for the SAM website, please feel free to contact me further and I look forward to moving forward together.
Kind Regards,
Darren Small.
Awesome Websites Australia.
0449760334
~~~

### Question 7 Answers :
~~~
Situation 1: - Being employed as a Product Owner, we designed, produced and sold medication packing materials. We also included in our packaging supplies a software program for pharmacies to use to print the patients medication details on these packaging materials. This software program had been used for a long time before my employment and was becoming very old & outdated for the changing legal requirements required. So the decision was made to create and release a new software program. The company appointed a software development company for this task and I was in the lead team for project management.
  We supplied the developers a copy of our current program and the new requirements we needed in the new program.
  The Developers supplied us with a beta version for testing / reviewing BUT the program was not what we were expecting and didn't meet the needs, our clients would require for efficient productivity.
  Eventually with alot of back and forth and numerous beta testing versions, we did get the program our clients would be happy with & released.

My Feelings On Situation 1: - I was excited & looked forward on being involved in this project as I had never done anything like this before with software or internet based products. But I remember on that first beta test review being very disappointed and nervous that we had stuffed this up !! On reflection my feelings are it was a very big learning curve on how to approach such a project.

Analysis And Future Courses Of Action 1:  - We were not specific enough in relaying the requirements our new program needed to meet our clients needs or even the designs we had in our heads for it. In our documents the requirements were to general and then the developers did their own interpretation of what they thought we needed.
  In future I see that any / all requirement documents will need to be very specific. They will need to include the design we are thinking of , very specific legal requirements needed and the exact workflow we expect to happen in the program to meet our clients productivity.

Situation 2: - One of my first jobs was in a Customer Service role. While working, the company dispatched a number of faulty products out to customers. Taking a number of disgruntled customers phone calls regarding these orders, I had to follow the company resolution procedures on how to resolve the issue of these faulty products supplied. In brief the company procedure was; Customers responsibility to return the product, company inspected it to confirm was faulty or not, then a replacement was shipped to customer if faulty or returned to customer if not.

My Feelings On Situation 2: - My feelings at the time I remember were conflicted on following the company procedures to resolve these faulty products for customers. On one hand I knew I had to do my job professionally and follow the company procedures but on the other hand I did not agree with the process and resulting situation it put the customers in, when the issue was not the customers fault.

Analysis And Future Courses Of Action 2:  - Following the company procedures was the correct course of action, as that is what my role included in the Customer Services Team. On reflection of my conflicted feelings regarding these procedures: in the future my course of action would be to make my concerns known in customer service meetings and ask if we could look at changing the procedure slightly to increase customer satisfaction of an outcome to the issue. One of the outcomes to suggest would be:
- The company to first organise a replacement product.
- Then company to pick up the faulty product.
- Then upon inspection is either dealt with by the manufacturer, or refurbished for future sale.

~~~

### Question 8 Answers :
~~~
Action Plan For Networking Events Or Workshops: 
Event 1:  - I am attending for my current job: ![MongoDB.local Sydney](https://www.mongodb.com/events/mongodb-local/sydney)
 In my current job, the software application the company supplies uses a MongoDB database. My knowledge about MongoDB is limited to how our services use and relate to it and from what the companies Dev team have explained to me.
 Even though I am just starting out on my full stack development journey, my particular interest is in the back end area of development (databases, API etc), so from the different workshops available I am curious to find out how MongDB is being used more widely in the industry. 
 
Action Plan 1: 
 - Workshops I plan to attend are 'Methodology and Principles of Data Modelling for MongDB' + 'Building event-driven applications with Atlas Stream Processing', im hoping these workshops will provide insight and knowledge into some of the features mongoDB offer that I might be able to bring to our team at work.
 - Networking side of the event, I would like to speak to some developers and find out how they use MongDB and in general what they do, the applications they work on and how they started out in the industry. As im trying to start out in this industry, id like to speak to some experienced developers on how they did it and their advice on what to do / not to do.

Event 2:  - Online workshop Coder Academy, 20th June 2024, 6pm: 'Interviews, Preparation and How to get the most out of them!' - this is a webinar with a experienced software engineer who is experienced in helping other developers land new jobs, skills or promotions.

Action Plan 2:
 - Being that I have not had to many different jobs and therefore not done many interviews, my action plan here is to note down with great detail, his experienced guidance on how we should conduct ourselves, how we should show our skills to prospective employers in both technical and non technical areas for software development jobs. Looking forward to this and knowing 'How To Stand Out Among The Crowd' when it comes to interviewing for a new position.


Event 3:  - Looking forward in the future to any Coder Academy meet ups or industry speaker workshops for Sydney students (none to date!).

Action Plan 3:
 - For any workshops from industry speakers, Im very interested to know their roles and daily tasks as a developer and where they feel the industry in moving in the future. Then what they are looking for in starting out junior developers and any advice they can offer.
 - Networking side of any event, looking forward to sharing and understanding how other students are going / coping with the workload and just face to face conversations on coding etc. I think people are more honest with in person conversations than online chat conversations and will be more encouraging for students to keep pursuing the goals they started with.   
 ~~~

### Question 9 Answers :
~~~
There are multiple uses for LLM technologies on written and technical works such as reports and projects, these are:

- Gathering Information Faster: Information gathering for any report or project is a very time consuming exercise, either by using google, reading through websites, articles and books. Because of the huge amount of data and resources these LLM technologies have access to, it can produce/list the information required from multiple sources within a fraction of the time compared to gathering manually.
  - Example: A Doctor can produce a diagnosis or medication research report instantly while in consultation with a patient.

- Documentation Creation: LLM's can quickly generate many different types of draft documents quicker. Users just need to input their main points or provide an outline and the LLM will output the layout and content of the draft document required.
  - Example: A Project Manager can produce a project draft quotation on the details and costings of the project for the client.

- Using Natural Language: Reports & projects generated by LLM's will include insights and explanations provided in a natural language. This will make them easier for wider public access and any outcomes to be actioned faster.
  -Example: A Sales Manager can produce a sales report detailing all the sales figures and providing explanations for fluctuations and recommendations for future sales growth.

- Data Access In Real Time: Any stakeholder data access or analytics required will be available and reported in real time. This provides real time reliability and accuracy of data provided in LLM generated reports or projects.
  - Example: A financial institution can provide real time stock market reports with stock prices, trends and recommendations which traders respond to straight away. 

- Customised Project Documents: LLM's can be used for suggested requirements for customised documents such as technical documentation, user manuals, installation guides and release notes, which can be used for software / application projects.
  - Example: A Software Developer before deployment of a clients software application can quickly generate a user manual for the client to rely on when using the application.

Reference:
Johansson, J., 2023. ChatGPT for project managers: 8 benefits you don’t want to miss out on. [Online] 
Available at: https://resourceguruapp.com/blog/project-management/chatgpt-for-project-managers
Khalid, F., n.d. How to Use ChatGPT for Software Documentation. [Online] 
Available at: https://www.devteam.space/blog/chatgpt-for-software-documentation/

~~~


### Question 10 Answers :
~~~
Listed below are the legal and ethical impacts of using LLM technologies on written and technical works:

- Copyright Infringement - because LLM technologies are trained on a huge amount of data, they may produce content that is similar or identical to existing copyrighted material, which if used could be legally infringing on this material.
  - Example: Software project documentation may reference the same application features of a current registered product. 

- Data Privacy - LLM's could generate content that include personal or sensitive data information which could violate Privacy laws. 

- Accuracy And Reliability - because LLM technologies are trained on a huge amount of data, it may not provide the most accurate or reliable information on a particular topic. Content provided must always be checked for any bias or inaccurate referencing.
  - Example:  Can be used to produce legal documents such as contracts. They should still be reviewed and edited by a legal professional to ensure they are accurate and legally binding.

- Misinterpretation - This could also be used unethically to spread false and misleading information about individuals or companies.
  - Example: Could be used to generate or promote a conspiracy theory against a political party or politician.


References:
Baljević, D., 2022. ChatGPT and the Ethical and Legal Implications of Data and Technology. [Online] 
Available at: https://isg-one.com/articles/chatgpt-and-the-ethical-and-legal-implications-of-data-and-technology
Gordon, D. C., 2023. AI Ethicist Views On ChatGPT. [Online] 
Available at: https://www.forbes.com/sites/cindygordon/2023/04/30/ai-ethicist-views-on-chatgpt/
~~~


### Question 11 Answers :
~~~
Soft Skills - This term is used as a synonym for people skills or emotional intelligence. These skills and their importance in a software development workplace are:
- Communication: This is important for working together in a team environment. So that the team members ae all on the same page during a project for requirements, issues, deadlines and expectations on workload outcomes during team meetings and daily jobs.

- Problem Solving / Critical thinking: This skill is essential for designing an outcome to meet the projects complex issues. Its also a way of approaching tasks with a different open mindset that other people might not think of.

- Time Management:  Software developers can spend alot of time working by themselves. To be able to effectively manage your time and job allocation on specific tasks is essential for effective project management. It is also essential to meet the task time lines provided as to not go over the estimation provided on the project. 

- Accountability: Mistakes will always happen. This skill will mean in software development taking responsibility for mistakes made and learning from them, so they can be prevented from happening again. 

- Self Awareness: For developers to be self confident in what they know but be able to acknowledge what they do not understand. This enables team members to rely on one another and help each other for the common goal of finishing the project.

Hard Skills - Hard skills is a term used to define a specific skill set or technical abilities a individual may have. These skills and their importance in a software development workplace are:
- Programming Languages: Understanding and knowledge of how to use different programming languages for coding of applications. All application source code is written in languages like Python, Java, C++ etc, and using algorithms to produce the features required in the application. Proficiency in one or multiple of these languages is a much in demand hard skill to have.

- OOP Programming: Knowing the 4 fundamental pillars of OOP is essential for creating reusable and modular code in software applications.

- Web Development: Knowledge of both front and back end technologies of html, CSS & Javascript are essential skills when required to develop website or internet based development projects.

- Database Management: Knowing how to use both SQL and NoSql databases is an essential hard skill to have in any software development team when the application project requires the use of data and data storage. 

- Versions Control Systems: Having the skill of using VCS systems is a must when working on software projects in a team environment. This skill allows the project to always be updated and tracked along the life cycle of the project.

References:
Kugell, A., 2022. 10 Soft Skills Every Software Engineer Should Have. [Online] 
Available at: https://trio.dev/software-engineer-soft-skills/
Pratt, M. K., 2023. Definition Soft Skills. [Online] 
Available at: https://www.techtarget.com/searchcio/definition/soft-skills
alxafrica.com, 2023. Software Engineering: Hard vs. Soft Skills. [Online] 
Available at: https://www.alxafrica.com/software-engineering-hard-vs-soft-skills/
CareerScale, 2023. Top Hard Skills to Land a Job as a Software Developer. [Online] 
Available at: https://www.linkedin.com/pulse/top-hard-skills-land-job-software-developer-careerscale

~~~

### Question 12 Answers:
~~~
The roles you will find in a medium sized software development company are:

- Project Manager:
- This role has the responsibility of leading the whole team through each project SDLC. They are a good leader with effective communication skills, problem solving abilities and making sure all projects meet the development principles, timelines and within budgets. Their responsibilities also extend to negotiating and maintaining the expectations of stakeholders.

- Product Owner:
- This role is a key position between the stakeholders requirements and the developers. Their responsibilities are providing the product developments direction in organising the tasks and backlog priorities for achieving the projects objectives. They must have effective communication, team management and technical skills to steer the project towards a successful outcome.

- Full Stack Developers:
- These roles have very strong technical abilities to design, develop and maintain software applications. The term 'full stack' means their technical requirements can be used on both the front and back end of software development. They must be able to work well in a team, focus on the tasks assigned and meet all the development industry standards and requirements.

-QA Engineer:
- This Quality Assurance role is an effective part in each projects SDLC. The ensure the product development meets the highest quality standards. They are responsible for testing the product with a great attention to detail for requirement functionality, usability and performance. They will work closely with the developers and provide feedback on any defects or issues found.

References:
Kanoika, A., 2023. How to Structure Your Software Development Team. [Online] 
Available at: https://sumatosoft.com/blog/software-development-team-structure
Katariya, J., 2024. How to Build an Effective Software Development Team Structure. [Online] 
Available at: https://www.moontechnolabs.com/blog/software-development-team-structure/
~~~
















