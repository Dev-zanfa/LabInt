# LabInt
During this course the following report have been developed:

## Group analysis
In this experience we analyzed the open source *Signal* app. 
More in details we tried to discover protocols and mechanism that regulate the following actions:
- opening and closing the app
- direct message on a single chat
- message on a group chat
- vocal messages 
- multimedia file exchange 
- videocall

Using wireshark packet sniffing and linux command line we were able to process the gathered information and elaborate some theories on the app functionalities.

## Individual Report _ NMAP command
This was an in depth report on Nmap scanning functionalities and how different scan modes operates at different level. 
- scan TCP (privileged/unprivileged) 
- scan UDP (privileged)

## Report 1 - Advanced ping
Using wireshark the following scenarios are analyzed, in particular exchanged packets and ARP tables behaviour:
- ping to a broadcast address
- ping to a valid network address
- ping to duplicate addresses in the same subnetwork
- ping in network with wrong and peculiar netmask configurations 

## Report 2 - Speed analysis using ping command
In this expreience an estimate of the speed at phisical layer is made, using ping command and operating on transmitted packets.
Different configuration are analyzed

## Report 3 - performance test on *off the shell* hardware 
Goodput estimate between two different host on a simplified network model, using *iperf3* to confirm the prediction
