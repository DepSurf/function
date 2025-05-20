# Function: <code>mmc_read_ssr</code>

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
In drivers/mmc/core/sd.c (ffffffff816c723b)
Location: drivers/mmc/core/sd.c:225
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
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
In drivers/mmc/core/sd.c (ffffffff8172a224)
Location: drivers/mmc/core/sd.c:223
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
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
In drivers/mmc/core/sd.c (ffffffff8175d324)
Location: drivers/mmc/core/sd.c:223
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
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
In drivers/mmc/core/sd.c (ffffffff8177bab5)
Location: drivers/mmc/core/sd.c:225
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff817f24ed)
Location: drivers/mmc/core/sd.c:225
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff8183b71a)
Location: drivers/mmc/core/sd.c:225
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff818676aa)
Location: drivers/mmc/core/sd.c:225
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
In drivers/mmc/core/sd.c (ffffffff818ab52d)
Location: drivers/mmc/core/sd.c:235
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
In drivers/mmc/core/sd.c (ffffffff818dd97d)
Location: drivers/mmc/core/sd.c:235
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:235
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff819afbc0-ffffffff819afcdd: mmc_read_ssr (STB_LOCAL)
ffffffff819b0fed-ffffffff819b1064: mmc_read_ssr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:235
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff819b2130-ffffffff819b224d: mmc_read_ssr (STB_LOCAL)
ffffffff81c2ae3d-ffffffff81c2aeb4: mmc_read_ssr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:241
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81996960-ffffffff81996a7d: mmc_read_ssr (STB_LOCAL)
ffffffff81c1d1b6-ffffffff81c1d22d: mmc_read_ssr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:251
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81a428c0-ffffffff81a42a0e: mmc_read_ssr (STB_LOCAL)
ffffffff81d2e087-ffffffff81d2e100: mmc_read_ssr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:260
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81bb0190-ffffffff81bb02e1: mmc_read_ssr (STB_LOCAL)
ffffffff81efa4bf-ffffffff81efa532: mmc_read_ssr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d53e80)
Location: drivers/mmc/core/sd.c:260
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81d53e80-ffffffff81d54048: mmc_read_ssr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbe810)
Location: drivers/mmc/core/sd.c:260
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81dbe810-ffffffff81dbe9d5: mmc_read_ssr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_read_ssr(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e76e40)
Location: drivers/mmc/core/sd.c:260
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
```
**Symbols:**

```
ffffffff81e76e40-ffffffff81e77034: mmc_read_ssr (STB_LOCAL)
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
In drivers/mmc/core/sd.c (ffff800010b37c68)
Location: drivers/mmc/core/sd.c:235
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
In drivers/mmc/core/sd.c (c0c12594)
Location: drivers/mmc/core/sd.c:235
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
In drivers/mmc/core/sd.c (c000000000c3365c)
Location: drivers/mmc/core/sd.c:235
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
In drivers/mmc/core/sd.c (ffffffe00070fbb6)
Location: drivers/mmc/core/sd.c:235
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
In drivers/mmc/core/sd.c (ffffffff8188133d)
Location: drivers/mmc/core/sd.c:235
Inline: True
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
In drivers/mmc/core/sd.c (ffffffff818d27dd)
Location: drivers/mmc/core/sd.c:235
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
In drivers/mmc/core/sd.c (ffffffff818ef2fd)
Location: drivers/mmc/core/sd.c:235
Inline: True
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
