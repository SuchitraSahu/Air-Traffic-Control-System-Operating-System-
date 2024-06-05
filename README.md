# Air-Traffic-Control-System-Operating-System-
In this assignment, we are going to use the different OS concepts learnt so far to create an Air Traffic Control System. 
● Plane (Each plane is a single-threaded process). Two types of planes are considered.
○ Passenger plane: includes passengers, 5 cabin crew members and 2 pilots
○ Cargo plane: includes only 2 pilots
● Airport (Each airport is a multi-threaded process)
● Air Traffic Controller (ATC) (This is a single-threaded process)
● Passenger traveling on a specific passenger plane (Each passenger process is a child of the corresponding plane process and each passenger process is single-threaded)
● Cleanup (This is a single-threaded process)
The overall block diagram of the Air Traffic Control System is depicted in the following figure. Note that the diagram only depicts passenger plane processes. If the plane is of type cargo, there will be no passengers onboard. In the figure, ATC implies Air Traffic Controller.
