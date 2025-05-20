# Function: <code>mmc_select_hs</code>

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
In drivers/mmc/core/mmc.c (ffffffff816c38e4)
Location: drivers/mmc/core/mmc.c:958
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_select_hs(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81726800)
Location: drivers/mmc/core/mmc.c:1019
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81726800-ffffffff81726861: mmc_select_hs (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffffffff81759657)
Location: drivers/mmc/core/mmc.c:1027
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff8177876b)
Location: drivers/mmc/core/mmc.c:1051
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff817eeb69)
Location: drivers/mmc/core/mmc.c:1053
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818374ff)
Location: drivers/mmc/core/mmc.c:1055
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818634cf)
Location: drivers/mmc/core/mmc.c:1055
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818a6089)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff818d84d9)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff819ab5a9)
Location: drivers/mmc/core/mmc.c:1057
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff819ae149)
Location: drivers/mmc/core/mmc.c:1064
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff81993c1d)
Location: drivers/mmc/core/mmc.c:1064
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81a3f83e)
Location: drivers/mmc/core/mmc.c:1067
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81bace10)
Location: drivers/mmc/core/mmc.c:1074
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81d502e3)
Location: drivers/mmc/core/mmc.c:1074
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81dbaca8)
Location: drivers/mmc/core/mmc.c:1074
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81e72f84)
Location: drivers/mmc/core/mmc.c:1084
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffff800010b32aa8)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (c0c0d520)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (c000000000c2cd20)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffe00070b2be)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff8187be99)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff818cd339)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff818e9e59)
Location: drivers/mmc/core/mmc.c:1052
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
