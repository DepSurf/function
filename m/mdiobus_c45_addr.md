# Function: <code>mdiobus_c45_addr</code>

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
In drivers/net/phy/phy.c (ffffffff8187fa01)
Location: include/linux/mdio.h:336
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-core.c (ffffffff818818c2)
Location: include/linux/mdio.h:336
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
```
In drivers/net/phy/phy_device.c (ffffffff81882cb5)
Location: include/linux/mdio.h:336
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
In drivers/net/phy/phy.c (ffffffff8188e2b1)
Location: include/linux/mdio.h:337
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-core.c (ffffffff8188fff2)
Location: include/linux/mdio.h:337
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
```
In drivers/net/phy/phy_device.c (ffffffff81893453)
Location: include/linux/mdio.h:337
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
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
In drivers/net/phy/phy.c (ffffffff81870ae5)
Location: include/linux/mdio.h:350
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-core.c (ffffffff818728f2)
Location: include/linux/mdio.h:350
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
```
In drivers/net/phy/phy_device.c (ffffffff81876034)
Location: include/linux/mdio.h:350
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
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
In drivers/net/phy/phy.c (ffffffff8190118d)
Location: include/linux/mdio.h:353
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-core.c (ffffffff81903002)
Location: include/linux/mdio.h:353
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
```
In drivers/net/phy/phy_device.c (ffffffff81906bb4)
Location: include/linux/mdio.h:353
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:get_phy_c45_ids
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
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
In drivers/net/phy/phy.c (ffffffff81a52c03)
Location: include/linux/mdio.h:451
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-core.c (ffffffff81a55abe)
Location: include/linux/mdio.h:451
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
```
In drivers/net/phy/phy_device.c (ffffffff81a57335)
Location: include/linux/mdio.h:451
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
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
In drivers/net/phy/phy.c (ffffffff81bdcd53)
Location: include/linux/mdio.h:451
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-core.c (ffffffff81bdf59e)
Location: include/linux/mdio.h:451
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:__phy_write_mmd
```
```
In drivers/net/phy/phy_device.c (ffffffff81be11f5)
Location: include/linux/mdio.h:451
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_c45_probe_present
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
