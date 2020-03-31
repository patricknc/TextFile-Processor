# Answers to Questions
1. # How long time did you end up spending on this coding test?    
I spent around 12 hours on this coding test.

2.	# Explain why you chose the code structure(s) you used in your solution.   

**Why I choose ASP.NET Core:**  
ASP.NET Core is the open-source version of ASP.NET, and can be used to create robust web applications.  It can run on macOS, Linux, and Windows. It incorporates ‘Client-side development, hence integrates seamlessly with popular client-side frameworks and libraries, including Blazor, Angular, React, and Bootstrap.  
Below are the advantages of using ASP.NET Core to develop web application:
1.	Improved collaboration and cross-platform support. A unified story for building web UI and web APIs.
2.	Architected for testability.
3.	Razor Pages makes coding page-focused scenarios easier and more productive.
4.	Mature framework and widely used programming languages. Blazor lets you use C# in the browser alongside JavaScript. Share server-side and client-side app logic all written with .NET.
5.	Ability to develop and run on Windows, macOS, and Linux.
6.	ASP.NET Core is an open-source and community-focused web framework.
7.	Integration of modern, client-side frameworks and development workflows.
8.	Support for hosting Remote Procedure Call (RPC) services using gRPC.
9.	A cloud-ready, environment-based configuration system.
10.	Built-in dependency injection.
11.	A lightweight, high-performance, and supports modular HTTP request.
12.	Hosting – It has the ability to host on IIS, Kestrel, Apache, HHTP.sys, Docker, Self-Hosting
13.	Tooling that simplifies modern web development.

**ASP.NET Core MVC provides features to build web APIs and web apps:**
The Model-View-Controller (MVC) architectural pattern separates an app into three main components: **M**odel, **V**iew, and **C**ontroller. The MVC pattern helps you create apps that are more testable and easier to update than traditional monolithic apps. In MVC, each route request goes to a **Controller** on the server. The Controller interacts with the **Model** (the data) and generates a **View** (the HTML/CSS/JavaScript client-side). This has several advantages. It creates a nice separation of concern between the client, server, and the different components. As a result, more developers can work on the same project without conflicts. It allows to reuse components.

The MVC pattern helps you create apps that separate the different aspects of the app (input logic, business logic, and UI logic), while providing a loose coupling between these elements. The pattern specifies where each kind of logic should be located in the app. The UI logic belongs in the view. Input logic belongs in the controller. Business logic belongs in the model. This separation helps you manage complexity when you build an app, because it enables you to work on one aspect of the implementation at a time without impacting the code of another. For example, you can work on the view code without depending on the business logic code.

MVC-based apps contain:  
*	**Models:** Set of classes that represent the data of the app. The model classes use validation logic to enforce business rules for that data. Typically, model objects retrieve and store model state in a database. Updated data is written to a database.

*	**Views:** Contains the display logic to present the Model data provided to it by the Controller. Views are the components that display the app's user interface (UI). Generally, this UI displays the model data.

*	**Controllers:** Handles the http request, work with the model, and select a view to render that model. Classes that handle browser requests. They retrieve model data and call view templates that return a response. 

In an MVC app, the view only displays information; the controller handles and responds to user input and interaction. For example, the controller handles route data and query-string values, and passes these values to the model. The model might use these values to query the database

**I used LINQ to implement foo and bar**   
I read all text words from the file and store it in a string array variable to enable me easily query it using Linq. To get the most used word can be achieved in several ways. I found using LINQ in .Net Framework faster and easier since I have already store all the words in a collection. Using Linq, I can easily query and manipulate each string in the array.

3.	# What would you add to your solution if you had more time?  
**This question is especially important if you did not spend much time on the coding test - use this as an opportunity to explain what your solution is missing.**  
Enough time was provided for the coding test, and I believe nothing is missing in the solution.

4.	# What did you think of this recruitment test?   
I think that this recruitment test gives the candidates an opportunity to demonstrate their coding skills. It will test the candidate’s problem-solving ability. It will enable the recruiter understand how a candidate think through a problem. It tests the capability of candidates in technical decision making and the reasons behind taking such decisions. For instance, why the candidates choose a particular technology, and why they design things the way they do. Generally, I can say that the recruitment test is fun but a realistic work sample project.



