# Vision Document for Team Asklepios
## Section 1: Introduction
### 1.1 Purpose
We strive to put together a useable and aesthetically pleasing system that allows the NICU to input and store data and see that data at a glance.
### 1.2 Solution Overview
Using Google Cloud Platform, we will put together a web app that allows the user to input data and store it in a data base. We will then have a separate webpage that will display the information in an easy to digest fashion.
### 1.3 References
No References are needed.

## Section 2: User Description
### 2.1 User/Market Demographics
This product is designed specifically for the NICU at OU Medical. Dr. Ernst made it sound like they don't currently have a good program for this but there are other programs out there that would accomplish this. That being said, our product will be tailored specifically to our clients so ours will have an advantage.
### 2.2 User Personas
Our main goal is to ensure our program is easy to use. It will be primarily used by people without a background in tech and as such should be as user friendly as possible. With this in mind, we need to ensure that our program accurately stores and displays the information the user puts in. Ideally, this should increase efficiency in the NICU and make it easier to find necessary information.
### 2.3 User Enviornment
This program will ideally allow multiple users to access it at once. Normally, inputting the data should take no more than a few minutes and the data should be able to be digested in under a minute. This would need to be a secure server if implemented in the workplace as HIPAA protected data would be stored on the server. 
### 2.4 Key User Needs
This program needs to securely take data, store the data, and accurately display the data. Right now they need to manually look up each patient. Our solution would allow them to see any patient they need at a glance.
### 2.5 Alternatives and Competition
Right now competitors would also need to work with the NICU to build this tool. We know of at  least one other group also attempting to solve this problem. We believe the ease of use of our product will, in the end, put us ahead of them.
## Section 3: Stakeholders
|   |   |
|---|---|
|Name|Description|
|Requirements Manager|This stakeholder works with nurse and staff in NICU to translate their needs into requirements|
|Software Developer|This stakeholder design and develop the software that meets the requirements|

## Section 4: Product Overview
#### 4.1 Product Perspective



#### 4.2 Product Position Statement


This product is made for staff in NICU to help them know how their quality improvement projects are progressing. The Asklepios is a web app that helps the NICU nurses to improve their quality by comparing it to other NICU. Unlike the product, the other group is creating. Our product will be the best of all.  

#### 4.3 Summary of Capabilities

|   |   |
|---|---|
|Feature|Benefit|
|produce a graph|This feature will make the data easier to understand|
|Data Entry Form|This feature will let the user enter the data and added into our database|
|Auto Updating|This feature will update the data without you refresh the web page|

#### 4.4 Assumptions and Dependencies

* it assumes that the user has internet access.
* it assumes that the user can read graph and chart


#### 4.5 Cost and Pricing
There is no cost for using this product. Our main goal is to improve the quality of all NICU.

## Section 5: Product Features
### 5.1 - Graphs & Charts at a glance: Our product will feature quite a few graphs and charts so that NICU nurses and staff may view information about the current status of neonatal patients at a glance. We may expand this to be customizable, so that different staff may choose different preferences on which information they would like to view
### 5.2 - Data Entry Form: Our product will feature a separate webpage so that staff may enter data in to the program to be viewed. The information gathered may vary depending on what kind of data is being entered. 
### 5.3 - Auto Updating: The dashboard will automatically update whenever new data is entered. Of course, since our product is a web application, you may always use the refresh button in your browser to refresh as well

## Section 6: Exemplary use cases
Our product is designed to be used as an 'at a glance' overview of the neonatal unit at the HSC. The graphs and charts page is designed to be a sort of static display on monitors around the office, with data entry being done perhaps by a secretary for instance on another machine. Once data is entered, all monitors displaying our web app should automatically update.

## Section 7: Nonfunctional Requirements
### 7.1 Usability
  * UI ccomodation for color blindness either by offering differenet color pallettes or by overall using a color-blind safe pallete.
  * UI will allow health care workers to quickly enter data.  
  * There should be accomodations for the most common disabilities recorded in health care workers.
### 7.2 Reliability
  * Less than 1% error of margin on data entry.
  * Allow for data entry after server failure/down time.
  * Data being outputted should be verified by system.
### 7.3 Performance
  * With proper connection speed webpage, with no data rendering,loading time avearge should be less than 1 second. 
  * All data/graphs/tables rendering should be on average less than 5 seconds. 
  * The overall web application should be optimized to handle hundreds of users simulataneously.
### 7.4 Supportability
  * The most common down time for each NCIU should be used as a time to release updates and server maintence
  * The webapp should be supported for the next 50 years even if having to port to another language.
  * The webapp should also be designed for reuseability and facilitate the implimentation of new features. 
### 7.5 Other Requirements
  * There should be a techinical support desk to aid with any user questions.
  * Technical support should be available 24/7.
  * An on site specialist should be available to any NCIU's that would feel an onsite specialist should be required.
#### 7.5.1 Applicable Standards
This webapp will adhere to the standards pre-disclosed by the following organizations:
I-EEE, ISO, IEC, ITU, ANSI, HIPAA, and NHS standards and guidelines.

#### 7.5.2 System Requirements
The webapp will be built and designed for cloud computing therefore th system requirements will be those of the major cloud computing engines such as GCP and AWS. 

#### 7.5.3 Licensing, Security, and Installation
* The NCIU Dashboard webapp will be aimed to have no dependencies on other software or databases and built from scratch therefore, not requiring any licensing.
* The webapp will be highly secured and have different levels of access within itself
* Since it will be deployed on a cloud computing engine we will aim for no installation to be required

## Section 8: Documentation Requirements
### 8.1 User Manual
The webapp will ship with a very short electronic user manual. The user manual will quickly walk the users how to access all pages on the base level of the system.
### 8.2 Online Help
There will be a QA section where users will have access to frequently asked questions and their answers. If this section does not answer their question or issue then there will be an online chat available where they will be connected to real people providing technical support.
### 8.3 Installation Guides, Configuration, “Read Me” File
The installation guide will simply be steps for the system administrator to reproduce in order to deploy the dashboard. Configuration will not be allowed since we will tailor the software to each NCIU. There will be a basic "Read Me" file that includes the deployment steps as well as process to follow in instances of system issues or failures.

## Section 9: Glossary

ACRONYMS
* UI - User Interface 
* I-EEE - Institute of Electrical and Electronics Engineers
* ISO - International Organization for Standardization
* IEC - The International Electrotechnical Commission
* ITU - International Telecommunication Union
* ANSI - American National Standards Institute
* HIPAA - Health Insurance Portability and Accountability Act
* NHS - National Health Services
