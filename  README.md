# get multiple lan connection througt one ethernet connetion 

# whats the point ?
We need ethernet and POE througt one flat cable  (ethernet is standard and cheep  to  buy) 

if we use ethernet it shuld be speck  conform  
(at least a bit ... so it do not destroy too mutch :3 )

# Idea: 
use old Poe 1 standard 

than you  have 4 wires for POE 
in 2 pairs for  vcc and grond. 
and the other 4  wires for ethernet right ? 

you  cant divide them caus this cause trouble and would destroy firs funktionalety.
the voltage of poe 1 is a range therefore  poe 1  is compatible from  12 -48  v at least.

we can modulate the voltage to on the poe wire to transfare data. 
 
turns out there is a standart to  transfare ethernet over moulated DC current called FlowWire. 

you  can  use direct connection of 1:1  flowire or 1:9 on older standards

your poe device shuld work with  it. 

Becaus of several  reasons.
a all  your poe devices use a dc dc-converter internaly to step -down  your input from a specifiyd range to 3.3 or less voltage for internal  logic. 

you  can take out your flowire with the opponent  device.
the  last  question is dos the feald of the modulation destroy the other things in ethernet? 

I dont know. 

if this works we can  bring at least 3 ethernet connections trough  one wire with poe

# Testing it: 
for me was it not possible cause my flowwire equiptment was broken and was not fixable for me.
if someone had test it let me know :)
