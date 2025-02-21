---
title: Adding Gateways
section: Gateways
---

To connect your gateway to The Things Stack Community Edition, it has to be configured to properly forward the traffic to it, and it also has to be added/registered on The Things Stack Community Edition.

It is recommended to use [LoRa Basics Station protocol](https://www.thethingsindustries.com/docs/gateways/lora-basics-station/), due to a number of security and scalability issues related to the [UDP Packet Forwarder](https://www.thethingsindustries.com/docs/gateways/semtech-udp-packet-forwarder/).

To add a gateway, you will need to provide **Gateway EUI** and its **Frequency Plan**. Some other optional parameters can also be defined.

Registering your gateway can be done in two ways, via [Console](https://www.thethingsindustries.com/docs/getting-started/console/) or via [CLI](https://www.thethingsindustries.com/docs/getting-started/cli/).

More detailed instructions for adding gateways are available in the [official The Things Stack documentation](https://www.thethingsindustries.com/docs/gateways/).

If you are experiencing issues while adding gateways to The Things Stack Community Edition, see [Troubleshooting](https://www.thethingsindustries.com/docs/gateways/adding-gateways/troubleshooting/).
