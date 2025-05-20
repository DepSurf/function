# Function: <code>mii_stat1000_mod_linkmode_lpa_t</code>

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
In drivers/net/phy/phy_device.c (ffffffff8175c224)
Location: include/linux/mii.h:299
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff817994ea)
Location: include/linux/mii.h:299
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff817bcea6)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (ffffffff81883b71)
Location: include/linux/mii.h:299
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff818892a8)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (ffffffff8189229f)
Location: include/linux/mii.h:299
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff81897518)
Location: include/linux/mii.h:299
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff818748e9)
Location: include/linux/mii.h:299
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879d33)
Location: include/linux/mii.h:299
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff81905339)
Location: include/linux/mii.h:299
Inline: True
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190adba)
Location: include/linux/mii.h:299
Inline: True
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
In drivers/net/phy/phy_device.c (ffffffff81a58802)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e767)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy_device.c (ffffffff81be4c50)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be9507)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy_device.c (ffffffff81c3ca73)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c4191f)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy_device.c (ffffffff81cf1e73)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6faf)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/bcm84881.c:bcm84881_read_status
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
In drivers/net/phy/phy_device.c (ffff8000109d5e3c)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (c0abd828)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (c000000000a96bc8)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
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
In drivers/net/phy/phy_device.c (ffffffe000622240)
Location: include/linux/mii.h:299
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_read_lpa
  - drivers/net/phy/phy_device.c:genphy_read_lpa
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
In drivers/net/phy/phy_device.c (ffffffff81781976)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (ffffffff81761706)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (ffffffff817b1d26)
Location: include/linux/mii.h:299
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
In drivers/net/phy/phy_device.c (ffffffff817cbcb6)
Location: include/linux/mii.h:299
Inline: True
```
</details>
</li>
</ul>

## Differences
