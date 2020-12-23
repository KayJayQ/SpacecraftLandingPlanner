# SpacecraftLandingPlanner

## What problem does it solve?
In KSP (RSS), it is hard to decide when to ignite the descent engine. If you ignite it too early, then you probably hover on some altitude above 10km and waste tons of fuel. If you ignite too late, then a crash with 1km/s is heart breaking. This script aims to calculate the ignition position for you. Luckly you will make it zero speed above several hundreds of meters from ground.

## How to use?
You need to make your spacecraft enter a descend orbit at first. (Perigee under ground)
Then, enter key parameters about everything.

dry_mass and wet_mass can be read from MJ deltaV (long statistic) page

thrust #Max thrust of spacecraft, in Newton

Isp #Isp, gravity measure, unit: second

g #g for landing planet. meter per second square

R #Radius of landing planet, meter

pv #parallel velocity, meter per second, no direction needed

vv #vertical velocity towards space, meter per second

altitude #current altitude, meter

OK! Restart the script and get the ignition altitdue!
Attention! Lock thrust vector to anti-velocity direction.
The default parameters was for Chang E 5 moon vessel landing stage.
