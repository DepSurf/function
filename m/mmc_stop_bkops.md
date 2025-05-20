# Function: <code>mmc_stop_bkops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int mmc_stop_bkops(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be350)
Location: drivers/mmc/core/core.c:762
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff816be350-ffffffff816be389: mmc_stop_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int mmc_stop_bkops(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817202c0)
Location: drivers/mmc/core/core.c:763
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff817202c0-ffffffff817202f9: mmc_stop_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int mmc_stop_bkops(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81752b40)
Location: drivers/mmc/core/core.c:836
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff81752b40-ffffffff81752b72: mmc_stop_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_stop_bkops(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177acc0)
Location: drivers/mmc/core/mmc_ops.c:910
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff8177acc0-ffffffff8177acf2: mmc_stop_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_stop_bkops(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f12b0)
Location: drivers/mmc/core/mmc_ops.c:911
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff817f12b0-ffffffff817f12e2: mmc_stop_bkops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_stop_bkops(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8183a4a0)
Location: drivers/mmc/core/mmc_ops.c:909
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:_mmc_suspend
```
**Symbols:**

```
ffffffff8183a4a0-ffffffff8183a4d2: mmc_stop_bkops (STB_GLOBAL)
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
