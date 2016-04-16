# Control_of_an_Ozone_Generation_System
# There were two sections in the project.
# The first section dealt with the designing of start-up and shut-down systems for the overall system. In these systems, there was a Master Controller (MC) which received signals to control the Local Controller (LC) which in turn was responsible for the opening and closing of the valves in the system by analyzing the values from the pressure sensors.
# The system was such that it could function only after all the valves were opened. This was followed by turning ON the Power Supply Unit (PSU) which started the Ozone Generation System. After the system was started, LC sent a signal to MC indicating that the system was functioning properly.
# The second part of the project took care of the practical issues. This part implemented the safety measures. The ozone generator had to be purged first so that the oxygen flow was established befor the PSU started. This was accomplished by using a supervisor.
# Thus there were a total of 2 supervisors in the system, one for each part.
