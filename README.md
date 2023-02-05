# mac-cangerPro

This is a bash script that can change the MAC address of either the eth0 or wlan0 network interface.

### Requirements <br/>
• macchanger

### Installation

To install the script, follow these steps <br>

1 Clone the repository using the following command:
    
    git clone https://github.com/4m3rr0r/mac-cangerPro

2 Change the working directory to the newly cloned repository:

    cd mac-cangerPro
    
3 Make the script executable:

    chmod +x mac-cangerPro


4 Move the script to `/usr/local/bin` to access it from anywhere in the system
    
    sudo mv mac-cangerPro /usr/local/bin

## Usage

To run the script, use the following command:

    sudo mac-cangerPro [OPTION]
    
 Change the MAC address of either the eth0 or wlan0 network interface.
 
 ### Options
      
      -e, --eth0         Change the MAC address of the eth0 interface
      -w, --wlan0        Change the MAC address of the wlan0 interface 
      -h, --help         Display this help menu

      
 
 
