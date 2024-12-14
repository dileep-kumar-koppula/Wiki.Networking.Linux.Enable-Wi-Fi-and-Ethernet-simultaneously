# Enable both Wi-Fi and Ethernet simultaneously

+ Use the below command to use both Network Interfaces work
+ Here, We used `wlan0` adapter to work with Ethernet (LAN) Adapter
+ `192.168.0.1` should be the Default Gateway (Mostly Router IP Address)

    ```bash
    sudo ip route add default via 192.168.0.1 dev wlan0
    ```
