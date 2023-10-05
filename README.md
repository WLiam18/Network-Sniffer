# Network Sniffer with Scapy


The Network Sniffer with Scapy is a Python script designed for network analysis and exploration. It utilizes the Scapy library to capture and examine network traffic, making it a valuable tool for network administrators and security professionals.

## How to Use

1. Clone or download this repository to your local machine.

2. **Run with Root/Admin Privileges:**
   - To capture network traffic effectively, ensure you run the script with root/administrator privileges.

3. **Syntax:**
   - Execute the script from the command line using the following syntax:
     ```bash
     python network_sniffer.py <ip_address>/<subnet>
     ```
   - Replace `<ip_address>/<subnet>` with the target IP address or IP range you want to monitor.

4. **Observe Network Activity:**
   - The script will capture network packets and display relevant information about the source IP addresses and their corresponding MAC addresses.

## Features

- A powerful network analysis tool powered by Scapy.
- Real-time monitoring of network traffic.
- Provides insights into source IP addresses and MAC addresses.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Inspired by the need for network monitoring and analysis tools.
- Built with the Scapy library for packet manipulation and sniffing.
