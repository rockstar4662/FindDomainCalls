FindDomainCalls
===============

I had once come accross with a scenario while doing an incident response or rather a malware/exploit investigation. The scenario was this - while execution of suspecious file, infected machines will initiate calls to remote servers., i.e., attackers' machines. As usual I setup a sandbox and started capturing the network traffic and observed there were lot of DNS calls (FakeNet can do this task easily). After capturing the packets, it became a little hectic to go though each DNS calls and recon on them individually. So, I quickly cooked this script which can parse DNS calls from a network capture, and do further recon on extracted domains.
