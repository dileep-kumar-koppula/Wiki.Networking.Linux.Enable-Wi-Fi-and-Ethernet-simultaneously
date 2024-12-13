# Enable both Wi-Fi and Ethernet simultaneously.

+ Use the below command to use both Network Interfaces work
+ Here, We used `eth0` adapter to work with Wi-Fi Adapter

    ```bash
    sudo ip route add default via 192.168.0.2 dev eth0
    ```
