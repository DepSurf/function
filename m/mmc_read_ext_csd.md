# Function: <code>mmc_read_ext_csd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_read_ext_csd(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c2950)
Location: drivers/mmc/core/mmc.c:593
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff816c2950-ffffffff816c33be: mmc_read_ext_csd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_read_ext_csd(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817256e0)
Location: drivers/mmc/core/mmc.c:622
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff817256e0-ffffffff817261c6: mmc_read_ext_csd (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffffffff81759b87)
Location: drivers/mmc/core/mmc.c:643
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
In drivers/mmc/core/mmc.c (ffffffff81778290)
Location: drivers/mmc/core/mmc.c:659
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
In drivers/mmc/core/mmc.c (ffffffff817ee68d)
Location: drivers/mmc/core/mmc.c:659
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
In drivers/mmc/core/mmc.c (ffffffff81837bc1)
Location: drivers/mmc/core/mmc.c:659
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
In drivers/mmc/core/mmc.c (ffffffff81863b95)
Location: drivers/mmc/core/mmc.c:659
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
In drivers/mmc/core/mmc.c (ffffffff818a7ccd)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818da134)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_read_ext_csd(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:658
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff819ac600-ffffffff819ac694: mmc_read_ext_csd (STB_LOCAL)
ffffffff819ad77d-ffffffff819ad7cd: mmc_read_ext_csd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_read_ext_csd(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:665
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff819af1d0-ffffffff819af264: mmc_read_ext_csd (STB_LOCAL)
ffffffff81c2a913-ffffffff81c2a963: mmc_read_ext_csd.cold (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffffffff81994102)
Location: drivers/mmc/core/mmc.c:665
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
In drivers/mmc/core/mmc.c (ffffffff81a3fe05)
Location: drivers/mmc/core/mmc.c:668
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
In drivers/mmc/core/mmc.c (ffffffff81bad094)
Location: drivers/mmc/core/mmc.c:676
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
In drivers/mmc/core/mmc.c (ffffffff81d5056e)
Location: drivers/mmc/core/mmc.c:676
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
In drivers/mmc/core/mmc.c (ffffffff81dbaf35)
Location: drivers/mmc/core/mmc.c:676
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
In drivers/mmc/core/mmc.c (ffffffff81e73231)
Location: drivers/mmc/core/mmc.c:682
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
In drivers/mmc/core/mmc.c (ffff800010b344fc)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (c0c0eeb4)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (c000000000c2ebf0)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffe00070c9b2)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff8187daf4)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818cef94)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818ebab4)
Location: drivers/mmc/core/mmc.c:656
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
