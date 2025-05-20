# Function: <code>netif_testing_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188094b)
Location: include/linux/netdevice.h:3963
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff819fffad)
Location: include/linux/netdevice.h:3963
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81a83b1a)
Location: include/linux/netdevice.h:3963
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff8188f10b)
Location: include/linux/netdevice.h:4131
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff819fffed)
Location: include/linux/netdevice.h:4131
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81a8d64a)
Location: include/linux/netdevice.h:4131
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff81871a4b)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff819e654d)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81a761ba)
Location: include/linux/netdevice.h:4261
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff81902187)
Location: include/linux/netdevice.h:4284
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81a96a7d)
Location: include/linux/netdevice.h:4284
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81b307fa)
Location: include/linux/netdevice.h:4284
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff81a54092)
Location: include/linux/netdevice.h:4148
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81c0d94f)
Location: include/linux/netdevice.h:4148
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81cbb696)
Location: include/linux/netdevice.h:4148
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff81bdd88d)
Location: include/linux/netdevice.h:4192
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81dc10bf)
Location: include/linux/netdevice.h:4192
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81e79c26)
Location: include/linux/netdevice.h:4192
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff81c344a1)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81e30d0f)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81ed5f26)
Location: include/linux/netdevice.h:4251
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
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
In drivers/net/phy/phy.c (ffffffff81ce8b0f)
Location: include/linux/netdevice.h:4327
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81eef2a2)
Location: include/linux/netdevice.h:4327
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81f99a89)
Location: include/linux/netdevice.h:4327
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_self_test
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
