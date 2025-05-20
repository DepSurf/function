# Function: <code>is_valid_ether_addr</code>

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
In drivers/base/property.c (ffffffff81551b4b)
Location: include/linux/etherdevice.h:189
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff8173fcba)
Location: include/linux/etherdevice.h:189
Inline: True
Inline callers:
  - net/ethernet/eth.c:eth_validate_addr
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
In drivers/base/property.c (ffffffff815a36cb)
Location: include/linux/etherdevice.h:189
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff817aca65)
Location: include/linux/etherdevice.h:189
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
In drivers/base/property.c (ffffffff815d1ddb)
Location: include/linux/etherdevice.h:189
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff817dc055)
Location: include/linux/etherdevice.h:189
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
In drivers/base/property.c (ffffffff815e6c1c)
Location: include/linux/etherdevice.h:194
Inline: True
```
```
In net/ethernet/eth.c (ffffffff817fb655)
Location: include/linux/etherdevice.h:194
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
In drivers/base/property.c (ffffffff8164e05c)
Location: include/linux/etherdevice.h:195
Inline: True
```
```
In net/ethernet/eth.c (ffffffff81879005)
Location: include/linux/etherdevice.h:195
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
In drivers/base/property.c (ffffffff81688c3c)
Location: include/linux/etherdevice.h:195
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff818ca9ec)
Location: include/linux/etherdevice.h:195
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
In drivers/base/property.c (ffffffff816a893c)
Location: include/linux/etherdevice.h:195
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff818f5f7f)
Location: include/linux/etherdevice.h:195
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
In drivers/base/property.c (ffffffff816e1d2c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff819555e5)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a6de78)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff81705edc)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff8198ba85)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aa4848)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff817c0d58)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81a63685)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81ba0417)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff817d5b08)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81a6b7d5)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81bafdf7)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff817b9528)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81a53f35)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81b9ef5e)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff81843188)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
```
In net/ethernet/eth.c (ffffffff81b0cc45)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81c6c5de)
Location: include/linux/etherdevice.h:191
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
In net/ethernet/eth.c (ffffffff81c939da)
Location: include/linux/etherdevice.h:198
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81e10550)
Location: include/linux/etherdevice.h:198
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
In net/ethernet/eth.c (ffffffff81e4f11a)
Location: include/linux/etherdevice.h:198
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81fe6c40)
Location: include/linux/etherdevice.h:198
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
In net/ethernet/eth.c (ffffffff81eaa7ba)
Location: include/linux/etherdevice.h:198
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82062b59)
Location: include/linux/etherdevice.h:198
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
In net/ethernet/eth.c (ffffffff81f6d26a)
Location: include/linux/etherdevice.h:198
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff82135ca5)
Location: include/linux/etherdevice.h:198
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
In drivers/base/property.c (ffff8000108f2b40)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e42ac)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_probe
```
```
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e9274)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fb818)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_probe
```
```
In drivers/of/of_net.c (ffff800010b756b8)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/ethernet/eth.c (ffff800010c36a80)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffff800010d75f54)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (c09df780)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In drivers/net/ethernet/freescale/fec_main.c (c0aca4bc)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_init
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad56a8)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_probe
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_set_mac_address
```
```
In drivers/of/of_net.c (c0c57ad0)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/ethernet/eth.c (c0d493e8)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (c0e72010)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (c00000000098d65c)
Location: include/linux/etherdevice.h:191
Inline: True
```
```
In drivers/of/of_net.c (c000000000c52c50)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/ethernet/eth.c (c000000000d2ec3c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (c000000000eb65b8)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffe000584ecc)
Location: include/linux/etherdevice.h:191
Inline: True
```
```
In drivers/of/of_net.c (ffffffe000728db6)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/of/of_net.c:of_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffe0007a8468)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffe0008a68dc)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff816cb62c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff8192b8f5)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a43bd8)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff816a695c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In drivers/net/vxlan.c (ffffffff8176b45c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_validate
```
```
In net/ethernet/eth.c (ffffffff818e56a5)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81a007c8)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff816f9b9c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff8197ca85)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81aafa88)
Location: include/linux/etherdevice.h:191
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
In drivers/base/property.c (ffffffff8171443c)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - drivers/base/property.c:fwnode_get_mac_addr
```
```
In net/ethernet/eth.c (ffffffff8199efe5)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
  - net/ethernet/eth.c:eth_validate_addr
  - net/ethernet/eth.c:eth_mac_addr
```
```
In net/ncsi/ncsi-rsp.c (ffffffff81abbe38)
Location: include/linux/etherdevice.h:191
Inline: True
Inline callers:
  - net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_oem_bcm
```
</details>
</li>
</ul>

## Differences
