FindDomainCalls
===============

I had come accross to a scenario once while doing an incident response or rather a malware investigation. The scenario was while execution of suspecious file, infected machines will initiate calls to remote servers., i.e., attackers' servers. As usual I setup by sandbox and started capturing the network traffic and observed there were lot of DNS calls (FakeNet can do this task easily). After capturing the packets, it became a little hectic to go though each DNS calls and recon on them individually. So, I quickly build this script which can parse DNS calls, and do further recon on the extracted domains.
