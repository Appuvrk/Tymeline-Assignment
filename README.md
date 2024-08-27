1. Set Up the Environment
Before writing the code, make sure you have the following:

Java installed on your machine.
Maven for dependency management.
An IDE like Eclipse or IntelliJ IDEA.
Selenium WebDriver dependency in your pom.xml file.
ChromeDriver or any other WebDriver depending on the browser you want to use.
2. Add Dependencies in pom.xml
For a Maven project, add the following dependencies to your pom.xml:

xml
Copy code
<dependencies>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.10.0</version> <!-- or the latest version -->
    </dependency>
    <dependency>
        <groupId>org.testng</groupId>
        <artifactId>testng</artifactId>
        <version>7.7.1</version>
        <scope>test</scope>
    </dependency>
</dependencies>
3. Write the Test Script
Here is a basic test script in Java using Selenium and TestNG:
4. Run the Test
Import the project into your IDE (Eclipse, IntelliJ IDEA).
Run the test using TestNG.
Explanation of the Code:
@BeforeClass: Sets up the environment before running the test, initializing the WebDriver.
testGoogleSearch: The actual test function that:
Opens Google.
Enters the search query.
Submits the search.
Verifies if the search results contain relevant keywords.
@AfterClass: Cleans up by closing the browser after the test is complete.


Note : I apologize for any inconvenience this may have caused. I've completed an assignment using Selenium with Java, which I'm currently learning. Please take this into consideration.
Link : https://drive.google.com/file/d/1wy_TVnbTBWMYj0lDVS92dHMPHW1tg7Gr/view?usp=drive_link
