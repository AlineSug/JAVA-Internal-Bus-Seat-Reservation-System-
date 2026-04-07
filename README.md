I developed this application as an internal bus seat reservation system.
The project was built using Java in IntelliJ IDEA, with MongoDB running locally as the database.
For the user interface, I used Java Swing to create a simple and intuitive layout.
The bus seats are represented as buttons in a graphical view: green indicates an available seat, while red indicates an occupied one.

The system allows users to register a passenger’s name and CPF (Brazilian ID) in order to reserve a seat for a specific date. 
Once a reservation is completed, the data is stored in the system’s reservation history. 
Users can also delete reservations, which completely removes the data from the system.
Additionally, the application provides a full reservation history view, with filtering options by name, seat number, date, and other criteria.

It is also possible to export the reservation history as a CSV file, which can be saved locally on the user’s computer.
This file can be opened in spreadsheet applications such as Excel or Numbers, making it useful for record-keeping and
for generating data for future reports or declarations.
