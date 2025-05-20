# Function: <code>mii_adv_to_ethtool_adv_t</code>

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
In drivers/net/phy/phy.c (ffffffff815e9d03)
Location: include/linux/mii.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy_device.c (ffffffff815eb99b)
Location: include/linux/mii.h:136
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
In drivers/net/phy/phy.c (ffffffff81648671)
Location: include/linux/mii.h:136
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy_device.c (ffffffff8164a76f)
Location: include/linux/mii.h:136
Inline: True
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
In drivers/net/phy/phy.c (ffffffff816797e1)
Location: include/linux/mii.h:140
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy_device.c (ffffffff8167be1f)
Location: include/linux/mii.h:140
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8168eb09)
Location: include/linux/mii.h:140
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff8168f6d7)
Location: include/linux/mii.h:140
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff81690d5f)
Location: include/linux/mii.h:140
Inline: True
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
In drivers/net/phy/phy.c (ffffffff816f85fc)
Location: include/linux/mii.h:141
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff816f9167)
Location: include/linux/mii.h:141
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff816fab6f)
Location: include/linux/mii.h:141
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8173584a)
Location: include/linux/mii.h:141
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_mii_ioctl
```
```
In drivers/net/phy/phy-c45.c (ffffffff817362e7)
Location: include/linux/mii.h:141
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_read_lpa
```
```
In drivers/net/phy/phy_device.c (ffffffff81737eb6)
Location: include/linux/mii.h:141
Inline: True
```
</details>
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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/mii.c (ffff8000109cedd4)
Location: include/linux/mii.h:170
Inline: True
Inline callers:
  - drivers/net/mii.c:mii_get_an
```
</details>
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
