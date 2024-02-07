# Book-of-admin-tips
quick book of common issues in the sys admin world.


1. turn it off and back on<br>
2. its DNS<br>
3. its a firewall issue<br>
4. its SElinux<br>
5. the time and / or date is wrong<br>
6. you’re missing libs and dependencies<br>

network diagnosing:<br>
<br>
<br>
layer 4: application<br>
  - is the application running?<br>
  - can you get to it from the localhost?<br>
  - any firewalls in the way?<br>
  - is it DNS? try going to the IP rather than hostname.<br>
<br>
layer 3: transport<br>
  - tcp / udp, does a syn scan show it open?<br>
  - is the application listening on a port?<br>
<br>
layer 2: network<br>
  - can you ping into it? can it ping out?<br>
<br>
layer 1: physical<br>
  - is it even plugged in<br>
