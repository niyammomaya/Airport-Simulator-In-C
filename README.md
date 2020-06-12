# Airport-Simulator-In-C

To simulate the working of an airport.

Let us consider a small but busy airport with only one runway. In each unit of time (minute, hour), one plane can land or one plane can take off, but not both. Planes arrive ready to land or ready to take off at random times, so at any given unit of time, the runway may be idle or a plane may be landing or taking off and there may be several planes waiting either to land or take off. We therefore need two queues, called landing and takeoff, to hold these planes. It is better to keep a plane waiting on the ground than in the air, so a small airport allows a plane to take off only if there are no planes waiting to land. Hence, after receiving requests from new planes to land or take off, our simulation will first service the head of the queue of planes waiting to land, and only if the landing queue is empty, will it allow a plane to take off. The simulation should run through many units of time. 
