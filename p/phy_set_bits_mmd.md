# Function: <code>phy_set_bits_mmd</code>

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
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81794a86)
Location: include/linux/phy.h:886
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff81796585)
Location: include/linux/phy.h:886
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
In drivers/net/phy/phy.c (ffffffff817b8626)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff817b9f45)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (ffffffff8187fec4)
Location: include/linux/phy.h:1044
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff818814c2)
Location: include/linux/phy.h:1044
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
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
In drivers/net/phy/phy.c (ffffffff8188e774)
Location: include/linux/phy.h:1173
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff8188fbf2)
Location: include/linux/phy.h:1173
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
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
In drivers/net/phy/phy.c (ffffffff81871035)
Location: include/linux/phy.h:1193
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff818724e2)
Location: include/linux/phy.h:1193
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
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
In drivers/net/phy/phy.c (ffffffff81901715)
Location: include/linux/phy.h:1201
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff81902bf2)
Location: include/linux/phy.h:1201
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
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
In drivers/net/phy/phy.c (ffffffff81a53067)
Location: include/linux/phy.h:1245
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff81a546c0)
Location: include/linux/phy.h:1245
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_fast_retrain
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
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
In drivers/net/phy/phy.c (ffffffff81bdc1c7)
Location: include/linux/phy.h:1283
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff81bde1ef)
Location: include/linux/phy.h:1283
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
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
In drivers/net/phy/phy.c (ffffffff81c321ed)
Location: include/linux/phy.h:1442
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff81c34e2c)
Location: include/linux/phy.h:1442
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
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
In drivers/net/phy/phy.c (ffffffff81ce6edd)
Location: include/linux/phy.h:1483
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff81ce9d2c)
Location: include/linux/phy.h:1483
Inline: True
Inline callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_plca_set_cfg
  - drivers/net/phy/phy-c45.c:genphy_c45_check_and_restart_aneg
  - drivers/net/phy/phy-c45.c:genphy_c45_pma_suspend
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
In drivers/net/phy/phy.c (ffff8000109d1a44)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffff8000109d20f8)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (c0ab9c30)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (c0aba288)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (c000000000a90ce0)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (c000000000a91f7c)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (ffffffe00061e424)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffe00061eaf0)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (ffffffff8177d0f6)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff8177ea15)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (ffffffff8175cea6)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff8175e7b5)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (ffffffff817ad4a6)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff817aedc5)
Location: include/linux/phy.h:893
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
In drivers/net/phy/phy.c (ffffffff817c7436)
Location: include/linux/phy.h:893
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
```
In drivers/net/phy/phy-c45.c (ffffffff817c8d55)
Location: include/linux/phy.h:893
Inline: True
```
</details>
</li>
</ul>

## Differences
