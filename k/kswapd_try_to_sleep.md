# Function: <code>kswapd_try_to_sleep</code>

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
In mm/vmscan.c (ffffffff811a58b7)
Location: mm/vmscan.c:3344
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
In mm/vmscan.c (ffffffff811bc346)
Location: mm/vmscan.c:3314
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
In mm/vmscan.c (ffffffff811cca0b)
Location: mm/vmscan.c:3325
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
In mm/vmscan.c (ffffffff811d56ca)
Location: mm/vmscan.c:3423
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
In mm/vmscan.c (ffffffff811eac2d)
Location: mm/vmscan.c:3447
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff8120c731)
Location: mm/vmscan.c:3464
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff8121f5c1)
Location: mm/vmscan.c:3756
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff8122eda6)
Location: mm/vmscan.c:3715
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff8123cf36)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812655c0)
Location: mm/vmscan.c:3776
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812655c0-ffffffff812657d7: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126fb30)
Location: mm/vmscan.c:3774
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8126fb30-ffffffff8126fd30: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273850)
Location: mm/vmscan.c:3972
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81273850-ffffffff81273a50: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b0b40)
Location: mm/vmscan.c:4164
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff812b0b40-ffffffff812b0d3d: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8130c460)
Location: mm/vmscan.c:4310
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff8130c460-ffffffff8130c677: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81379db0)
Location: mm/vmscan.c:7250
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff81379db0-ffffffff81379fc9: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ae310)
Location: mm/vmscan.c:7614
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff813ae310-ffffffff813ae528: kswapd_try_to_sleep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kswapd_try_to_sleep(pg_data_t *pgdat, int alloc_order, int reclaim_order, unsigned int highest_zoneidx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813d7940)
Location: mm/vmscan.c:6981
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff813d7940-ffffffff813d7b58: kswapd_try_to_sleep (STB_LOCAL)
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
In mm/vmscan.c (ffff8000102ce224)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (c04f8078)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (c00000000038bf40)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffe0001ec47a)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff81235586)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812285f6)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81233326)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
In mm/vmscan.c (ffffffff81242836)
Location: mm/vmscan.c:3801
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
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
