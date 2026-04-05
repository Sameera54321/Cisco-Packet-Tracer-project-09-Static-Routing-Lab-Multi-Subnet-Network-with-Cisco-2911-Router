# Cisco-Packet-Tracer-project-09-Static-Routing-Lab-Multi-Subnet-Network-with-Cisco-2911-Router

I’m excited to share my latest Cisco Packet Tracer project – a static routing lab that demonstrates how to connect multiple isolated subnets using a single router with manually configured static routes.

![image alt](https://github.com/Sameera54321/Cisco-Packet-Tracer-project-09-Static-Routing-Lab-Multi-Subnet-Network-with-Cisco-2911-Router/blob/main/Static%20Routes.png?raw=true)

## 📌 Summary

### Static Routing Lab is a Cisco Packet Tracer simulation that teaches how to manually configure static routes on a single router (or multiple routers) to enable communication between different IP subnets. The topology includes:

    1 router – Cisco 2911 (R1)

    4 switches – Cisco 2960‑24TT / 2950‑24TT (access layer)

    6+ end devices – PCs and one server (Sanarth)

    Multiple subnets (as seen in the image):

    | Subnet | Example Device IP | Gateway (on R1) |
| :--- | :--- | :--- |
| 10.10.10.0/8 | Sanarth: 10.10.10.10 | 10.10.10.1 |
| 172.16.31.0/16 | PC: 172.16.31.12 | 172.16.31.1 |
| 192.168.50.0/24 | PC: 192.168.50.252 | 192.168.50.1 |
| 192.168.80.0/24 | PC: 192.168.80.100 | 192.168.80.1 |
| 200.10.150.0/24 | PC: 200.10.150.100 | 200.10.150.1 |
| 20.10.10.0/24 | Router interface | 20.10.10.1 |
| 20.10.20.0/24 | Router interface | 20.10.20.3 |

### The lab includes:

    Interface IP assignment on the router

    Static routes for each remote subnet

    Default gateway configuration on PCs and server

    Connectivity verification across all subnets

## ✨ Features

    ✅ Single router (2911) – central routing point

    ✅ 4 switches – connecting multiple end devices

    ✅ 6+ subnets – diverse IP ranges (private and public)

    ✅ Static routing – manual ip route entries

    ✅ End devices – PCs and server with static IPs

    ✅ Verification tools – ping, traceroute, show ip route

    ✅ Full Packet Tracer file (.pkt) – ready to load and practice

    ✅ Documentation – IP plan, static route tables, switch configs

## 🛠️ Built With

    Cisco Packet Tracer – version 8.x

    CLI – router, switch, and end‑device configurations

## 🤝 Contributing

Contributions are welcome! To extend this lab:

    Fork the repository.

    Add a second router and configure static routes between them.

    Replace static routes with a dynamic routing protocol (RIP/OSPF).

    Add a DHCP server to automate IP assignment.

    Implement ACLs to restrict traffic between specific subnets.

    Open a pull request with a clear description.

## 📜 License

Distributed under the MIT License. See the LICENSE file for more information.
Free to use, modify, and share for educational purposes.
