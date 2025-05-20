# Function: <code>balance_pgdat</code>

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
In mm/vmscan.c (ffffffff811a5a1c)
Location: mm/vmscan.c:3156
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811bc354)
Location: mm/vmscan.c:3191
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811cca19)
Location: mm/vmscan.c:3202
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811d56d1)
Location: mm/vmscan.c:3290
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff811eabe3)
Location: mm/vmscan.c:3314
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120c320)
Location: mm/vmscan.c:3323
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8120c320-ffffffff8120c661: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121efa0)
Location: mm/vmscan.c:3534
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8121efa0-ffffffff8121f500: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e760)
Location: mm/vmscan.c:3492
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8122e760-ffffffff8122ecf0: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123c8f0)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8123c8f0-ffffffff8123ce80: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81269760)
Location: mm/vmscan.c:3553
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81269760-ffffffff81269cab: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81274250)
Location: mm/vmscan.c:3551
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81274250-ffffffff812747dc: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81279480)
Location: mm/vmscan.c:3749
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81279480-ffffffff81279ae9: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:3938
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812b72a0-ffffffff812b7a8f: balance_pgdat (STB_LOCAL)
ffffffff81cba8a1-ffffffff81cba8d4: balance_pgdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:4084
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81311ff0-ffffffff8131286d: balance_pgdat (STB_LOCAL)
ffffffff81e6c141-ffffffff81e6c195: balance_pgdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:7025
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff813853f0-ffffffff81385c92: balance_pgdat (STB_LOCAL)
ffffffff82062bd5-ffffffff82062c29: balance_pgdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:7389
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff813b86d0-ffffffff813b8f5b: balance_pgdat (STB_LOCAL)
ffffffff820e2389-ffffffff820e23c2: balance_pgdat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (0)
Location: mm/vmscan.c:6756
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff813e16d0-ffffffff813e1f5b: balance_pgdat (STB_LOCAL)
ffffffff821bed33-ffffffff821bed6c: balance_pgdat.cold (STB_LOCAL)
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
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cdbc0)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffff8000102cdbc0-ffff8000102ce168: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f7a2c)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
c04f7a2c-c04f7fa0: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c00000000038b750)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
c00000000038b750-c00000000038be28: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001ebf62)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffe0001ebf62-ffffffe0001ec416: balance_pgdat (STB_LOCAL)
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
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81234f40)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81234f40-ffffffff812354d0: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81227fb0)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81227fb0-ffffffff81228540: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81232ce0)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81232ce0-ffffffff81233270: balance_pgdat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int balance_pgdat(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812421f0)
Location: mm/vmscan.c:3578
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812421f0-ffffffff8124277b: balance_pgdat (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
