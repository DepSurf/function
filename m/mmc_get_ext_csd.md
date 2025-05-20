# Function: <code>mmc_get_ext_csd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff816c5a50)
Location: drivers/mmc/core/mmc_ops.c:393
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
```
**Symbols:**

```
ffffffff816c5a50-ffffffff816c5afb: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817288d0)
Location: drivers/mmc/core/mmc_ops.c:383
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
```
**Symbols:**

```
ffffffff817288d0-ffffffff81728979: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8175b850)
Location: drivers/mmc/core/mmc_ops.c:358
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_read_bkops_status
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
```
**Symbols:**

```
ffffffff8175b850-ffffffff8175b8f9: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81779d20)
Location: drivers/mmc/core/mmc_ops.c:353
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/debugfs.c:mmc_ext_csd_open
```
**Symbols:**

```
ffffffff81779d20-ffffffff81779dc9: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0190)
Location: drivers/mmc/core/mmc_ops.c:354
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff817f0190-ffffffff817f0239: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818394a0)
Location: drivers/mmc/core/mmc_ops.c:354
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818394a0-ffffffff81839523: mmc_get_ext_csd.part.4 (STB_LOCAL)
ffffffff81839530-ffffffff8183955f: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818654d0)
Location: drivers/mmc/core/mmc_ops.c:354
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818654d0-ffffffff81865553: mmc_get_ext_csd.part.4 (STB_LOCAL)
ffffffff81865560-ffffffff8186558f: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a93c0)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818a93c0-ffffffff818a9442: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffffffff818a9450-ffffffff818a947f: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818db800)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818db800-ffffffff818db882: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffffffff818db890-ffffffff818db8bf: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819ae4d0)
Location: drivers/mmc/core/mmc_ops.c:358
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
```
**Symbols:**

```
ffffffff819ae4d0-ffffffff819ae57b: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b0b30)
Location: drivers/mmc/core/mmc_ops.c:358
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
```
**Symbols:**

```
ffffffff819b0b30-ffffffff819b0bdb: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995410)
Location: drivers/mmc/core/mmc_ops.c:337
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
```
**Symbols:**

```
ffffffff81995410-ffffffff819954bb: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a416a0)
Location: drivers/mmc/core/mmc_ops.c:341
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
```
**Symbols:**

```
ffffffff81a416a0-ffffffff81a4174d: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81baec90)
Location: drivers/mmc/core/mmc_ops.c:370
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
```
**Symbols:**

```
ffffffff81baec90-ffffffff81baed77: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81d525d0)
Location: drivers/mmc/core/mmc_ops.c:370
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
```
**Symbols:**

```
ffffffff81d525d0-ffffffff81d526b7: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81dbcfe0)
Location: drivers/mmc/core/mmc_ops.c:370
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
```
**Symbols:**

```
ffffffff81dbcfe0-ffffffff81dbd0c7: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81e755e0)
Location: drivers/mmc/core/mmc_ops.c:370
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_compare_ext_csds
```
**Symbols:**

```
ffffffff81e755e0-ffffffff81e756f6: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b35660)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffff800010b35660-ffff800010b356f8: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffff800010b356f8-ffff800010b35750: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10110)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
c0c10110-c0c101a0: mmc_get_ext_csd.part.0 (STB_LOCAL)
c0c101a0-c0c101e4: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c306a0)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
c000000000c306a0-c000000000c30774: mmc_get_ext_csd.part.0 (STB_LOCAL)
c000000000c30780-c000000000c307c0: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070db84)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffffffe00070db84-ffffffe00070dc0a: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffffffe00070dc0a-ffffffe00070dc54: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187f1c0)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff8187f1c0-ffffffff8187f242: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffffffff8187f250-ffffffff8187f27f: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d0660)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818d0660-ffffffff818d06e2: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffffffff818d06f0-ffffffff818d071f: mmc_get_ext_csd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_get_ext_csd(struct mmc_card *card, u8 **new_ext_csd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818ed180)
Location: drivers/mmc/core/mmc_ops.c:356
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_bus_width
```
**Symbols:**

```
ffffffff818ed180-ffffffff818ed202: mmc_get_ext_csd.part.0 (STB_LOCAL)
ffffffff818ed210-ffffffff818ed23f: mmc_get_ext_csd (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
