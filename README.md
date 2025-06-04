# port-killer


# How to Use:

Save as ports.sh


# Make it executable:

chmod +x ports.sh


# Run it:

./ports.sh


# ✅ Example Output:

🔍 Scanning open/listening ports...

▶ Using ss:
Netid  State      Recv-Q Send-Q Local Address:Port  Peer Address:Port
tcp    LISTEN     0      128    0.0.0.0:22          0.0.0.0:*
tcp    LISTEN     0      128    127.0.0.1:5432       0.0.0.0:*
udp    LISTEN     0      0      0.0.0.0:68           0.0.0.0:*
