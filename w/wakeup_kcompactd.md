# Function: <code>wakeup_kcompactd</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d2460)
Location: mm/compaction.c:1960
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811d2460-ffffffff811d2569: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e2320)
Location: mm/compaction.c:1945
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811e2320-ffffffff811e2429: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811ec140)
Location: mm/compaction.c:1994
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811ec140-ffffffff811ec24f: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812024a0)
Location: mm/compaction.c:2017
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812024a0-ffffffff812025b8: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81223850)
Location: mm/compaction.c:2025
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81223850-ffffffff81223965: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812368b0)
Location: mm/compaction.c:2026
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff812368b0-ffffffff812369c8: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81247de0)
Location: mm/compaction.c:2607
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81247de0-ffffffff81247efb: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81256240)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81256240-ffffffff8125635b: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812848d0)
Location: mm/compaction.c:2615
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff812848d0-ffffffff812849f5: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128ebf0)
Location: mm/compaction.c:2811
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8128ebf0-ffffffff8128ed03: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81294270)
Location: mm/compaction.c:2856
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81294270-ffffffff81294383: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d48a0)
Location: mm/compaction.c:2873
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff812d48a0-ffffffff812d49ce: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813338d0)
Location: mm/compaction.c:2893
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813338d0-ffffffff81333a2e: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813aa600)
Location: mm/compaction.c:2892
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813aa600-ffffffff813aa75e: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813dd720)
Location: mm/compaction.c:2987
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813dd720-ffffffff813dd8a6: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81407680)
Location: mm/compaction.c:3046
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81407680-ffffffff81407814: wakeup_kcompactd (STB_GLOBAL)
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
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ed870)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffff8000102ed870-ffff8000102ed9c0: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c051182c)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
c051182c-c0511968: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003b16e0)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
c0000000003b16e0-c0000000003b18b0: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000201d5a)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffe000201d5a-ffffffe000201e8a: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124e890)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8124e890-ffffffff8124e9ab: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81241830)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81241830-ffffffff8124194b: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124c630)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8124c630-ffffffff8124c74b: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_kcompactd(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125bfd0)
Location: mm/compaction.c:2598
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8125bfd0-ffffffff8125c103: wakeup_kcompactd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int highest_zoneidx</code>
</li>
<li>
<b>Param removed. </b>
<code>int classzone_idx</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
