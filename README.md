# Asset-Management-System-Database
Made up a Database to understand the functionality of Asset Management in an organization. 

Platforms Used: PHPMyAdmin
Language USed: MySQL

# Introduction

The theme of my project is an Asset Management System. Here, we're attempting to arrange and maintain a record of the various assets that are available to a corporation. A corporation may benefit from an ordered database thanks to an Asset Management System. It is essential to maintain track of which devices have been given to each employee when there are more workers present. As a result, this system can assist the Asset Tracking Manager in understanding the availability of assets within the organization, purchase information pertaining to an asset, the issuance of an asset to an employee, as well as information about the employee who issued the asset.

The Management System is a condensed form of how a business could maintain the specifics of its assets to keep track of them. Ten tables provide the data that could be utilized to characterize the company's resources and personnel. 

When a new employee is hired by the company, the Asset Tracking Manager must give them the necessary devices or equipment, such as a telephone and a hard drive, and must record these details in the Management System along with the issue date and the person's information. Similarly, if an existing employee requests additional devices based on project requirements, the Asset Tracking Manager must give them all necessary devices and may save information in the tracker system.

EMPLOYEE: Contains details of an Employee
DEPARTMENT: Contains details of the Department an Employee belongs to
HARDDRIVE: Each Employee working in the company has access to 1 Hard drive
TELEPHONE: Each employee has a Landline and can also have a Mobile phone along with a Landline
ASSET: Contains details regarding all the assets in the company. ASSET is a Supertype to 4 Subtype Tables – LAPTOPS, TABLETS, iPads, and HEADPHONES
ASSET_ASSIGNMENT: Contains details about an Asset that has been issued to an Employee

Each Employee has a 1:1 relationship with the asset Hard Drive. Every employee in the company has access to one and only one Hard Drive.
 
Each Employee has a 1:M relationship with the Asset Telecommunication. Every employee has 1 Landline available and can also have one company mobile phone along with the Landline.

Whenever an employee or group of employees is working on a project, they can be issued multiple assets from the total number of assets the company offers such as – Laptops, Tablets, Headphones, and iPads.
All the aforementioned assets will be tracked via the asset management system. The system will keep a record of information such as who was issued an asset, which asset has been issued, when was it issued, and when was it returned.

The System will also store the Employee data along with the departments that the employee belongs to. 
Below are the further details for the Asset Management System:
1.	The Data Dictionary – Table 1.1
2.	The Business Rules – Table 1.2
3.	Entity relationship model (ERM) components – Table 1.3

# Crow's Foot Notation

![image](https://github.com/user-attachments/assets/0642440f-f8bf-497b-a609-25f63817dd3b)

# Relationship in PHPmyadmin

![image](https://github.com/user-attachments/assets/05590d2c-79e8-401d-829d-f6135c100714)





