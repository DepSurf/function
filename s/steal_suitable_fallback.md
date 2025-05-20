# Function: <code>steal_suitable_fallback</code>

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
In mm/page_alloc.c (ffffffff81195b76)
Location: mm/page_alloc.c:1584
Inline: True
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
In mm/page_alloc.c (ffffffff811a87cd)
Location: mm/page_alloc.c:1943
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
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
In mm/page_alloc.c (ffffffff811b8bcf)
Location: mm/page_alloc.c:1962
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
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
In mm/page_alloc.c (ffffffff811c0a24)
Location: mm/page_alloc.c:1982
Inline: True
Inline callers:
  - mm/page_alloc.c:__rmqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d5100)
Location: mm/page_alloc.c:2020
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811d5100-ffffffff811d5271: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f6550)
Location: mm/page_alloc.c:2129
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff811f6550-ffffffff811f66d2: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81208830)
Location: mm/page_alloc.c:2199
Inline: False
Direct callers:
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:get_page_from_freelist
```
**Symbols:**

```
ffffffff81208830-ffffffff81208a43: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126ec90)
Location: mm/page_alloc.c:2378
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8126ec90-ffffffff8126ee95: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127dad0)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff8127dad0-ffffffff8127dcd5: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812afbf0)
Location: mm/page_alloc.c:2449
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812afbf0-ffffffff812afea3: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bb890)
Location: mm/page_alloc.c:2529
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812bb890-ffffffff812bbb28: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c08f0)
Location: mm/page_alloc.c:2578
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812c08f0-ffffffff812c0b83: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2651
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff81303840-ffffffff81303b05: steal_suitable_fallback (STB_LOCAL)
ffffffff81cbd518-ffffffff81cbd537: steal_suitable_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2676
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff8136b820-ffffffff8136bb65: steal_suitable_fallback (STB_LOCAL)
ffffffff81e6f516-ffffffff81e6f534: steal_suitable_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:2755
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff813e7b60-ffffffff813e7ea5: steal_suitable_fallback (STB_LOCAL)
ffffffff820652d1-ffffffff820652ef: steal_suitable_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1801
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff8141cc40-ffffffff8141cf88: steal_suitable_fallback (STB_LOCAL)
ffffffff820e4ab2-ffffffff820e4aca: steal_suitable_fallback.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:1764
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue_bulk
```
**Symbols:**

```
ffffffff81449740-ffffffff81449a28: steal_suitable_fallback (STB_LOCAL)
ffffffff821c174d-ffffffff821c1765: steal_suitable_fallback.cold (STB_LOCAL)
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
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103153f8)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffff8000103153f8-ffff800010315660: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c052fc84)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c052fc84-c052fed8: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e7260)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
c0000000003e7260-c0000000003e7584: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021be16)
Location: mm/page_alloc.c:2369
Inline: False
```
**Symbols:**

```
ffffffe00021be16-ffffffe00021bfc6: steal_suitable_fallback (STB_LOCAL)
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
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81276120)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81276120-ffffffff81276325: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81268070)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81268070-ffffffff81268275: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81273ec0)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff81273ec0-ffffffff812740c5: steal_suitable_fallback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void steal_suitable_fallback(struct zone *zone, struct page *page, unsigned int alloc_flags, int start_type, bool whole_block);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812839c0)
Location: mm/page_alloc.c:2369
Inline: False
Direct callers:
  - mm/page_alloc.c:rmqueue
```
**Symbols:**

```
ffffffff812839c0-ffffffff81283bc5: steal_suitable_fallback (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int alloc_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, page, start_type, whole_block</code> ➡️ <code>zone, page, alloc_flags, start_type, whole_block</code>
</li>
</ul>
</details>
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
