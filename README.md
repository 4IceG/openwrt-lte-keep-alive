# LTE OpenWRT Keep-alive scripts

You might need to compile OpenWRT with netcat package (which requires changes to kernel config).
The main script tests the online status, then has 2 fallback options.
Firstly, it restarts the interface associated with your LTE modem, this usually helps.
Secondly, if there are too many interface restarts, it restarts whole router. There might be a step to restart networking, but I did not bother :)

Enjoy!