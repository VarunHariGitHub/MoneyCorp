Tech Solution – This exercise is implemented using selenium - C# - NUnit Test Framework with Page Object Model design
Selenium Overview:
Selenium is an open-source, web automation test suite that supports multiple browsers and multiple operating systems. It allows testers to use multiple programming languages such as Java, C#, Python, .Net, Ruby, PHP, and Perl for coding automated tests.
C# Overview:
C# is an object-oriented programming language derived from C++ and Java. C# allows developers to build applications using Visual Studio on .Net platform. The following are the key features:
1.	It is an Object-Oriented programming language
2.	It supports the development of console, windows and web-based applications
3.	It provides features such as Encapsulation, Inheritance, and Polymorphism.
NUnit # Overview:
Integration of selenium with NUnit framework allows a tester to differentiate between various test classes. NUnit also allows testers to use annotations such as SetUp, Test, and TearDown to perform actions before and after running the test. NUnit framework can be integrated with Selenium by creating a NUnit test class and running the test class using NUnit framework.


MoneyCorp Test assignment architecture
	Base Class – This class includes WebDriver initialization, Launch Chrome, Extent Report Creation and Quit Browser features.

	DriverExtensions Class – This class includes the common driver utilities example Screenshot implementation.

	WebElementExtensions Class – This class includes all the common methods to be used in page classes example “WaitAndClick”

	MoneyCorpObjectRepository Class – This class includes all the locator information like XPath, CSSSelector, ID etc

	MoneyCorpHomePage Class – This class incudes all attributes and functions for Home Page.

	MoneyCorpDetailPage Class – This class incudes all attributes and functions for Detail Page.

	MoneyCorpInternationalPaymentPage Class – This class incudes all attributes and functions for International Payment page.

	Scenarios Class – This class includes the main Tests being executed and also capturing the results.

	MoneyCorpTestData Class – This class includes all the test data definition being presented in tests.

	ExtentReportsHelper Class – This class includes the ExtentReport utility


Refer steps followed to complete the assignment:
Pre-condition: Visual Studio (IDE) that is used by developers to build applications across multiple platforms such as Windows, Android, iOS and Cloud-based applications, With NUnit testing framework configured, you can now create NUnit Test Project in Visual Studio for C#. Below are the steps to setup your Selenium and C# in Visual Studio.
	Step 1: Create a new NUnit test Project in C# by navigating to New → Project → NUnit Test Project (.Net Core).
	Step 2: The newly created project will have the basic test ready with NUnit annotations being used in the source code.
	Step 3: Navigate to Tools → NuGet Package Manager → Manager NuGet Packages for Solution and search for ‘Selenium’.
	Step 4:  Install Selenium WebDriver interface from NuGet Package
	Step 5:  Install Selenium.WebDriver.ChromeDriver from NuGet Package for executing scripts on chrome browser.
	Step 6: Install ExtentReports from NuGet Package for creation of extent reporting framework
	Step 7: After all above successful installation, you can start automation testing using NUnit, a Selenium C# framework for test automation

Instructions for setting up an environment and execution details
Clone from following GITHUB repository: 
	Initiate Visual Studio IDE and then follow steps to clone the project from git repository URL location:
	File menu option  click “Clone Repository” option
	Provide the “Repository Location” of the Github Repository and provide the local path details.
	Click Clone button
	As expected, the Project should open “MoneyCorp”
	Add all the dependencies and Build the Project
	You are good to start execution of test scenarios.


Benefits of Framework
	Reusability of code 
	Easy to maintain the code 
	Eliminate duplicate code 
	Data Driven Test 
	Optimized code 
	Simplifying the visualization and model of the web page under test


Further Enhancements that can be incorporated
	BDD Framework integration to write test in Gherkin language. 
	SQL DB and Excel Test Data connectivity utilities
	Email generation utilities in case of failed cases
	CI/CD Integrations
	Headless browser executions
	Parallel test executions
	Docker/Selenium grid integrations
	Website’s device(mobile) view test executions using ChromeOptions
	Handling Browser Authentications
	Creating utilities to execute tests on multiple browsers
	Handling Actions class concepts instead of normal operation.
