# Function: <code>to_mdio_device</code>

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
In drivers/net/phy/phy_device.c (ffffffff81874175)
Location: include/linux/mdio.h:53
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_shutdown
  - drivers/net/phy/phy_device.c:phy_remove
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_standalone_show
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/net/phy/phy_device.c:phy_dev_flags_show
  - drivers/net/phy/phy_device.c:phy_has_fixups_show
  - drivers/net/phy/phy_device.c:phy_interface_show
  - drivers/net/phy/phy_device.c:phy_id_show
  - drivers/net/phy/phy_device.c:phy_device_release
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81876f35)
Location: include/linux/mdio.h:53
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_match
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
```
```
In drivers/net/phy/mdio_device.c (ffffffff81877fe5)
Location: include/linux/mdio.h:53
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_remove
  - drivers/net/phy/mdio_device.c:mdio_probe
  - drivers/net/phy/mdio_device.c:mdio_device_bus_match
  - drivers/net/phy/mdio_device.c:mdio_device_release
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
In drivers/net/phy/phy_device.c (ffffffff81904b35)
Location: include/linux/mdio.h:53
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_shutdown
  - drivers/net/phy/phy_device.c:phy_remove
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_standalone_show
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/net/phy/phy_device.c:phy_dev_flags_show
  - drivers/net/phy/phy_device.c:phy_has_fixups_show
  - drivers/net/phy/phy_device.c:phy_interface_show
  - drivers/net/phy/phy_device.c:phy_id_show
  - drivers/net/phy/phy_device.c:phy_device_release
```
```
In drivers/net/phy/mdio_bus.c (ffffffff81907b95)
Location: include/linux/mdio.h:53
Inline: True
Inline callers:
  - drivers/net/phy/mdio_bus.c:mdio_bus_match
  - drivers/net/phy/mdio_bus.c:mdio_bus_device_stat_field_show
```
```
In drivers/net/phy/mdio_device.c (ffffffff81908ca5)
Location: include/linux/mdio.h:53
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_shutdown
  - drivers/net/phy/mdio_device.c:mdio_remove
  - drivers/net/phy/mdio_device.c:mdio_probe
  - drivers/net/phy/mdio_device.c:mdio_device_bus_match
  - drivers/net/phy/mdio_device.c:mdio_device_release
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
Location: include/linux/mdio.h:55
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:55
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:55
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
Location: include/linux/mdio.h:55
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:55
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:55
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
Location: include/linux/mdio.h:47
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:47
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:47
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
Location: include/linux/mdio.h:48
Inline: True
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/mdio.h:48
Inline: True
```
```
In drivers/net/phy/mdio_device.c (0)
Location: include/linux/mdio.h:48
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
