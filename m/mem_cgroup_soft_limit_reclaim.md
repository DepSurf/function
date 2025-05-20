# Function: <code>mem_cgroup_soft_limit_reclaim</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(struct zone *zone, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811ffc30)
Location: mm/memcontrol.c:2634
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - mm/vmscan.c:kswapd
```
**Symbols:**

```
ffffffff811ffc30-ffffffff811fff70: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81223990)
Location: mm/memcontrol.c:2567
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81223990-ffffffff81223cd1: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81235e80)
Location: mm/memcontrol.c:2540
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81235e80-ffffffff812361c6: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241900)
Location: mm/memcontrol.c:2548
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81241900-ffffffff81241c4b: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261650)
Location: mm/memcontrol.c:2575
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81261650-ffffffff8126199b: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285690)
Location: mm/memcontrol.c:2503
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81285690-ffffffff812859ad: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129a590)
Location: mm/memcontrol.c:2777
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8129a590-ffffffff8129a8be: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5830)
Location: mm/memcontrol.c:3012
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812b5830-ffffffff812b5b4a: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c74e0)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812c74e0-ffffffff812c77fa: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fcf40)
Location: mm/memcontrol.c:3104
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_zones
```
**Symbols:**

```
ffffffff812fcf40-ffffffff812fd192: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813093a0)
Location: mm/memcontrol.c:3409
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_zones
```
**Symbols:**

```
ffffffff813093a0-ffffffff813095fd: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f980)
Location: mm/memcontrol.c:3245
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff8130f980-ffffffff8130fd3d: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (0)
Location: mm/memcontrol.c:3413
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81cc2b89-ffffffff81cc2b9d: mem_cgroup_soft_limit_reclaim.cold (STB_LOCAL)
ffffffff8135ac00-ffffffff8135afea: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d42e0)
Location: mm/memcontrol.c:3418
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff813d42e0-ffffffff813d466f: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81459cd0)
Location: mm/memcontrol.c:3518
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff81459cd0-ffffffff8145a05f: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148f960)
Location: mm/memcontrol.c:3529
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff8148f960-ffffffff8148fcb3: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bf190)
Location: mm/memcontrol.c:3721
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
```
**Symbols:**

```
ffffffff814bf190-ffffffff814bf4e3: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036a300)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffff80001036a300-ffff80001036a620: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055b7b4)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c055b7b4-c055bb64: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0000000004592e0)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
c0000000004592e0-c000000000459828: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000247b92)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffe000247b92-ffffffe000247e9c: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
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
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bfac0)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812bfac0-ffffffff812bfdda: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b0ba0)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812b0ba0-ffffffff812b0eae: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd8d0)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812bd8d0-ffffffff812bdbea: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int mem_cgroup_soft_limit_reclaim(pg_data_t *pgdat, int order, gfp_t gfp_mask, long unsigned int *total_scanned);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ce210)
Location: mm/memcontrol.c:3221
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff812ce210-ffffffff812ce546: mem_cgroup_soft_limit_reclaim (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pg_data_t *pgdat</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
