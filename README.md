# CHWNT
Can't Hit What's Not There

Manage your wifi network over ssh, timed/controlled up/down, GUI

Wifi - "Loudness Wars" like the period in audio recordings where they were trying to burn that LP pressing as max-loudness... so everyone upgrading their wifi which is just saturating the airwaves, and the new 802.11AC dumping on the 2.4Ghz channels for anyone stuck on them.  So a background proliferation of devices problem, and ease of access to tools for bad-actors...

I guess it's a design principle, now a common problem, so design to not be there longer than necessary, and back-out if contention for logging-on....

I guess with trilateration, might make a good guess at revenge attack targets, but, "an eye for an eye and soon the whole world will be blind" eh! (and from my testing of same chips running same arduino-chain software, probability of false trilateration seems high.... 1 of 4 chips seems v.good... long term calibration eh!  Find 4 or more good ones, the ESP8266's not even receiving the same packets.)

I guess if you really want to get into it need multiple sdr radios sweeping eh! trusted chips eh!  I guess detecting a radio receiver would be a handy trick.... any electronics probably a transmiter....

Ideally I'm thinking port-knocking using packet injection of a custom packet on an esp-8266 with a guard/tripwire esp-8266 doing monitoring on each pi, esp-8266 seem much harder to disrupt off wifi compared to an old pi-zero running a full linux.

Static IP addresses on raspberry nodes will improve the wifi connect process, no dhcp negotiation required each time up, just a pain in the neck to manage manually rather than setting by mac address on the router.

Another one of those things that you can spend a lot of time on to be negated as soon as the the zero-2w becomes available which I read does wpa3, I have not got my hands on one yet...
