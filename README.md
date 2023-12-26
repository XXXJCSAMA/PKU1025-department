# PKU1025-department
The Department of Security has a new headquarters building. 
The building has several floors, and on each floor there are rooms numbered xxyy where yy stands for the room number and xx for the floor number,
0 < xx; yy <= 10. The building has `pater-noster' elevator, i.e. elevator build up from several cabins running all around.
From time to time the agents must visit the headquarters. During their visit they want to visit several rooms and in each room they want to stay for some time. Due to the security reasons,
there can be only one agent in the same room at the same time, The same rule applies to the elevators. The visits are planned in the way ensuring they can be accomplished within one day. 
Each agent visits the headquarters at most once a day.

Each agent enters the building at the 1st floor, passes the reception and then starts to visit the rooms according to his/her list.
Agents always visit the rooms by the increasing room numbers. The agents form a linear hierarchy according to which they have assigned their one letter personal codes.
The agents with higher seniority have lexicographically smaller codes. No two agents have the same code.

If more then one agent want to enter a room, or an elevator, the agents have to form a queue. In each queue, they always stand according to their codes. 
The higher the seniority of the agent, the closer to the top of the queue he stands. Every 5 s (seconds) the first agent in the queue in front of the elevator enters the elevator.
After visiting the last room in the headquarters each agent uses if necessary elevator to the first floor and exits the building.

The times necessary to move from a certain point in the headquarters to another are set as follows:
Entering the building, i.e. passing the reception and reaching the elevator, or a room on the first floor takes 30 s.
Exiting the building, i.e. stepping out of the elevator or a room on the first floor and passing the reception takes also 30 s.
On the same floor, the transfer from the elevator to the room (or to the queue in front of the room), 
or from the room to the elevator (or to the queue in front of the elevator),
or from one room to another (or to the queue in front of the room) takes 10 s. The transfer from one floor to the next floor above or below in an elevator takes 30 s.
Write a program that determines time course of agent's visits in the headquarters.
