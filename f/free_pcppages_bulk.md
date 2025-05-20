# Function: <code>free_pcppages_bulk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811944e0)
Location: mm/page_alloc.c:777
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_zone_pages
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:free_hot_cold_page
```
**Symbols:**

```
ffffffff811944e0-ffffffff811949aa: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811a79b0)
Location: mm/page_alloc.c:1069
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff811a79b0-ffffffff811a7e6c: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b7da0)
Location: mm/page_alloc.c:1085
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff811b7da0-ffffffff811b8254: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bfbf0)
Location: mm/page_alloc.c:1099
Inline: False
Direct callers:
  - mm/page_alloc.c:free_hot_cold_page
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff811bfbf0-ffffffff811c00c5: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d45d0)
Location: mm/page_alloc.c:1113
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff811d45d0-ffffffff811d4aa8: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f51b0)
Location: mm/page_alloc.c:1080
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff811f51b0-ffffffff811f577a: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81207c20)
Location: mm/page_alloc.c:1125
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff81207c20-ffffffff812081d5: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126df40)
Location: mm/page_alloc.c:1249
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff8126df40-ffffffff8126e5cc: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127cd80)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff8127cd80-ffffffff8127d40c: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af0d0)
Location: mm/page_alloc.c:1286
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff812af0d0-ffffffff812af399: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bad40)
Location: mm/page_alloc.c:1348
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_local_pages_wq
  - mm/page_alloc.c:drain_pages
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff812bad40-ffffffff812bafea: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bfe90)
Location: mm/page_alloc.c:1383
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff812bfe90-ffffffff812c012d: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81302a70)
Location: mm/page_alloc.c:1442
Inline: False
Direct callers:
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff81302a70-ffffffff81302d8d: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp, int pindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813697e0)
Location: mm/page_alloc.c:1453
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff813697e0-ffffffff81369aad: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp, int pindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1533
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff813e5850-ffffffff813e5b3c: free_pcppages_bulk (STB_LOCAL)
ffffffff82064dde-ffffffff82064e0e: free_pcppages_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp, int pindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1208
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff8141a530-ffffffff8141a862: free_pcppages_bulk (STB_LOCAL)
ffffffff820e4543-ffffffff820e4572: free_pcppages_bulk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp, int pindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1187
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
  - mm/page_alloc.c:decay_pcp_high
```
**Symbols:**

```
ffffffff81447790-ffffffff81447a6e: free_pcppages_bulk (STB_LOCAL)
ffffffff821c124c-ffffffff821c127b: free_pcppages_bulk.cold (STB_LOCAL)
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
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010314918)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffff800010314918-ffff800010314c4c: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052ebec)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
```
**Symbols:**

```
c052ebec-c052f2c8: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e60c0)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
c0000000003e60c0-c0000000003e68d8: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021b258)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
```
**Symbols:**

```
ffffffe00021b258-ffffffe00021b7a8: free_pcppages_bulk (STB_LOCAL)
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
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812753d0)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff812753d0-ffffffff81275a5c: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81267330)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff81267330-ffffffff812679bc: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273170)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff81273170-ffffffff812737fc: free_pcppages_bulk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_pcppages_bulk(struct zone *zone, int count, struct per_cpu_pages *pcp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282c50)
Location: mm/page_alloc.c:1236
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_commit
  - mm/page_alloc.c:drain_pages_zone
  - mm/page_alloc.c:drain_zone_pages
```
**Symbols:**

```
ffffffff81282c50-ffffffff812832f3: free_pcppages_bulk (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int pindex</code>
</li>
</ul>
</details>
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
