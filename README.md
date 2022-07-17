A static-hard-linked build of Quake 3 with Baseq3a for higher native performance. The correct interfaces have been limited to only support baseq3 content. QVMs removed for conciseness. 

# BIG WARNING:

There's no reason this should work. The fact that it does, just goes to show how perfectly isolated
all the system are. I have not tested this throughly. People report there are tons of static variables
that need to be reset in between games. All I did was get it to compile and successfully load a map
and walk around a bit. I'm pretty amazed at how fast and responsive it feels so it was worth 
publishing separately. I would like to get MUSL and image support libraries working on and embedded
system like Raspberri Pi with the added benefit of LTO and tree-shaking from having it statically linked.


