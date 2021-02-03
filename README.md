# MHN Dionaea Deployment Scripts

While using MHN as a Honeynet master It was apparent that some tweaks to the Dionaea deployment script was needed. 

These scripts are designed for $5 servers on both Digital Ocean and Linode, One thing to note is the hard coded IP for the HPFeeds connection. This appears to be the easiest method for deployment. 

This script includes

 - Bistream Management / Rotation
 - VirusTotal Integration
 - Dionaea Config Tweak (Reduces Log files / storage requirements)
 - On Linode it will also disable IPv6 addresses as this appeared to cause some issues with dionaea

