                                                                           **Debugging the Calendar Booking System**

Step 1: Understanding the Requirements: The first step in debugging the code was to understand the requirements of the calendar booking system. The system should allow users to book events with a start and end time, and it should prevent overlapping events from being booked.

Step 2: Identifying the Issues Upon reviewing the code, the following issues were identified: The "insert" method in the "Node" class was not correctly handling the insertion of new nodes based on their start and end times.
The "book" method in the "Calendar" class was not correctly calling the insert method on the root node.

Step 3: Debugging the "insert" Method: The "insert" method was modified to correctly handle the insertion of new nodes. The method now checks if the new node's start time is greater than or equal to the current node's end time, and if so, it goes to the right child. If the new node's end time is less than or equal to the current node's start time, it goes to the left child. If neither condition is met, the insertion fails.

Step 4: Debugging the "book" Method: The "book" method was modified to correctly call the insert method on the root node. This ensures that new events are correctly inserted into the calendar.

                                                                                      ** Underlying Issue **
The underlying issue with the initial code was the incorrect implementation of the insert method in the Node class. The method was not correctly handling the insertion of new nodes based on their start and end times, which led to overlapping events being booked.

                                                                                            ** Solution **
  The Solution for the problem I attached in the another File.
