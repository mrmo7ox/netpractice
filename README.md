# netpractice

my journey into networking, ip addressing, and subnetting for the 1337 curriculum.

## the story
so netpractice is basically a puzzle game but for networking. instead of writing c code, you get thrown into these broken network topologies and have to fix them. at first, looking at ip addresses and /24 or /30 cidr notations just looked like random numbers. i had to sit down with a piece of paper and actually learn how to convert ip addresses to binary just to understand how routers decide where to send packets and how masks actually work.

## the goal
the main objective is to pass 10 different levels of network configurations, going from level 1 all the way up to level 10. each level is stored as its own json file and gives you a mix of clients, routers, and switches. you have to configure the ip addresses, subnet masks, and routing tables so that all the specified devices can successfully communicate with each other. you have to figure out things like how to put two computers on the exact same subnet or how to route traffic through multiple hops to reach an external internet server without overlapping your private networks.

## the lesson
i learned so much about how the actual internet works under the hood. subnetting makes complete sense to me now. i know how to calculate network addresses, broadcast addresses, and usable ip ranges just by looking at a subnet mask. it also made me realize how important routing tables are and how the default gateway is the only way a device can find its way out of a local area network.

## how to use
there is no code to compile for this project. you just run the provided index.html file in a web browser, load up the interactive levels from their respective json files, and start typing in the correct ip addresses and routing rules to make the network connections light up and work.
