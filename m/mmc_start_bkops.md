# Function: <code>mmc_start_bkops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mmc_start_bkops(struct mmc_card *card, bool from_exception);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be390)
Location: drivers/mmc/core/core.c:309
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff816be390-ffffffff816be4ef: mmc_start_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_start_bkops(struct mmc_card *card, bool from_exception);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81720300)
Location: drivers/mmc/core/core.c:310
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff81720300-ffffffff8172045f: mmc_start_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mmc_start_bkops(struct mmc_card *card, bool from_exception);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81752b80)
Location: drivers/mmc/core/core.c:346
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_start_req
```
**Symbols:**

```
ffffffff81752b80-ffffffff81752ce5: mmc_start_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mmc_start_bkops(struct mmc_card *card, bool from_exception);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177ad00)
Location: drivers/mmc/core/mmc_ops.c:956
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_areq
```
**Symbols:**

```
ffffffff8177ad00-ffffffff8177aeaa: mmc_start_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_start_bkops(struct mmc_card *card, bool from_exception);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0e00)
Location: drivers/mmc/core/mmc_ops.c:957
Inline: True
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_areq
```
**Symbols:**

```
ffffffff817f0e00-ffffffff817f0f97: mmc_start_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_start_bkops(struct mmc_card *card, bool from_exception);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (0)
Location: drivers/mmc/core/mmc_ops.c:953
Inline: True
```
**Symbols:**

```
ffffffff8183a574-ffffffff8183a5b8: mmc_start_bkops.cold.11 (STB_LOCAL)
ffffffff8183a0f0-ffffffff8183a254: mmc_start_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
