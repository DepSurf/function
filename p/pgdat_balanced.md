# Function: <code>pgdat_balanced</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a2420)
Location: mm/vmscan.c:2993
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811a2420-ffffffff811a250a: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cf4b0)
Location: mm/vmscan.c:3162
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811cf4b0-ffffffff811cf539: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e4860)
Location: mm/vmscan.c:3186
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811e4860-ffffffff811e48e9: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81206070)
Location: mm/vmscan.c:3195
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81206070-ffffffff812060f9: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81218d00)
Location: mm/vmscan.c:3402
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81218d00-ffffffff81218d7f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228720)
Location: mm/vmscan.c:3360
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81228720-ffffffff8122879f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812365c0)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff812365c0-ffffffff8123663f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81263900)
Location: mm/vmscan.c:3418
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81263900-ffffffff81263978: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e290)
Location: mm/vmscan.c:3416
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8126e290-ffffffff8126e308: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81272f90)
Location: mm/vmscan.c:3614
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81272f90-ffffffff81273008: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b02c0)
Location: mm/vmscan.c:3771
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff812b02c0-ffffffff812b033b: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130bbb0)
Location: mm/vmscan.c:3914
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
```
**Symbols:**

```
ffffffff8130bbb0-ffffffff8130bc5b: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813770b0)
Location: mm/vmscan.c:6855
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
```
**Symbols:**

```
ffffffff813770b0-ffffffff8137715b: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813a5ae0)
Location: mm/vmscan.c:7218
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
```
**Symbols:**

```
ffffffff813a5ae0-ffffffff813a5b8b: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813cf650)
Location: mm/vmscan.c:6585
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:prepare_kswapd_sleep
```
**Symbols:**

```
ffffffff813cf650-ffffffff813cf6fb: pgdat_balanced (STB_LOCAL)
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
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c6180)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffff8000102c6180-ffff8000102c6218: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f13bc)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
c04f13bc-c04f1444: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c000000000382320)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
c000000000382320-c0000000003823f8: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e6bd4)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffe0001e6bd4-ffffffe0001e6c4e: pgdat_balanced (STB_LOCAL)
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
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122ec10)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8122ec10-ffffffff8122ec8f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81221cd0)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81221cd0-ffffffff81221d4f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122c9b0)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8122c9b0-ffffffff8122ca2f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pgdat_balanced(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123bde0)
Location: mm/vmscan.c:3446
Inline: False
Direct callers:
  - mm/vmscan.c:wakeup_kswapd
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8123bde0-ffffffff8123be5f: pgdat_balanced (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
