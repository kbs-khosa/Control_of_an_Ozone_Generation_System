# Control_of_an_Ozone_Generation_System
# There are two sections in the project.
# The first section deals with the design of start-up and shut-down systems for the overall system. In these systems, there is a Master Controller (MC) which receives the signals to control the Local Controller (LC) which in turn is responsible for the opening and closing of the valves in the system by analyzing the values from the pressure sensors.
# The system can functioning after all the valves are opened. This is followed by turning ON the Power Supply Unit (PSU) which starts the Ozone Generation System. After the system has started, LC can send a signal to MC indicating that the system is functioning.
# The second part of the project deals with the issues faced practically. This part implements the safety measures. The ozone generator has to be purged first so that the oxygen flow is established befor the PSU starts. This is accomplished by using a supervisor.
# Thus there are a total of 2 supervisors in the system, one for each part.
