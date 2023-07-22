# Conceptual-database-design
The challenge presented by DIO, consist in understanding the narrative and needs of the client, and turn these in a concept database design

===========================================================================================================================================
Narrative:
Service order execution control and management system in a mechanical workshop
Customers take vehicles to the repair shop to be maintained or undergo periodic inspections
Each vehicle is assigned to a team of mechanics who identify the services to be performed and fill in an OS with delivery data.
From the SO, the value of each service is calculated, consulting a labor reference table
The value of each piece will also compose the OSO client authorizes the execution of the services
The same team evaluates and executes the services
Mechanics have code, name, address and specialty
Each OS has: number, date of issue, value, status and date for completion of work

==========================================================================================================================================

Creating Entities:
Vehicle: To divide vehicle types
Customer: To save customer contact, and generate order request
Request: type of service, problem description, date
Analysis: Delivery Date, analysis description, budget
Mechanic: Name, Address, Specialty
Labor: labor hour pricing
Inventory: part pricing
Service Order: Os status
