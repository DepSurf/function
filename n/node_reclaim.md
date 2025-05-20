# Function: <code>node_reclaim</code>

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
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811bbf20)
Location: mm/vmscan.c:3755
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811bbf20-ffffffff811bc12c: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811cc5f0)
Location: mm/vmscan.c:3766
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811cc5f0-ffffffff811cc7fc: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d5240)
Location: mm/vmscan.c:3871
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811d5240-ffffffff811d547b: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811ea770)
Location: mm/vmscan.c:3894
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811ea770-ffffffff811ea9ab: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8120c0c0)
Location: mm/vmscan.c:3923
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8120c0c0-ffffffff8120c179: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121ebe0)
Location: mm/vmscan.c:4216
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8121ebe0-ffffffff8121ee14: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8122e2c0)
Location: mm/vmscan.c:4174
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8122e2c0-ffffffff8122e5d3: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8123c450)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8123c450-ffffffff8123c763: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8126ace0)
Location: mm/vmscan.c:4218
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8126ace0-ffffffff8126ad9a: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81275720)
Location: mm/vmscan.c:4221
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81275720-ffffffff812757da: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8127aa40)
Location: mm/vmscan.c:4411
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff8127aa40-ffffffff8127aafa: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff812b8aa0)
Location: mm/vmscan.c:4603
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff812b8aa0-ffffffff812b8b5a: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81314540)
Location: mm/vmscan.c:4746
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81314540-ffffffff81314604: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81388680)
Location: mm/vmscan.c:7691
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81388680-ffffffff81388744: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813ba810)
Location: mm/vmscan.c:8055
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff813ba810-ffffffff813ba8d4: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff813e3930)
Location: mm/vmscan.c:7425
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff813e3930-ffffffff813e39f4: node_reclaim (STB_GLOBAL)
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
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffff8000102cd5f0)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffff8000102cd5f0-ffff8000102cd9c8: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (c00000000038b060)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
c00000000038b060-c00000000038b518: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81234aa0)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81234aa0-ffffffff81234db3: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81227b10)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81227b10-ffffffff81227e23: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81232840)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81232840-ffffffff81232b53: node_reclaim (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int node_reclaim(struct pglist_data *pgdat, gfp_t gfp_mask, unsigned int order);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81241d00)
Location: mm/vmscan.c:4260
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81241d00-ffffffff8124203e: node_reclaim (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
