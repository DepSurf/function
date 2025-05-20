# Function: <code>free_unref_page_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4bc0)
Location: mm/page_alloc.c:2635
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff811d4bc0-ffffffff811d4ca1: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5ff0)
Location: mm/page_alloc.c:2740
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff811f5ff0-ffffffff811f60c3: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812082c0)
Location: mm/page_alloc.c:2839
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812082c0-ffffffff81208393: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126e6c0)
Location: mm/page_alloc.c:3015
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8126e6c0-ffffffff8126e790: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127d500)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8127d500-ffffffff8127d5d0: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812af3a0)
Location: mm/page_alloc.c:3098
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812af3a0-ffffffff812af465: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812baff0)
Location: mm/page_alloc.c:3199
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812baff0-ffffffff812bb0ba: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c0280)
Location: mm/page_alloc.c:3248
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812c0280-ffffffff812c0347: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3366
Inline: True
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81302f80-ffffffff813030d5: free_unref_page_commit.constprop.0 (STB_LOCAL)
ffffffff81cbd371-ffffffff81cbd3b0: free_unref_page_commit.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void free_unref_page_commit(struct page *page, int migratetype, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3394
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81369ca0-ffffffff81369e4a: free_unref_page_commit (STB_LOCAL)
ffffffff81e6f037-ffffffff81e6f07d: free_unref_page_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void free_unref_page_commit(struct zone *zone, struct per_cpu_pages *pcp, struct page *page, int migratetype, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:3424
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff813e5ed0-ffffffff813e605e: free_unref_page_commit (STB_LOCAL)
ffffffff82064e0e-ffffffff82064ede: free_unref_page_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void free_unref_page_commit(struct zone *zone, struct per_cpu_pages *pcp, struct page *page, int migratetype, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2403
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff8141ac00-ffffffff8141adc5: free_unref_page_commit (STB_LOCAL)
ffffffff820e4572-ffffffff820e4661: free_unref_page_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void free_unref_page_commit(struct zone *zone, struct per_cpu_pages *pcp, struct page *page, int migratetype, unsigned int order);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2427
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81447e00-ffffffff81448180: free_unref_page_commit (STB_LOCAL)
ffffffff821c127b-ffffffff821c139d: free_unref_page_commit.cold (STB_LOCAL)
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
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010314d90)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffff800010314d90-ffff800010314ea0: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052f3b0)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
c052f3b0-c052f4a0: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e6ab0)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
c0000000003e6ab0-c0000000003e6b98: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021b8b6)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffe00021b8b6-ffffffe00021b9a2: free_unref_page_commit (STB_LOCAL)
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
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81275b50)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81275b50-ffffffff81275c20: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81267aa0)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff81267aa0-ffffffff81267b70: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812738f0)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812738f0-ffffffff812739c0: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_unref_page_commit(struct page *page, long unsigned int pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812833f0)
Location: mm/page_alloc.c:3006
Inline: False
Direct callers:
  - mm/page_alloc.c:free_unref_page_list
  - mm/page_alloc.c:free_unref_page
```
**Symbols:**

```
ffffffff812833f0-ffffffff812834c0: free_unref_page_commit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct zone *zone</code>
</li>
<li>
<b>Param added. </b>
<code>struct per_cpu_pages *pcp</code>
</li>
<li>
<b>Param reordered. </b>
<code>page, migratetype, order</code> ➡️ <code>zone, pcp, page, migratetype, order</code>
</li>
</ul>
</details>
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
