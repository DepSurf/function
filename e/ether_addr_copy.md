# Function: <code>ether_addr_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff81739562)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817403a7)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff817a5816)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817ad157)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/switchdev/switchdev.c (ffffffff8188b58b)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_del
  - net/switchdev/switchdev.c:switchdev_port_fdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/netpoll.c (ffffffff817d4286)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817dc7c7)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/switchdev/switchdev.c (ffffffff818bf90b)
Location: include/linux/etherdevice.h:274
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_del
  - net/switchdev/switchdev.c:switchdev_port_fdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c508a)
Location: include/linux/etherdevice.h:279
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/netpoll.c (ffffffff817f35c8)
Location: include/linux/etherdevice.h:279
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff817fbe97)
Location: include/linux/etherdevice.h:279
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/switchdev/switchdev.c (ffffffff818e65bf)
Location: include/linux/etherdevice.h:279
Inline: True
Inline callers:
  - net/switchdev/switchdev.c:switchdev_port_fdb_del
  - net/switchdev/switchdev.c:switchdev_port_fdb_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183eb32)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/netpoll.c (ffffffff8186e9b8)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff81879857)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81889761)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/netpoll.c (ffffffff818bfb42)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff818cb207)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818aa312)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/netpoll.c (ffffffff818e8962)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff818f5fa0)
Location: include/linux/etherdevice.h:280
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f5534)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffff81908909)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffff81938174)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff8195561d)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81927408)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffff8193b04c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffff8196b034)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff8198babd)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fb091)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81a3eda5)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff81a636bd)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/ethtool/ioctl.c (ffffffff81a81e23)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f01aa)
Location: include/linux/etherdevice.h:287
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff819facbe)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81a41b45)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff81a6b80d)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/ethtool/ioctl.c (ffffffff81a8b8f3)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d4ae4)
Location: include/linux/etherdevice.h:287
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff819e0e76)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81a26602)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81a36201)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81a53f6d)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/ethtool/ioctl.c (ffffffff81a74ae5)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a84874)
Location: include/linux/etherdevice.h:287
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81a912b6)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81adb37d)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81aebea5)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81b0cc7d)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
```
In net/ethtool/ioctl.c (ffffffff81b2f534)
Location: include/linux/etherdevice.h:287
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfa887)
Location: include/linux/etherdevice.h:295
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81c073ad)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81c5c884)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81c6e82c)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81c93d30)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
```
In net/ethtool/ioctl.c (ffffffff81cba1ee)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da94ba)
Location: include/linux/etherdevice.h:295
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81db6e0d)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81e12f74)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e2655c)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81e4f4e0)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
```
In net/ethtool/ioctl.c (ffffffff81e789f4)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e181ea)
Location: include/linux/etherdevice.h:295
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81e274cd)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81e868a0)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81e9bafd)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81eaab80)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
```
In net/ethtool/ioctl.c (ffffffff81ed4ea5)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed568a)
Location: include/linux/etherdevice.h:295
Inline: True
```
```
In net/core/flow_dissector.c (ffffffff81ee581e)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
  - net/core/flow_dissector.c:__skb_flow_dissect_arp
```
```
In net/core/netpoll.c (ffffffff81f488ad)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/core/selftests.c (ffffffff81f5e25d)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/core/selftests.c:net_test_get_skb
  - net/core/selftests.c:net_test_get_skb
```
```
In net/ethernet/eth.c (ffffffff81f6d640)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:platform_get_ethdev_address
```
```
In net/ethtool/ioctl.c (ffffffff81f9896a)
Location: include/linux/etherdevice.h:295
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e2530)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_set_mac_address
```
```
In drivers/net/ethernet/broadcom/bgmac-platform.c (ffff8000109e5030)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac-platform.c:bgmac_probe
```
```
In drivers/net/ethernet/freescale/fman/mac.c (ffff8000109f3c90)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fman/mac.c:mac_probe
  - drivers/net/ethernet/freescale/fman/mac.c:set_multi
```
```
In net/core/flow_dissector.c (ffff800010bc3928)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffff800010bd929c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffff800010c1160c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffff800010c36ac4)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ethernet/ti/cpsw.c (c0ad34a8)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe_dt
```
```
In net/core/flow_dissector.c (c0cdec74)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (c0cf3b14)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (c0d2955c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (c0d4942c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9db0c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (c000000000cba3dc)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (c000000000cfe324)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (c000000000d2eca0)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe0007503f0)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffe000762650)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffe00078d818)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffe0007a84a0)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c7408)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffff818db01c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffff8190b004)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff8192b92d)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/vxlan.c (ffffffff817736f1)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:neigh_reduce
  - drivers/net/vxlan.c:vxlan_fdb_find_uc
```
```
In net/core/flow_dissector.c (ffffffff81881348)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffff81894e5c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffff818c4d9f)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff818e56dd)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81918408)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffff8192c04c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffff8195c034)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff8197cabd)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81939794)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/core/ethtool.c (ffffffff8194d71c)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/core/netpoll.c (ffffffff8197e414)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_send_udp
  - net/core/netpoll.c:netpoll_send_udp
```
```
In net/ethernet/eth.c (ffffffff8199f01d)
Location: include/linux/etherdevice.h:276
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_platform_get_mac_address
```
</details>
</li>
</ul>

## Differences
