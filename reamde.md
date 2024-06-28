Rule1 
on switch1#state do backlog add1 1 endon   on var1#state==1 do power1 1 endon   on var1#state==1 do power2 0 endon   on var1#state==2 do power1 0 endon   on var1#state==2 do power2 1 endon   on var1#state==3 do power1 1 endon   on var1#state==3 do power2 1 endon   on var1#state==4 do power1 0 endon   on var1#state==4 do power2 0 endon   on var1#state==4 do var1 0 endon
rule1 on

Rule2
on power3#state==1 do backlog var1 0; power1 0; power2 0 endon
rule2 on

Rule3
on power4#state==1 do backlog add1 1 endon   on var1#state==1 do power1 1 endon   on var1#state==1 do power2 0 endon   on var1#state==2 do power1 0 endon   on var1#state==2 do power2 1 endon   on var1#state==3 do power1 1 endon   on var1#state==3 do power2 1 endon   on var1#state==4 do power1 0 endon   on var1#state==4 do power2 0 endon   on var1#state==4 do var1 0 endon
rule3 on

