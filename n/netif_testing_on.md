# Function: <code>netif_testing_on</code>

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
In drivers/net/phy/phy.c (ffffffff81880495)
Location: include/linux/netdevice.h:3951
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff819fffd6)
Location: include/linux/netdevice.h:3951
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81a83af6)
Location: include/linux/netdevice.h:3951
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
In drivers/net/phy/phy.c (ffffffff8188ed45)
Location: include/linux/netdevice.h:4119
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81a00016)
Location: include/linux/netdevice.h:4119
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81a8d626)
Location: include/linux/netdevice.h:4119
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
In drivers/net/phy/phy.c (ffffffff818714d7)
Location: include/linux/netdevice.h:4249
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff819e6576)
Location: include/linux/netdevice.h:4249
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81a76196)
Location: include/linux/netdevice.h:4249
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
In drivers/net/phy/phy.c (ffffffff81901bb7)
Location: include/linux/netdevice.h:4272
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81a96aa6)
Location: include/linux/netdevice.h:4272
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81b307d6)
Location: include/linux/netdevice.h:4272
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
In drivers/net/phy/phy.c (ffffffff81a534e7)
Location: include/linux/netdevice.h:4136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81c0d98c)
Location: include/linux/netdevice.h:4136
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81cbb673)
Location: include/linux/netdevice.h:4136
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
In drivers/net/phy/phy.c (ffffffff81bdc8b6)
Location: include/linux/netdevice.h:4180
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81dc10fc)
Location: include/linux/netdevice.h:4180
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81e79c03)
Location: include/linux/netdevice.h:4180
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
In drivers/net/phy/phy.c (ffffffff81c33c76)
Location: include/linux/netdevice.h:4239
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81e30d4c)
Location: include/linux/netdevice.h:4239
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81ed5f03)
Location: include/linux/netdevice.h:4239
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
In drivers/net/phy/phy.c (ffffffff81ce8e66)
Location: include/linux/netdevice.h:4315
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In net/core/dev.c (ffffffff81eef2e5)
Location: include/linux/netdevice.h:4315
Inline: True
Inline callers:
  - net/core/dev.c:netif_stacked_transfer_operstate
```
```
In net/ethtool/ioctl.c (ffffffff81f99a63)
Location: include/linux/netdevice.h:4315
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
