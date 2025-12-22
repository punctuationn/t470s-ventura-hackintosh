# macOS Ventura EFI folder for T470s
# GET YOUR OWN SERIAL NUMBERS 
To get them just follow this section of the opencore guide also i used MacbookPro14,1  https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/kaby-lake.html#platforminfo <br>
you should still read the entire opencore guide but if you're on a time crunch (you shouldn't be doing this in the first place) just read the config.plist section for kaby lake laptop
<br>
Specifications: <br>
Intel(R) Core(TM) i7-7600U CPU @ 2.80 GHz <br>
Intel(R) HD Graphics 620 <br>
Realtek ALC298 @ Intel Sunrise Point-LP PCH - High Definition Audio Controller [C1] <br>
Intel Dual Band Wireless-AC 8265 WiFi Adapter <br>
Intel Ethernet Connection (4) I219-LM <br>
KXG5AZNV512G TOSHIBA (TOSHIBA XG5 NVME SSD 512 GB M.2 2280)
16GB Ram<br><br>
### also quick note remove the intelbtpatcher, bluetoolfixup and intel bluetooth firmware kexts when installing also remember to update the config.plist just add them back and reflect that in the config.plist when done installing <br><br>

the hdmi semi works everything else should work except for airdrop<br>
also i have itlwm and airportitlwm you could probably remove itlwm but it still works so i haven't removed it
