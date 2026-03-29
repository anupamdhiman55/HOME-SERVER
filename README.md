# HOME-SERVER
Creating a high-performance home server using an old laptop and a mobile hotspot is a brilliant way to repurpose hardware while maintaining high data privacy. This setup acts as a personal, globally accessible cloud that eliminates reliance on subscription-based services like Google Photos.
Home Server: Old Laptop & Hotspot Setup
Architecture:

• Internet Source: Phone Hotspot.

• Network Bridge: A Router in 'Repeater/Client Mode' connects to the Hotspot and creates a local LAN.

• The Server: Old laptop (Lid-sleep disabled, plugged in) connected to the Router.

Key Functionalities:

• Global Access: Uses a VPN Tunnel (e.g., Tailscale ) to bypass mobile CGNAT, allowing access from the office or anywhere in the world.

• Auto-Backup: Running Immich to provide a "Google Photos" experience with automatic media syncing.

• Local Connectivity: All home devices (TVs, tablets) connect to the Router to stream or access files locally.

Advantages:

• Built-in UPS: Laptop battery protects against power flickers.

• Energy Efficient: Lower power draw than dedicated desktops.

Set a battery charge limit (e.g., 60%) to prevent battery swelling from being plugged in 24/7.
