# Function: <code>bus_find_device_by_fwnode</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff81707851)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff817c2522)
Location: include/linux/device/bus.h:198
Inline: True
Inline callers:
  - drivers/base/devcon.c:device_connection_fwnode_match
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8190657e)
Location: include/linux/device/bus.h:198
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81a5936e)
Location: include/linux/device/bus.h:202
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81be30fe)
Location: include/linux/device/bus.h:202
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
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
In drivers/net/phy/phy_device.c (ffffffff81c3affe)
Location: include/linux/device/bus.h:182
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2a41e)
Location: include/linux/device/bus.h:182
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode
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
In drivers/net/phy/phy_device.c (ffffffff81cefc2e)
Location: include/linux/device/bus.h:177
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:fwnode_phy_find_device
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de02de)
Location: include/linux/device/bus.h:177
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_find_device_by_fwnode
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffff8000108f51c4)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (c09e1508)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (c00000000098f664)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffe000586484)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816ccfa1)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816a82d1)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff816fb511)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/devcon.c (ffffffff81715db1)
Location: include/linux/device.h:212
Inline: True
```
</details>
</li>
</ul>

## Differences
