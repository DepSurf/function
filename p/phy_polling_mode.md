# Function: <code>phy_polling_mode</code>

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
Location: include/linux/phy.h:823
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
Location: include/linux/phy.h:923
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:923
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:923
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
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:930
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
In drivers/net/phy/phy.c (ffffffff818807fc)
Location: include/linux/phy.h:1081
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81880c00)
Location: include/linux/phy.h:1081
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff81882d7e)
Location: include/linux/phy.h:1081
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff8188efbc)
Location: include/linux/phy.h:1210
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188f330)
Location: include/linux/phy.h:1210
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff8189148e)
Location: include/linux/phy.h:1210
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff818718fc)
Location: include/linux/phy.h:1230
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81871c71)
Location: include/linux/phy.h:1230
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff81873d3e)
Location: include/linux/phy.h:1230
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff81902068)
Location: include/linux/phy.h:1238
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902817)
Location: include/linux/phy.h:1238
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff819046de)
Location: include/linux/phy.h:1238
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff81a53f11)
Location: include/linux/phy.h:1282
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a54883)
Location: include/linux/phy.h:1282
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5749e)
Location: include/linux/phy.h:1282
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff81bdd701)
Location: include/linux/phy.h:1320
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bdde03)
Location: include/linux/phy.h:1320
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff81be138e)
Location: include/linux/phy.h:1320
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff81c343e4)
Location: include/linux/phy.h:1479
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c34a6a)
Location: include/linux/phy.h:1479
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff81c38bce)
Location: include/linux/phy.h:1479
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffff81ce8892)
Location: include/linux/phy.h:1520
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:_phy_state_machine
  - drivers/net/phy/phy.c:phy_start_cable_test_tdr
  - drivers/net/phy/phy.c:phy_start_cable_test
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ce996a)
Location: include/linux/phy.h:1520
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffff81cedf5e)
Location: include/linux/phy.h:1520
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:930
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
In drivers/net/phy/phy.c (c0ab9db0)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
```
In drivers/net/phy/phy-c45.c (c0aba2cc)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (c0abc194)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (c000000000a9181c)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
```
In drivers/net/phy/phy-c45.c (c000000000a91fe0)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (c000000000a94c4c)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
In drivers/net/phy/phy.c (ffffffe00061e5ac)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061e7ac)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_link
```
```
In drivers/net/phy/phy_device.c (ffffffe000620896)
Location: include/linux/phy.h:930
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_update_link
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
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:930
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
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:930
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
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:930
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
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy-c45.c (0)
Location: include/linux/phy.h:930
Inline: True
```
```
In drivers/net/phy/phy_device.c (0)
Location: include/linux/phy.h:930
Inline: True
```
</details>
</li>
</ul>

## Differences
