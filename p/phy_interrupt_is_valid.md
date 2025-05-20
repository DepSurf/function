# Function: <code>phy_interrupt_is_valid</code>

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
In drivers/net/phy/phy.c (0)
Location: include/linux/phy.h:675
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:675
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
In drivers/net/phy/phy.c (ffffffff81649450)
Location: include/linux/phy.h:670
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/phy/phy_device.c (ffffffff81649a9b)
Location: include/linux/phy.h:670
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
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
In drivers/net/phy/phy.c (ffffffff8167a7f3)
Location: include/linux/phy.h:705
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/phy/phy_device.c (ffffffff8167ad7a)
Location: include/linux/phy.h:705
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
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
In drivers/net/phy/phy.c (ffffffff8168f256)
Location: include/linux/phy.h:717
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/phy/phy_device.c (ffffffff8168fd8a)
Location: include/linux/phy.h:717
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
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
In drivers/net/phy/phy.c (ffffffff816f8e3e)
Location: include/linux/phy.h:739
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
```
In drivers/net/phy/phy_device.c (ffffffff816f9a4a)
Location: include/linux/phy.h:739
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
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
In drivers/net/phy/phy.c (ffffffff81735b7d)
Location: include/linux/phy.h:822
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
  - drivers/net/phy/phy.c:phy_stop
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_change
```
```
In drivers/net/phy/phy_device.c (ffffffff817375ca)
Location: include/linux/phy.h:822
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
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
In drivers/net/phy/phy.c (ffffffff81757d76)
Location: include/linux/phy.h:813
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_start
```
```
In drivers/net/phy/phy_device.c (ffffffff8175c6c5)
Location: include/linux/phy.h:813
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff8179989b)
Location: include/linux/phy.h:913
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff817bd3bb)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (ffffffff81884eab)
Location: include/linux/phy.h:1071
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81893973)
Location: include/linux/phy.h:1200
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81876551)
Location: include/linux/phy.h:1220
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81907161)
Location: include/linux/phy.h:1228
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
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
In drivers/net/phy/phy_device.c (ffffffff81a5a399)
Location: include/linux/phy.h:1272
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
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
In drivers/net/phy/phy_device.c (ffffffff81be522c)
Location: include/linux/phy.h:1310
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81c3c79f)
Location: include/linux/phy.h:1469
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy_device.c (ffffffff81cf1b9f)
Location: include/linux/phy.h:1510
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
  - drivers/net/phy/phy_device.c:phy_connect
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
  - drivers/net/phy/phy_device.c:mdio_bus_phy_suspend
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
In drivers/net/phy/phy_device.c (ffff8000109d6274)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (c0abdce4)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (c000000000a97a80)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (ffffffe000622672)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (ffffffff81781e8b)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (ffffffff81761c1b)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (ffffffff817b223b)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
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
In drivers/net/phy/phy_device.c (ffffffff817cc1cb)
Location: include/linux/phy.h:920
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_probe
  - drivers/net/phy/phy_device.c:phy_disconnect
```
</details>
</li>
</ul>

## Differences
