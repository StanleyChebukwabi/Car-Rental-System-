# Car-Rental-System-(BSCIT-01-0088/2023)
Here’s an outline of our Car Rental System:
 ## System Requirements:
##### -The system will support renting different types of automobiles (cars, trucks, SUVs, vans, motorcycles).
##### -Each vehicle will have a unique barcode, parking stall number, and other details.
##### -Members can search the vehicle inventory, reserve available vehicles, and add rental insurance or additional services.
##### -Late fees will be collected for vehicles returned after the due date.
##### -Notifications will be sent for reservations, due dates, and overdue returns.
## Use Case Diagram:
We have four main actors:
##### -Receptionist: Responsible for adding/modifying vehicles, reserving vehicles, and managing workers.
##### -Member: Can search the catalogue, reserve, pick up, and return vehicles.
##### -Worker: Manages vehicle maintenance and logistics.
##### -System: Handles notifications and maintains logs.
Main Classes:
##### -Car Rental System: The central part of the organization.
##### -Car Rental Location: Represents different rental locations.
##### -Car: Represents a specific vehicle.
##### -Customer: Represents a member/customer.
##### -Rental: Represents a rental transaction.
## Class Diagram:
##### -The class diagram will show the relationships between these classes, including inheritance and associations.
 ## Activity Diagrams:
##### -We can create activity diagrams to illustrate the flow of processes like vehicle reservation, pick-up, and return.
 ## Test Cases:
We’ll thoroughly validate each method’s functionality using test cases.
Examples: Test vehicle reservation, late fee calculation, member cancellation, etc.
## Source Code, Test File, and Documentation:
We’ll organize our code into packages
Create JUnit test classes for each method.
