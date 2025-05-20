# Function: <code>mmc_interrupt_hpi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bddc0)
Location: drivers/mmc/core/core.c:664
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff816bddc0-ffffffff816bdf7b: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8171f9d0)
Location: drivers/mmc/core/core.c:665
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff8171f9d0-ffffffff8171fb86: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81752260)
Location: drivers/mmc/core/core.c:740
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff81752260-ffffffff8175240b: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177aa20)
Location: drivers/mmc/core/mmc_ops.c:839
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc_ops.c:mmc_stop_bkops
```
**Symbols:**

```
ffffffff8177aa20-ffffffff8177ac9c: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f1010)
Location: drivers/mmc/core/mmc_ops.c:840
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc_ops.c:mmc_stop_bkops
```
**Symbols:**

```
ffffffff817f1010-ffffffff817f128e: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:840
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc_ops.c:mmc_stop_bkops
```
**Symbols:**

```
ffffffff8183a5b8-ffffffff8183a656: mmc_interrupt_hpi.cold.12 (STB_LOCAL)
ffffffff8183a2d0-ffffffff8183a478: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:834
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff8186654c-ffffffff818665c4: mmc_interrupt_hpi.cold.12 (STB_LOCAL)
ffffffff818662b0-ffffffff8186644b: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:836
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff818aa38f-ffffffff818aa406: mmc_interrupt_hpi.cold (STB_LOCAL)
ffffffff818aa0f0-ffffffff818aa28d: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff818dc7df-ffffffff818dc856: mmc_interrupt_hpi.cold (STB_LOCAL)
ffffffff818dc540-ffffffff818dc6dd: mmc_interrupt_hpi (STB_GLOBAL)
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
In drivers/mmc/core/mmc_ops.c (ffffffff819af383)
Location: drivers/mmc/core/mmc_ops.c:881
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
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
In drivers/mmc/core/mmc_ops.c (ffffffff81c2ac9c)
Location: drivers/mmc/core/mmc_ops.c:881
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:861
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
**Symbols:**

```
ffffffff819951f0-ffffffff8199537a: mmc_interrupt_hpi (STB_LOCAL)
ffffffff81c1d002-ffffffff81c1d075: mmc_interrupt_hpi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:867
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
**Symbols:**

```
ffffffff81a40b70-ffffffff81a40d32: mmc_interrupt_hpi (STB_LOCAL)
ffffffff81d2de38-ffffffff81d2dec1: mmc_interrupt_hpi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:897
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
**Symbols:**

```
ffffffff81bae410-ffffffff81bae5eb: mmc_interrupt_hpi (STB_LOCAL)
ffffffff81efa299-ffffffff81efa31f: mmc_interrupt_hpi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:897
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
**Symbols:**

```
ffffffff81d51c40-ffffffff81d51e8b: mmc_interrupt_hpi (STB_LOCAL)
ffffffff820a9a0a-ffffffff820a9a1f: mmc_interrupt_hpi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:898
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
**Symbols:**

```
ffffffff81dbc650-ffffffff81dbc894: mmc_interrupt_hpi (STB_LOCAL)
ffffffff8212adec-ffffffff8212ae01: mmc_interrupt_hpi.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:898
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
```
**Symbols:**

```
ffffffff81e74c20-ffffffff81e74e64: mmc_interrupt_hpi (STB_LOCAL)
ffffffff8220cba9-ffffffff8220cbbe: mmc_interrupt_hpi.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b36710)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffff800010b36710-ffff800010b3693c: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c1118c)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
c0c1118c-c0c113a0: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c31a10)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
c000000000c31a10-c000000000c31cc8: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e81c)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffe00070e81c-ffffffe00070e9e6: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff8188019f-ffffffff81880216: mmc_interrupt_hpi.cold (STB_LOCAL)
ffffffff8187ff00-ffffffff8188009d: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff818d163f-ffffffff818d16b6: mmc_interrupt_hpi.cold (STB_LOCAL)
ffffffff818d13a0-ffffffff818d153d: mmc_interrupt_hpi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_interrupt_hpi(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:838
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
```
**Symbols:**

```
ffffffff818ee15f-ffffffff818ee1d6: mmc_interrupt_hpi.cold (STB_LOCAL)
ffffffff818edec0-ffffffff818ee05d: mmc_interrupt_hpi (STB_GLOBAL)
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
