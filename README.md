# RaspberryPI
Tutorial for myself on the learning process

The best way to output your Raspberry PI to your personal laptop is to establish a VNC server via Ethernet connection.

# 1. Connect your Raspberry Pi using the PC Ethernet Port using a straight Ethernet Cable.
# 2. Configure Ethernet properties in WiFi sharing center
https://farm4.staticflickr.com/3766/19707818710_b215538c81_o_d.png
https://farm1.staticflickr.com/498/19888335082_f7291782a5_o_d.png
# 4. So our laptop has an IP address of 192.168.0.10 and a gateway of 192.168.0.1 but your laptop may need a different IP address. I also tested 192.168.3.10 and gateway 192.168.3.1 and they both worked a treat. What's important is that you use an IP range that is similar for both the laptop and Raspberry Pi
# 5. Such an IP will be used to for connection via VNC server. Download links for Putty and VNC client are below:
https://www.realvnc.com/en/connect/download/viewer/

# 6. Connect Raspberry PI to a monitor and install VNC using the previous link 
# 7. After installation, type in terminal "sudo vncpasswd /root/.vnc/config.d/vncserver-x11" in order to install a password (ex: raspberry)
# 8. Check this link for the next settings: https://bigl.es/directly-connecting-to-a-raspberry-pi/
