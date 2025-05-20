# Function: <code>mmc_flush_cache</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be4f0)
Location: drivers/mmc/core/core.c:2744
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff816be4f0-ffffffff816be568: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81720460)
Location: drivers/mmc/core/core.c:2807
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81720460-ffffffff817204d8: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81752cf0)
Location: drivers/mmc/core/core.c:2902
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81752cf0-ffffffff81752d68: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a880)
Location: drivers/mmc/core/mmc_ops.c:1016
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff8177a880-ffffffff8177a907: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0cd0)
Location: drivers/mmc/core/mmc_ops.c:1015
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff817f0cd0-ffffffff817f0d57: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:1011
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff8183a54e-ffffffff8183a574: mmc_flush_cache.cold.10 (STB_LOCAL)
ffffffff81839fe0-ffffffff8183a04c: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81866084)
Location: drivers/mmc/core/mmc_ops.c:954
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff818664ea-ffffffff81866510: mmc_flush_cache.cold.10 (STB_LOCAL)
ffffffff81866030-ffffffff8186609c: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a9e98)
Location: drivers/mmc/core/mmc_ops.c:956
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff818aa32d-ffffffff818aa353: mmc_flush_cache.cold (STB_LOCAL)
ffffffff818a9e60-ffffffff818a9ed1: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc2e8)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff818dc77d-ffffffff818dc7a3: mmc_flush_cache.cold (STB_LOCAL)
ffffffff818dc2b0-ffffffff818dc321: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819aef18)
Location: drivers/mmc/core/mmc_ops.c:987
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff819af337-ffffffff819af35d: mmc_flush_cache.cold (STB_LOCAL)
ffffffff819aeee0-ffffffff819aef51: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b1578)
Location: drivers/mmc/core/mmc_ops.c:987
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81c2ac50-ffffffff81c2ac76: mmc_flush_cache.cold (STB_LOCAL)
ffffffff819b1540-ffffffff819b15b1: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995f2a)
Location: drivers/mmc/core/mmc_ops.c:967
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81c1d11e-ffffffff81c1d144: mmc_flush_cache.cold (STB_LOCAL)
ffffffff81995ef0-ffffffff81995f61: mmc_flush_cache (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b363d0)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffff800010b363d0-ffff800010b36474: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10e88)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
c0c10e88-c0c10f28: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c31590)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
c000000000c31590-c000000000c31674: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e59a)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
```
**Symbols:**

```
ffffffe00070e59a-ffffffe00070e614: mmc_flush_cache (STB_GLOBAL)
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
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187fca8)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff8188013d-ffffffff81880163: mmc_flush_cache.cold (STB_LOCAL)
ffffffff8187fc70-ffffffff8187fce1: mmc_flush_cache (STB_GLOBAL)
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
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d1148)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff818d15dd-ffffffff818d1603: mmc_flush_cache.cold (STB_LOCAL)
ffffffff818d1110-ffffffff818d1181: mmc_flush_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_flush_cache(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818edc68)
Location: drivers/mmc/core/mmc_ops.c:958
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff818ee0fd-ffffffff818ee123: mmc_flush_cache.cold (STB_LOCAL)
ffffffff818edc30-ffffffff818edca1: mmc_flush_cache (STB_GLOBAL)
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
