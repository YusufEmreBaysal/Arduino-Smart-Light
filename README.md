# Arduino-Smart-Light

There are countless Arduino wireless temperature sensor codes available online. You can follow any of them—I did the same. However, over time, I noticed an issue: after 1-2 days of continuous operation, the Arduino's Wi-Fi connection would drop, and the only way to reconnect was to manually restart the Arduino using the reset button.

This project addresses that issue by periodically checking the Wi-Fi connection status. If the connection is lost for a certain period, the system automatically attempts to reconnect.

The project has been in active use for over a year. Monitoring the connection status via Arduino Cloud reveals that occasional disconnections occur every few days due to device errors. However, these interruptions generally last no more than a minute, as the Arduino automatically reconnects to the Wi-Fi network.
