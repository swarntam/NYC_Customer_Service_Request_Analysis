### DESCRIPTION

Background of Problem Statement :

NYC 311's mission is to provide the public with quick and easy access to all New York City government services and information while offering the best customer service. Each day, NYC311 receives thousands of requests related to several hundred types of non-emergency services, including noise complaints, plumbing issues, and illegally parked cars. These requests are received by NYC311 and forwarded to the relevant agencies such as the police, buildings, or transportation. The agency responds to the request, addresses it, and then closes it.

### Problem Objective :

Perform a service request data analysis of New York City 311 calls. You will focus on the data wrangling techniques to understand the pattern in the data and also visualize the major complaint types.
Domain: Customer Service

#### Analysis Tasks to be performed:

1. Import a 311 NYC service request.
2. Read or convert the columns ‘Created Date’ and Closed Date’ to datetime datatype and create a new column ‘Request_Closing_Time’ as the time elapsed between request   creation and request closing. (Hint: Explore the package/module datetime)
3. Provide major insights/patterns that you can offer in a visual format (graphs or tables); at least 4 major conclusions that you can come up with after generic data   mining.
4. Order the complaint types based on the average ‘Request_Closing_Time’, grouping them for different locations.
5. Perform a statistical test for the following:

    Whether the average response time across complaint types is similar or not (overall)<br>
    Are the type of complaint or service requested and location related?
    
### Dataset Description :

Field	Description
Unique Key	(Plain text) - Unique identifier for the complaints <br>
Created Date	(Date and Time) - The date and time on which the complaint is raised <br>
Closed Date	(Date and Time)  - The date and time on which the complaint is closed <br>
Agency	(Plain text) - Agency code <br>
Agency Name	(Plain text) - Name of the agency <br>
Complaint Type	(Plain text) - Type of the complaint <br>
Descriptor	(Plain text) - Complaint type label (Heating - Heat, Traffic Signal Condition - Controller) <br>
Location Type	(Plain text) - Type of the location (Residential, Restaurant, Bakery, etc) <br>
Incident Zip	(Plain text) - Zip code for the location <br>
Incident Address	(Plain text) - Address of the location <br>
Street Name	(Plain text) - Name of the street <br>
Cross Street 1	(Plain text) - Detail of cross street <br>
Cross Street 2	(Plain text) - Detail of another cross street <br>
Intersection Street 1	(Plain text) - Detail of intersection street if any <br>
Intersection Street 2	(Plain text) - Detail of another intersection street if any <br>
Address Type	(Plain text) - Categorical (Address or Intersection) <br>
City	(Plain text) - City for the location <br>
Landmark	(Plain text) - Empty field <br>
Facility Type	(Plain text) - N/A <br>
Status	(Plain text) - Categorical (Closed or Pending) <br>
Due Date	(Date and Time) - Date and time for the pending complaints <br>
Resolution Action Updated Date	(Date and Time) - Date and time when the resolution was provided <br>
Community Board	(Plain text) - Categorical field (specifies the community board with its code) <br>
Borough	(Plain text) - Categorical field (specifies the community board) <br>
X Coordinate	(State Plane) (Number) <br>
Y Coordinate	(State Plane) (Number) <br>
Park Facility Name	(Plain text) - Unspecified <br>
Park Borough	(Plain text) - Categorical (Unspecified, Queens, Brooklyn etc) <br>
School Name	(Plain text) - Unspecified <br>
School Number	(Plain text)  - Unspecified <br>
School Region	(Plain text)  - Unspecified <br>
School Code	(Plain text)  - Unspecified <br>
School Phone Number	(Plain text)  - Unspecified <br>
School Address	(Plain text)  - Unspecified <br>
School City	(Plain text)  - Unspecified <br>
School State	(Plain text)  - Unspecified <br>
School Zip	(Plain text)  - Unspecified <br>
School Not Found	(Plain text)  - Empty Field <br>
School or Citywide Complaint	(Plain text)  - Empty Field <br>
Vehicle Type	(Plain text)  - Empty Field <br>
Taxi Company Borough	(Plain text)  - Empty Field <br>
Taxi Pick Up Location	(Plain text)  - Empty Field <br>
Bridge Highway Name	(Plain text)  - Empty Field <br>
Bridge Highway Direction	(Plain text)  - Empty Field <br>
Road Ramp	(Plain text)  - Empty Field <br>
Bridge Highway Segment	(Plain text)  - Empty Field <br>
Garage Lot Name	(Plain text)  - Empty Field <br>
 
Ferry Direction	(Plain text)  - Empty Field <br>
Ferry Terminal Name	(Plain text)  - Empty Field <br>
Latitude	(Number) - Latitude of the location <br>
Longitude	(Number) - Longitude of the location <br>
Location	(Location) - Coordinates (Latitude, Longitude) <br>

 
