<p align="center">
  <img src="https://i.imgur.com/XBAtE7W.png"><br>
</p>

# Fractal Trees Generator

<br>
Let's be honest - trees generated only from constant numbers are boring.. so in default version nearly every value used to create a new branch is randomized - random amount of branches, horizontal (yaw) and vertical (pitch) rotation (if needed there can also be a random length, thickness or the density of points in every branch)
Everything sounds great until you create some trees using that randomized values (they are just ugly lines without any pattern - which is shown in gallery below)

The best part while playing with this code is adding some conditions that tell how to generate those trees (for example: amount of branches depending on the current generation so there won't be 3 or more braches growing from ground etc.). Possibilities are unlimited.

There are no leaves on them for now - I will try to make some in the future (or you can make them yourself)

For now there will be only the default version - but my plan is to add more configurations in next few days/weeks.

Blocks are generated asynchronously, so there shuoldn't be a TPS drop even with bigger trees.


## Created and tested on:
- Purpur-966 (1.16.5)
- Skript 2.5.3 
- skript-reflect 2.2-alpha3

<br><br>

## Gallery

<p align="center">
  [- some ugly default trees:<br>](default.sk)
  <img src="https://i.imgur.com/4yLdU4b.jpg"><br><br>
  - an example or what this function can do:<br>
  <img src="https://media.discordapp.net/attachments/393129870722596868/815654840163369050/unknown.png">
</p>
