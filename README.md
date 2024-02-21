# mac-changerPro

This bash script allows you to change the MAC address of a specified network interface.


### Requirements
• macchanger

### Installation

To install the script, follow these steps <br>

1 Clone the repository using the following command:
    
    git clone https://github.com/4m3rr0r/mac-changerPro

2 Change the working directory to the newly cloned repository:

    cd mac-changerPro
    
3 Make the script executable:

    chmod +x mac-changerPro


4 Move the script to `/usr/local/bin` to access it from anywhere in the system
    
    sudo mv mac-changerPro /usr/local/bin

## Usage

To run the script, use the following command:

    sudo mac-changerPro [OPTION] 
    
 Change the MAC address of either the eth0 or wlan0 network interface.
 
 ### Options
      -i, --interface    Specify the network interface (e.g., eth0, wlan0 etc)  
      -h, --help         Display this help menu

      
 
 
