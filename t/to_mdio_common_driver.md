# Function: <code>to_mdio_common_driver</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff818763d7)
Location: include/linux/mdio.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_loopback
```
```
In drivers/net/phy/mdio_device.c (ffffffff81877fe5)
Location: include/linux/mdio.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_remove
  - drivers/net/phy/mdio_device.c:mdio_probe
  - drivers/net/phy/mdio_device.c:mdio_device_bus_match
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
In drivers/net/phy/phy_device.c (ffffffff81906fe7)
Location: include/linux/mdio.h:66
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
```
In drivers/net/phy/mdio_device.c (ffffffff81908ca5)
Location: include/linux/mdio.h:66
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_shutdown
  - drivers/net/phy/mdio_device.c:mdio_remove
  - drivers/net/phy/mdio_device.c:mdio_probe
  - drivers/net/phy/mdio_device.c:mdio_device_bus_match
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
In drivers/net/phy/phy_device.c (0)
Location: include/linux/mdio.h:68
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:68
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:68
Inline: True
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
In drivers/net/phy/phy_device.c (0)
Location: include/linux/mdio.h:68
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:68
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:68
Inline: True
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
In drivers/net/phy/phy_device.c (0)
Location: include/linux/mdio.h:60
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:60
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:60
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
In drivers/net/phy/phy_device.c (0)
Location: include/linux/mdio.h:61
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:61
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:61
Inline: True
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
