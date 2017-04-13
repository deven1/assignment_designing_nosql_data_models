You're building a restaurant table reserving app that allows users to reserve tables for specified numbers of people. The app will need to show only tables that are available and the times they are available. The app will need to store reservations under a given name with a phone number and number of guests.

INDEX TABLE
-----------
  * timeWindow_1 [tableID_1, tableID_2, tableID_3.....etc.]
  * timeWindow_2 [tableID_1, tableID_2, tableID_3.....etc.]
  * timeWindow_3 [tableID_1, tableID_2, tableID_3.....etc.]
  * timeWindow_4 [tableID_1, tableID_2, tableID_3.....etc.]
  * timeWindow_5 [tableID_1, tableID_2, tableID_3.....etc.]

DOCUMENTS
---------      
  * table
    -----
      tableID: INT
      seating_capacity : INT

  * reservation
    -----------
      number_of_guests: INT
      name_of_guest: String
      phone_number: String
      timeWindow: DateTime
      tableID: INT



You're building a backend for a university that requires students to be able to login. Once logged in, the students can view the exam grades for their classes. They should be able to view results by semester. Each semester should only show the classes in which that student is enrolled that semester.


