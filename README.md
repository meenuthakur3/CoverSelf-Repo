CoverSelfAssignment
│── src/main/java          # Main Java source files  
│── src/test/java          # Test cases  
│── src/test/resources     # Contains testng.xml  
│── pom.xml                # Maven dependencies  
│── README.md              # Project documentation  
│── .gitignore             # Files to ignore in Git  


** Technologies Used**
Java 11/17
Selenium WebDriver
TestNG
Maven
** Setup Instructions**
1Clone the Repository
sh
Copy
Edit
git clone https://github.com/your-github-username/your-repo-name.git

OR
Download the ZIP and extract it.

Open the project in IntelliJ IDEA / Eclipse.

**Run Tests Using testng.xml**
Since the testng.xml file is inside src/test/resources, use:

Right-click src/test/resources/testng.xml and select Run.
**From Terminal / Command Line**
Run the following Maven command:


mvn test -DsuiteXmlFile=src/test/resources/testng.xml
