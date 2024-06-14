# T1A1 Workbook Assignment

### Question 1 Answers: 
~~~
The following markup languages are used in web development:
 - HTML : HyperText Markup Language is used to create website pages. HTML defines the layout, structure and content displayed by defining different elements or tags in specific locations to render the appearence of text, images , multimedia or links to other files to display in a web browser. A element is placed by starting with a tag name (case sensitive) inside of a opening pair of "<" *name* ">", then the element content to display (not in all cases), and ended with the same tag name closed by a pair of "</" *name* ">". Some important must have element tags are `<html></html>, <head></head>, <title></title>, <body></body>` . Others are `<header>, <footer>, <p>, <img>, <article>, <section>, <div>, <ul>, <ol>, <li>.`

 - XML : eXtensible Markup Language is used to store and transfer data.It is different to HTML in that the document creator can define the tags and structure. XML tags are customised for the purposes of the document being sent, but are enclosed in the same opening and closing angle brackets. The XML language is a standardised format so all different types of applications can interpret the same data.

 - XHTML : eXtensible HyperText Markup Language is a combination between both HTML & XML. It combines the presentation functions of HTML but with the strict standardised rules of XML. The XHTML syntax is very strict and each page needs to include one of 3 types of DTD (Document Type Definition) declarations. These XHTML element tags are mandatory in a document:  <!DOCTYPE> , `<html></html>`, a "xmlns" attribute must be in the `<html>` tag, `<head></head>, <title></title>, <body></body>`. The XHTML elements must also be in lowercase, properly nested and always closed.
