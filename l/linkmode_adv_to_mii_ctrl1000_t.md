# Function: <code>linkmode_adv_to_mii_ctrl1000_t</code>

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
In drivers/net/phy/phy_device.c (ffffffff817bc80c)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81884065)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff8188940c)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81892795)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff8189767c)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81874f55)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff81879f3d)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81905a25)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff8190afe2)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81a5a766)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
```
```
In drivers/net/phy/bcm84881.c (ffffffff81a5e4ed)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81be46d8)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff81be922c)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81c3c36d)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff81c41655)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff81cf176d)
Location: include/linux/mii.h:218
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
```
```
In drivers/net/phy/bcm84881.c (ffffffff81cf6ce5)
Location: include/linux/mii.h:218
Inline: True
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
In drivers/net/phy/phy_device.c (ffff8000109d5828)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (c0abd318)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (c000000000a96788)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffe0006219c0)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff817812dc)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff8176106c)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff817b168c)
Location: include/linux/mii.h:218
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
In drivers/net/phy/phy_device.c (ffffffff817cb61c)
Location: include/linux/mii.h:218
Inline: True
```
</details>
</li>
</ul>

## Differences
