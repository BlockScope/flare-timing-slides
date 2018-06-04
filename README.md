# Flare Timing Elevator Pitch

Flare Timing is a program for scoring HG and PG competitions.

A comp pilot will fly a race task every day of a comp, wx permitting.

At the morning briefing a task is declared as a list of TPs on the way to goal.

We fly with a vario. This tells us whether we're going up or down.

It also shows us the TPs and the glide angle to goal so that we can decide 
when to leave lift and dive for goal.

As well it logs our GPS position every couple of seconds.

A scorer will use the tracklog to work out;
* What order pilots arrived in goal
* How fast they flew
* Who was leading other pilots

If you didn't make goal;
* How far you flew
* How difficult was the section of the course you flew.

The project is 25K lines in 20 pkgs.
Some of these are small and general purpose, such as;
* Rounding and units of measure, serializing these with aeson
* Lat/Lng and working out distances on Earth

Others are specific to scoring.

There are easy problems to work on;
* Comparing the scores with published comp results

There are harder problems;
* Interpolating the time and position of a TP crossing
* Working out the shortest path around the course

It's a fun project.
