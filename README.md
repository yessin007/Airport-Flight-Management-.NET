<h1>Airport-Flight Management System</h1>

<p id="description">Welcome to the Airport Management System project, a robust solution designed to facilitate the efficient operation of an airport. This comprehensive system simplifies the management of planes, flights, passengers, staff, and travelers. With well-defined entities and relationships, it ensures smooth and organized airport operations. </p>

<h1>Key Classes and Relationships</h1>

<h2>Plane Entity :</h2>

<p id="description">The Plane entity represents aircraft within the airport's fleet. Each plane is associated with:

 -Flight: A relationship linking the plane to a specific flight, allowing for precise tracking and assignment.

 -PlaneType: An enumeration (enum) that defines the type or category of the aircraft, such as "Commercial," "Cargo," or "Private."</p>

 <h2>Flight Entity :</h2>
 
<p id="description">The Flight entity manages the details of flights scheduled at the airport. It includes:

 -Passenger: A relationship connecting passengers to their respective flights, facilitating passenger management.</p>

  <h2>Passenger Entity :</h2>
  <p id="description">The Passenger entity serves as the parent class for both staff and travelers, offering a unified approach to managing individuals associated with flights.

 -Staff: Derived from Passenger, this subclass represents airport staff members, such as crew and ground personnel.

 -Traveler: Also derived from Passenger, this subclass represents passengers who are not part of the staff.</p>

 <p align="center"><img src="https://i.postimg.cc/NMsWXfC0/image-2023-09-16-161704034.png" alt="project-image"></p>
