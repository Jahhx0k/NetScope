# 🌐 NetScope

**NetScope** is a GUI-based tool that helps users understand how firewall rules impact network traffic. It visualizes TCP/UDP flows on a local network and allows users to simulate rule sets to see what traffic would be allowed or blocked. 

Designed for network administrators and security professionals, NetScope simplifies firewall rule management by providing real-time traffic visualization, rule simulations, and interactive analysis of how firewall configurations affect data flows.

## 📌 Features

- 🌊 **Traffic Flow Visualization**:
  - Displays real-time TCP/UDP traffic flows between devices on the local network
  - Interactive network diagram for easy visualization of connections
  - Highlights allowed and blocked traffic based on current firewall rules

- 🔒 **Firewall Rule Simulation**:
  - Simulates how different rule sets impact network traffic
  - Test new firewall configurations before applying them to production environments
  - Simulate both inbound and outbound traffic rules

- 🛠️ **Customizable Rule Sets**:
  - Users can create, modify, and simulate custom firewall rules
  - Support for standard firewall rule formats (e.g., IP ranges, ports, protocols)
  - Real-time feedback on the effectiveness of new rules

- 🖥️ **User-Friendly GUI**:
  - Intuitive graphical user interface with drag-and-drop rule management
  - Visualizes firewall rules and their effects on traffic flow
  - Displays rule match details (source, destination, port, protocol)

- 📈 **Traffic Analytics & Reporting**:
  - Provides detailed logs of allowed and blocked traffic
  - Shows statistics on traffic patterns, rule hits, and blocked packets
  - Generates easy-to-read reports for auditing and troubleshooting

- 🔐 **Security & Privacy**:
  - Local traffic analysis with no data transmitted outside the network
  - Option to export rule simulations and reports securely for team collaboration
  - No external dependencies for simulating local network traffic

## 🛠️ Tech Stack

- **Frontend**: Python (Tkinter, PyQt5), JavaScript (for web-based interfaces)
- **Backend**: Python (Scapy, socket programming for traffic simulation)
- **Network Tools**: Wireshark, tcpdump for traffic capture
- **Storage**: Local (no external storage by default)
- **Security**: Local traffic analysis, no data transmission to external servers

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- PyQt5 (for GUI)
- Scapy (for traffic simulation)
- Network interface (local machine or virtual machine)

### Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/netscope.git
cd netscope
