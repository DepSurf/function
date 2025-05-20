# Function: <code>phy_is_started</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:681
Inline: True
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:673
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:673
Inline: True
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:679
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:679
Inline: True
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
In drivers/net/phy/phy.c (ffffffff818809db)
Location: include/linux/phy.h:784
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81884705)
Location: include/linux/phy.h:784
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff8188f19b)
Location: include/linux/phy.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81892ec5)
Location: include/linux/phy.h:917
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff81871adb)
Location: include/linux/phy.h:937
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff818759d5)
Location: include/linux/phy.h:937
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff819021eb)
Location: include/linux/phy.h:945
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:_phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff819064e5)
Location: include/linux/phy.h:945
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff81a5410b)
Location: include/linux/phy.h:989
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:_phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81a592b5)
Location: include/linux/phy.h:989
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff81bdd92b)
Location: include/linux/phy.h:1027
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:_phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81be3085)
Location: include/linux/phy.h:1027
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff81c345dd)
Location: include/linux/phy.h:1183
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:_phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3af85)
Location: include/linux/phy.h:1183
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffff81ce8a3d)
Location: include/linux/phy.h:1224
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_ethtool_ksettings_set
  - drivers/net/phy/phy.c:_phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81cefbb5)
Location: include/linux/phy.h:1224
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:679
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:679
Inline: True
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
In drivers/net/phy/phy.c (c0ab9e00)
Location: include/linux/phy.h:679
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (c0abc64c)
Location: include/linux/phy.h:679
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (c000000000a918f0)
Location: include/linux/phy.h:679
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (c000000000a95378)
Location: include/linux/phy.h:679
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (ffffffe00061e5d2)
Location: include/linux/phy.h:679
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop_machine
  - drivers/net/phy/phy.c:phy_start_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffe000620d36)
Location: include/linux/phy.h:679
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:679
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:679
Inline: True
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:679
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:679
Inline: True
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:679
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:679
Inline: True
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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:679
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:679
Inline: True
```
</details>
</li>
</ul>

## Differences
