# Function: <code>linkmode_adv_to_mii_adv_t</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-c45.c (ffffffff81796300)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
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
In drivers/net/phy/phy-c45.c (ffffffff817b9cc0)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff817bc760)
Location: include/linux/mii.h:143
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
In drivers/net/phy/phy-c45.c (ffffffff818813a0)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81883fac)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffffffff8188fad0)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff818926dc)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffffffff81872380)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81874e9c)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffffffff81902a90)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff8190596c)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffffffff81a55091)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81a5a6bf)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:__genphy_config_aneg
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
In drivers/net/phy/phy-c45.c (ffffffff81bde411)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81be461a)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffffffff81c36539)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81c3c2aa)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffffffff81ceb4b9)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf16aa)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:genphy_config_advert
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
In drivers/net/phy/phy-c45.c (ffff8000109d1e24)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffff8000109d57a0)
Location: include/linux/mii.h:143
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
In drivers/net/phy/phy-c45.c (c0aba058)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (c0abd290)
Location: include/linux/mii.h:143
Inline: True
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
In drivers/net/phy/phy-c45.c (c000000000a91b28)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (c000000000a966d4)
Location: include/linux/mii.h:143
Inline: True
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
In drivers/net/phy/phy-c45.c (ffffffe00061e86e)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffe000621932)
Location: include/linux/mii.h:143
Inline: True
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
In drivers/net/phy/phy-c45.c (ffffffff8177e790)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81781230)
Location: include/linux/mii.h:143
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
In drivers/net/phy/phy-c45.c (ffffffff8175e530)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff81760fc0)
Location: include/linux/mii.h:143
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
In drivers/net/phy/phy-c45.c (ffffffff817aeb40)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff817b15e0)
Location: include/linux/mii.h:143
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
In drivers/net/phy/phy-c45.c (ffffffff817c8ad0)
Location: include/linux/mii.h:143
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_an_config_aneg
```
```
In drivers/net/phy/phy_device.c (ffffffff817cb570)
Location: include/linux/mii.h:143
Inline: True
```
</details>
</li>
</ul>

## Differences
