# Function: <code>prepare_kswapd_sleep</code>

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
In mm/vmscan.c (ffffffff811a601b)
Location: mm/vmscan.c:3038
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b7010)
Location: mm/vmscan.c:3102
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811b7010-ffffffff811b70a1: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c7610)
Location: mm/vmscan.c:3113
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811c7610-ffffffff811c76a1: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cfd50)
Location: mm/vmscan.c:3204
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811cfd50-ffffffff811cfdde: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e5200)
Location: mm/vmscan.c:3228
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811e5200-ffffffff811e528e: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81206930)
Location: mm/vmscan.c:3237
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81206930-ffffffff812069b9: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812194f0)
Location: mm/vmscan.c:3448
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812194f0-ffffffff81219570: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81228920)
Location: mm/vmscan.c:3406
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81228920-ffffffff812289a0: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812367c0)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812367c0-ffffffff81236840: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812640a0)
Location: mm/vmscan.c:3466
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff812640a0-ffffffff8126414d: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126e860)
Location: mm/vmscan.c:3464
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff8126e860-ffffffff8126e916: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273430)
Location: mm/vmscan.c:3662
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff81273430-ffffffff812734e6: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b0a80)
Location: mm/vmscan.c:3819
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff812b0a80-ffffffff812b0b33: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130bf80)
Location: mm/vmscan.c:3965
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff8130bf80-ffffffff8130c03f: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81379ce0)
Location: mm/vmscan.c:6906
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff81379ce0-ffffffff81379d9f: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ae230)
Location: mm/vmscan.c:7270
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff813ae230-ffffffff813ae2f7: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d7860)
Location: mm/vmscan.c:6637
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:kswapd_try_to_sleep
```
**Symbols:**

```
ffffffff813d7860-ffffffff813d7927: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102c7f10)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffff8000102c7f10-ffff8000102c7ff4: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c04f1514)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
c04f1514-c04f15bc: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c0000000003826e0)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
c0000000003826e0-c0000000003827e4: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffe0001e7274)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffe0001e7274-ffffffe0001e7314: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122ee10)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8122ee10-ffffffff8122ee90: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81221ed0)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81221ed0-ffffffff81221f50: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122cbb0)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8122cbb0-ffffffff8122cc30: prepare_kswapd_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool prepare_kswapd_sleep(pg_data_t *pgdat, int order, int classzone_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123bfe0)
Location: mm/vmscan.c:3492
Inline: True
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8123bfe0-ffffffff8123c060: prepare_kswapd_sleep (STB_LOCAL)
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
