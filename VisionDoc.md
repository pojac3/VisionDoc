# Vision Document for Team Asklepios
## Section 1: Introduction
## Section 2: User description
## Section 3: Stakeholders
## Section 4: Product Overview
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
