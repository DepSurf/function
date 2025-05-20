# Function: <code>is_zero_ether_addr</code>

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
In drivers/base/property.c (0)
Location: include/linux/etherdevice.h:96
Inline: True
```
```
In net/ethernet/eth.c (0)
Location: include/linux/etherdevice.h:96
Inline: True
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
In drivers/base/property.c (ffffffff815a36d4)
Location: include/linux/etherdevice.h:96
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff817aca6c)
Location: include/linux/etherdevice.h:96
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_validate_addr
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
In drivers/base/property.c (ffffffff815d1de4)
Location: include/linux/etherdevice.h:96
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff817dc05c)
Location: include/linux/etherdevice.h:96
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_validate_addr
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
In drivers/base/property.c (ffffffff815e6c25)
Location: include/linux/etherdevice.h:101
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817fb65c)
Location: include/linux/etherdevice.h:101
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
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
In drivers/base/property.c (ffffffff8164e065)
Location: include/linux/etherdevice.h:102
Inline: True
```
```
In net/ethernet/eth.c (ffffffff8187900c)
Location: include/linux/etherdevice.h:102
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
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
In drivers/base/property.c (ffffffff81688c45)
Location: include/linux/etherdevice.h:102
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff818ca9fc)
Location: include/linux/etherdevice.h:102
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
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
In drivers/base/property.c (ffffffff816a8945)
Location: include/linux/etherdevice.h:102
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff818f5f87)
Location: include/linux/etherdevice.h:102
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
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
In drivers/base/property.c (ffffffff816e1d35)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/core/ethtool.c (ffffffff81908900)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffff819555ed)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6de84)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff81705ee5)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/core/ethtool.c (ffffffff8193b043)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffff8198ba8d)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa4854)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff817c0dc7)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81a6368d)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ethtool/ioctl.c (ffffffff81a81e1a)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba0424)
Location: include/linux/etherdevice.h:98
Inline: True
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
In drivers/base/property.c (ffffffff817d5b77)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81a6b7dd)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ethtool/ioctl.c (ffffffff81a8b8ea)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bafe04)
Location: include/linux/etherdevice.h:98
Inline: True
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
In drivers/base/property.c (ffffffff817b9597)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81a53f3d)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ethtool/ioctl.c (ffffffff81a74adc)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9ef6f)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff818431f7)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81b0cc4d)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ethtool/ioctl.c (ffffffff81b2f52b)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6c5ef)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In net/ethernet/eth.c (ffffffff81c93a1c)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ethtool/ioctl.c (ffffffff81cba1e1)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e10561)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In net/ethernet/eth.c (ffffffff81e4f15c)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ethtool/ioctl.c (ffffffff81e789e7)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe6c51)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_intel
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/net/ethernet/microchip/vcap/vcap_tc.c (ffffffff81c5f6d1)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
```
```
In net/ethernet/eth.c (ffffffff81eaa7fc)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ethtool/ioctl.c (ffffffff81ed4e98)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82062b65)
Location: include/linux/etherdevice.h:105
Inline: True
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
In drivers/net/ethernet/microchip/vcap/vcap_tc.c (ffffffff81d16071)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_arp_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
  - drivers/net/ethernet/microchip/vcap/vcap_tc.c:vcap_tc_flower_handler_ethaddr_usage
```
```
In net/ethernet/eth.c (ffffffff81f6d2ac)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ethtool/ioctl.c (ffffffff81f9895d)
Location: include/linux/etherdevice.h:105
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82135cb1)
Location: include/linux/etherdevice.h:105
Inline: True
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
In drivers/base/property.c (ffff8000108f2b4c)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e44fc)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e95ac)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb854)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
```
```
In drivers/of/of_net.c (ffff800010b756c0)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/core/ethtool.c (ffff800010bd928c)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffff800010c36a88)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d75f5c)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (c09df790)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0aca4c0)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad592c)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
```
```
In drivers/of/of_net.c (c0c57adc)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/core/ethtool.c (c0cf3b04)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (c0d493f4)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (c0e72018)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (c00000000098d668)
Location: include/linux/etherdevice.h:98
Inline: True
```
```
In drivers/of/of_net.c (c000000000c52c5c)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/core/ethtool.c (c000000000cba3c8)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (c000000000d2ec48)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb65d8)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffe000584ed6)
Location: include/linux/etherdevice.h:98
Inline: True
```
```
In drivers/of/of_net.c (ffffffe000728dc0)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/core/ethtool.c (ffffffe00076263a)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffe0007a8472)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a6904)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff816cb635)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/core/ethtool.c (ffffffff818db013)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffff8192b8fd)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a43be4)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff816a6965)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In drivers/net/vxlan.c (ffffffff8176b484)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_validate
  - drivers/net/vxlan.c:vxlan_flush
  - drivers/net/vxlan.c:vxlan_fdb_update
  - drivers/net/vxlan.c:vxlan_fdb_update_existing
  - drivers/net/vxlan.c:vxlan_fdb_update_existing
  - drivers/net/vxlan.c:vxlan_fdb_find_uc
  - drivers/net/vxlan.c:vxlan_fdb_info
```
```
In net/core/ethtool.c (ffffffff81894e53)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffff818e56ad)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a007d4)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff816f9ba5)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/core/ethtool.c (ffffffff8192c043)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffff8197ca8d)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aafa94)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
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
In drivers/base/property.c (ffffffff81714445)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/core/ethtool.c (ffffffff8194d713)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
  - net/core/ethtool.c:ethtool_rx_flow_rule_create
```
```
In net/ethernet/eth.c (ffffffff8199efed)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abbe44)
Location: include/linux/etherdevice.h:98
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
```
</details>
</li>
</ul>

## Differences
