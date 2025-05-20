# Function: <code>mmc_manage_gp_partitions</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c2e34)
Location: drivers/mmc/core/mmc.c:292
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81725c15)
Location: drivers/mmc/core/mmc.c:308
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81758ad3)
Location: drivers/mmc/core/mmc.c:310
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8177761a)
Location: drivers/mmc/core/mmc.c:314
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817eda2f)
Location: drivers/mmc/core/mmc.c:314
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81836ab4)
Location: drivers/mmc/core/mmc.c:314
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81862adc)
Location: drivers/mmc/core/mmc.c:315
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff818a6cb1)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff818d9111)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mmc_manage_gp_partitions(struct mmc_card *card, u8 *ext_csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:312
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
**Symbols:**

```
ffffffff819aba00-ffffffff819abb17: mmc_manage_gp_partitions (STB_LOCAL)
ffffffff819ad70e-ffffffff819ad732: mmc_manage_gp_partitions.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mmc_manage_gp_partitions(struct mmc_card *card, u8 *ext_csd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:312
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
**Symbols:**

```
ffffffff819ae5b0-ffffffff819ae6c7: mmc_manage_gp_partitions (STB_LOCAL)
ffffffff81c2a8a3-ffffffff81c2a8c7: mmc_manage_gp_partitions.cold (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffffffff81993140)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff81a3ebbe)
Location: drivers/mmc/core/mmc.c:313
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff81babf04)
Location: drivers/mmc/core/mmc.c:321
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff81d4f34c)
Location: drivers/mmc/core/mmc.c:321
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff81db9c79)
Location: drivers/mmc/core/mmc.c:321
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff81e720de)
Location: drivers/mmc/core/mmc.c:333
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffff800010b336b0)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (c0c0e1d4)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (c000000000c2dcf8)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffe00070bd48)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff8187cad1)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818cdf71)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
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
In drivers/mmc/core/mmc.c (ffffffff818eaa91)
Location: drivers/mmc/core/mmc.c:312
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