~~~
[Ref1](https://developer.mozilla.org/en-US/) , [Ref2](https://wpamelia.com/markup-languages/) , [Ref3](https://www.w3schools.com/)

### Questions 2 Answers:
~~~ 
- packets : A packet is a unit of data that is gouped togther and sent over a network or the internet. Each packet has the information it needs to get to its destination like receivers IP address, senders IP address, how many packets the message or file is broken into and the number of each packet.

- IP addresses (IPv4 and IPv6)  : IP addresses are used to identify the computers / devices of both sending and receiving over a network or the internet. IPv4 IP addresses use a 32bit format and broken into 4 parts, example: 172.0.68.109. IPv6 uses 128 bit format, also include letters and use colons to separate segments, example: fe80::26f0:1ffe:b96c:93b9%12.

- Routers and Routing :  A router is a device that connects computers / devices over networks and the internet. It determines and sends the data on the best possible path by analysing the network metrics.
  - Routing is the process of selecting the best possible path for data to flow over a network or the internet. This helps reducing network failure by controlling the flow and congestion on a network.

- Domains and DNS : A domain is the host name or address of a website that users type in their browser url area to visit that website.
  - DNS is short for Domain Name System which essentially translates website domain names into IP addresses. It is a global network of servers that acts like a giant directory to convert domain names into IP addresses & vice versa.

- Explain how each technology has contributed to the development of the internet  : Each technology has vastly increased the development of the internet. As computers, mobile phones and all other types of devices have better technology and applications with the ability to access the internet, all will be assigned IP addresses, sending / receiving increased amount of data packets , which results in the need for better routers, so devices can access more & more domain names which results in the need for better DNS servers. 
 ~~~
[Ref1](https://www.techtarget.com/) , [Ref2](https://aws.amazon.com/)

 ### Questions 3 Answers (50 - 150 words for each technology):
 ~~~
- TCP : TCP stands for Transmission Control Protocol and is a standard protocol for ensuring successful communication deliveries between devices over a network or the internet. The TCP resides in the transport OSI layer and its role in the communications between devices is to ensure the establishment of a connection and that all data has been delivered correctly. It does this by working in collaboration with Internet Protocol rules.
  TCP delivery has continually been developing between client & server since its creation back in the early 1970's. It was first designed for the US department of defense and then in the 1980's helped with the development of the internet to be a world wide network. One way TCP works between Server and client devices by a web server setting up a connection when asked by the HTTP layer, then the TCP stack will divide the file into numbered packets to be delivered and send them to the IP layer for delivery. 
  The TCP layer in the client device will wait and confirm all numbered packets have been received correctly, then assembles all the packets back into the file and send it to the application required.

- HTTP and HTTPS  : Hypertext Transfer Protocol is a set of communication rules between client & server. This protocol is the communications foundation of the internet for browsers and servers, but data transmitted is unencrypted. So in the 1990's a more secure protocol of http was developed called https = Hypertext Transfer Protocol Secure. The http is an application layer protocol that interprets different types of requests and responses between client & server. When wanting to view data from a website the client http protocol will send a series of "GET" requests to the server to ask for all the information it needs to load the webpage. To send information to the server (like a form), the client http protocol will send a "PUT" request.
  The server will also send back coded responses to these requests, some examples are: 400 = Bad Request, 404 = Resource Not Found.
  Https works in the same way but adds an extra layer of security by combining the requests & responses with SSL & TLS certificates. These are shared by the client and server before exchanging data to verify a trusted connection.

- Web Browsers (requests, rendering and developer tools)  : Web Browsers are an application software for accessing and viewing websites over the internet. Using the http / https protocols between a client and server to receive the information requested , the browser will then compile the web documents to render them in html which is used to design web pages and display to the user the web sites content. Web browser features can include: a home page, URL address bar, navigation buttons, bookmark options, history of visited websites and refresh button.
Current web browsers will also include developer tools. These are tools that allow users to inspect & debug the rendered web sites html , css and javascript properties. Developers will use these to help in buiding better websites, diagnosing any problems and measuring its performance all in realtime as they view / build the web page.
 ~~~
 [Ref1](https://www.techtarget.com/searchnetworking/definition/TCP) , [Ref2](https://www.techopedia.com/definition/5773/transmission-control-protocol-tcpv) , [Ref3](https://aws.amazon.com/compare/the-difference-between-https-and-http/) , [Ref4](https://www.okta.com/au/identity-101/http-vs-https/) , [Ref5](https://www.geeksforgeeks.org/web-browser/) , [Ref5](https://www.techopedia.com/definition/288/web-browser) , [Ref6](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools)

 ### Question 4 Answers :
 ~~~
 - Interpreters / Compilers Features & Differences:
    - Interpreters: 
        - An interpreter executes a high-level language line by line while the program is running.
        - Better for debugging as runs each line sequentially until a error occurs.
        - Memory required is less than a compiler.
        - If interupted at any point, must restart from the begining.
        - Relatively flexible.

    - Compilers: 
        - A compiler executes a high-level language into a lower-level language, like machine code, in whole for the entire program.
        - Compilers will operate quicker than interpreters.
        - After compiling the entire code it returns all errors. This makes it harder to locate and fix them.
        - Larger in size compared to interpreters.
        - Not flexible.
 ~~~
[Ref1](https://www.linkedin.com/pulse/compilers-vs-interpreters-how-work-monzer-omer) , [Ref2](https://www.thecomputingteacher.com/csc/index.php/programming/206-compiler-and-interpreter)

### Question 5 Answers :
~~~
Compare 2 Programming Languages.
- Benefits.
  - Python:
    - mostly used for backend development.
    - easy to learn and the simple syntax makes faster to write which increases productivity.
    - well known for its ready to use modules and libraries.
    - multiple varieties of numeric data types.
    - open source with a large world wide communtiy.

  - Javascript:
    - used for user functionality in web development.
    - many application uses in browser, desktop, mobile, server.
    - known for its speed to execute on the clients side, resulting in less reliance on server side resources.
    - a multi-threading feature makes it highly scalable for application growth.
    - continually updated for improvements.

- Drawbacks.
  - Python:
    - slower to execute code, as does it on a line by line basis.
    - memory usage is greater.
    - less scalable as only works on a one-threading feature.
    - no mobile phone natively runs python.
  
  - Javascript:
    - syntax uses a variety of symbols making it harder to read / learn.
    - not many in built modules.
    - limited set of numeric data types.
    - debugging errors are more complicated as may only appear at runtime.
~~~
[Ref1](https://www.linkedin.com/pulse/python-vs-javascript-in-depth-comparison-hyperlinkinfosystem-xcmkf) , [Ref2](https://thecodest.co/blog/pros-and-cons-of-python/) , [Ref3](https://ellow.io/advantages-and-disadvantages-of-javascript/)

### Question 6 Answers :
~~~

Hi Alex,
  Thankyou for reaching out via email and yes we can definitely provide the website services the SAM is wanting to encourage people to visit. I will
briefly explain who we are , what we do and our thoughts on how we can provide a dynamic website for the SAM.
  We are 'Awesome Websites Australia' and we have been building, evaluating and supporting company & community websites for over 15 years. We are based in
Sydney but have many clients all around the country and overseas. We have all the technologies and tools required to facilitate this which allows us to be very cost effective, provide a full stack service from begining to end so you can put your mind at rest that everything is covered. These include:
  a.  Our customer service team will liase with you directly and in person to specifically gather the SAM requirements, information needed and images to be used.
  b.  Our design team uses their own wireframing program, colour palettes matching, understanding of design standards to facilitate people with disabilities.
  c.  The development team will build the website in house using the best practice standards for html, css and javascript.
  d.  We can do all the legal registrations needed, deploy live to the internet and update whenever required. All our teams are trained and will abide by the australian regulations for privacy & security of company and personal information.  
  Please visit our website to view the types of clients and websites we have developed: www.awesomewebsitesaustralia.com.au/

  Our staff have briefly put together some ideas for the SAM website, which will give you an idea of their expertise :
  1.  Home Page - the first landing page to show who the SAM is with dynamic images of your best pieces from around the world.
                - this will include a navigation bar with links to other pages such as : Featured Items , From Around The World , Our Location , Contact Us.
  2.  Featured Items Page - we think this page will be dedicated to the museums featured items or most popular pieces. This page is designed to draw the publics interest for those special famous items to see and can be continually be updated as newer items come in or older items move out of interest.
  3.  From Around The World Page - this page can have a dynamic map of the world where users can be involved and interact with a 'Select A Country' map, which then opens a page displaying the Items the museum has from this country with information explaining the history, artist etc about each piece.
  4.  Our Location Page - this page will have the SAM location address with a Google maps area & location pin displayed. Differnt modes of transport to visit can also be shown for the public to know how easy it is to find the SAM. EG: If Train - then disembark at central station & catch bus T102 for 4 stops.
  5.  Contact Us Page - this will have all the SAM's contact details and social media links.

Any other features you think would be required like ticket sales, donations or news letter registration and delivery can be discussed in the future.

I hope this explains and meets your expectations for the SAM website, please feel free to contact me further and I look forward in moving forward together.
Kind Regards,
Darren Small.
~~~

### Question 7 Answers :
~~~


~~~

### Question 8 Answers :
~~~
Action Plan For Networking Events Or Workshops:






