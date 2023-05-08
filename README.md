Download Link: https://assignmentchef.com/product/solved-prog2110-assignment-2-eer-diagram-used-car-dealership
<br>
<h2><span lang="EN-CA" style="font-size: 11.0pt; line-height: 107%; font-family: 'Calibri',sans-serif; color: black;">Wally Los Gatos, owner of Wally’s Wonderful World of Wheels, has hired you as a consultant todesign a database management system for his chain of stores that sell used vehicles. Wally requires this system to track details about inventory, employees, sales and suppliers. </span></h2>

<h2><span lang="EN-CA" style="font-size: 11.0pt; line-height: 107%; font-family: 'Calibri',sans-serif; color: black;">Wally’s daughter, Wanda, has recently started to apply her college courses in web design to help her father’s business. The company’s website allows customers to review details on vehicles for sale, but more importantly, allows them to fill out a ‘request form’. This new form will add new information to the database.</span></h2>

Demonstrate the use of an Enhanced Entity Relationship (EER) diagram

Demonstrate the modelling of relations and use of normalization within a diagram

RequirementsBased on the following information, draw an EER diagram and a diagram of the set of relations in 3rd normal form. Please indicate any assumptions that you have made in your diagrams!

After an initial meeting with Wally, you have developed a list of business rules and specification to begin the design of an the EER Model. Once the EER model is completed, ‘translate’ that model into a relation diagram:

<ul>

 <li>Customers place orders through a dealership. Wally has three dealership locations (Cambridge, Kitchener and London), and may add more in the future</li>

 <li>Wally would like to track the following about customers:Name, Address, City, Province, Postal Code, Telephone, Date of Birth, Email, Social Insurance Number (SIN)</li>

 <li>A customer may place many orders</li>

 <li>A customer does not always have to order through the same dealer all the time</li>

 <li>Customers often require financing/loans, and thus may need to have an account</li>

 <li>Customers may have one or more accounts, although they may also have no accounts</li>

 <li>The following information needs to be recorded about accounts:Balance, Last Payment Date, Last Payment Amount, Interest, Term</li>

 <li>A dealership may have many customers</li>

 <li>Orders are composed of one or more vehicles from inventory</li>

 <li>The following information about each order needs to be recorded:Order Date, Final Sale Price, Credit Authorization Status</li>

 <li>A vehicle is a unique item and can only be sold by one dealership (although it has happened that Wally has bought and resold the same vehicle at a different dealership)</li>

 <li>We wish to record the following about each vehicle:Vehicle Identification Number (VIN), Make, Model, Year, Colour, Km’s, Photo, Purchase Price, Sticker Price</li>

 <li>Wally obtains vehicles from a range of suppliers, including auctions, bank foreclosures, other dealerships and private sellers</li>

 <li>Every time a vehicle is purchased by Wally, his company pays a purchase price, and sells the vehicle at a ‘sticker price’</li>

 <li>The sticker price is always 35% more than the purchase price (this is how Wally makes profit!)</li>

 <li>Sales team members might agree to sell the vehicle for less than the sticker price, thus the order should track the final sale price</li>

 <li>Wally employs fifty-six employees</li>

 <li>He would like to track the following information about employees:Name, Address (Street, City, Province, Postal Code), Telephone, Date of Hire, Title, Salary, Age, Manager, and attributes that vary depending on the employee’s role</li>

 <li>If the employee’s role is that of a mechanic, we should track their Certification Number and Years of Experience</li>

 <li>If the employee’s role is that of a salesperson, we should track their commission and total Vehicles Sold</li>

 <li>If the employee’s role is that of a manager, we should track which employees they manage</li>

 <li>Some employees join Wally’s business as general staff, and have no special attributes to track</li>

 <li>Each employee works in one and only one dealership</li>

 <li>Each employee may have one or more dependents. We wish to record the name of the dependent as well as the age and relationship</li>

</ul>

<ul>

 <li>Demonstrate the use of an Enhanced Entity Relationship (EER) diagram</li>

 <li>Demonstrate the modelling of relations and use of normalization within a diagram</li>

</ul>

RequirementsBased on the following information, draw an EER diagram and a diagram of the set of relations in 3rd normal form. Please indicate any assumptions that you have made in your diagrams!

After an initial meeting with Wally, you have developed a list of business rules and specification to begin the design of an the EER Model. Once the EER model is completed, ‘translate’ that model into a relation diagram:

<ul>

 <li>Customers place orders through a dealership. Wally has three dealership locations (Cambridge, Kitchener and London), and may add more in the future</li>

 <li>Wally would like to track the following about customers:Name, Address, City, Province, Postal Code, Telephone, Date of Birth, Email, Social Insurance Number (SIN)</li>

 <li>A customer may place many orders</li>

 <li>A customer does not always have to order through the same dealer all the time</li>

 <li>Customers often require financing/loans, and thus may need to have an account</li>

 <li>Customers may have one or more accounts, although they may also have no accounts</li>

 <li>The following information needs to be recorded about accounts:Balance, Last Payment Date, Last Payment Amount, Interest, Term</li>

 <li>A dealership may have many customers</li>

 <li>Orders are composed of one or more vehicles from inventory</li>

 <li>The following information about each order needs to be recorded:Order Date, Final Sale Price, Credit Authorization Status</li>

 <li>A vehicle is a unique item and can only be sold by one dealership (although it has happened that Wally has bought and resold the same vehicle at a different dealership)</li>

 <li>We wish to record the following about each vehicle:Vehicle Identification Number (VIN), Make, Model, Year, Colour, Km’s, Photo, Purchase Price, Sticker Price</li>

 <li>Wally obtains vehicles from a range of suppliers, including auctions, bank foreclosures, other dealerships and private sellers</li>

 <li>Every time a vehicle is purchased by Wally, his company pays a purchase price, and sells the vehicle at a ‘sticker price’</li>

 <li>The sticker price is always 35% more than the purchase price (this is how Wally makes profit!)</li>

 <li>Sales team members might agree to sell the vehicle for less than the sticker price, thus the order should track the final sale price</li>

 <li>Wally employs fifty-six employees</li>

 <li>He would like to track the following information about employees:Name, Address (Street, City, Province, Postal Code), Telephone, Date of Hire, Title, Salary, Age, Manager, and attributes that vary depending on the employee’s role</li>

 <li>If the employee’s role is that of a mechanic, we should track their Certification Number and Years of Experience</li>

 <li>If the employee’s role is that of a salesperson, we should track their commission and total Vehicles Sold</li>

 <li>If the employee’s role is that of a manager, we should track which employees they manage</li>

 <li>Some employees join Wally’s business as general staff, and have no special attributes to track</li>

 <li>Each employee works in one and only one dealership</li>

 <li>Each employee may have one or more dependents. We wish to record the name of the dependent as well as the age and relationship</li>

</ul>