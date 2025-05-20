# Function: <code>start_isolate_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81203c50)
Location: mm/page_isolation.c:158
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81203c50-ffffffff81203e66: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81228c00)
Location: mm/page_isolation.c:162
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81228c00-ffffffff81228e14: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8123b1b0)
Location: mm/page_isolation.c:162
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff8123b1b0-ffffffff8123b3d2: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81246c10)
Location: mm/page_isolation.c:170
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81246c10-ffffffff81246edf: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81266d80)
Location: mm/page_isolation.c:171
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff81266d80-ffffffff81267043: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, bool skip_hwpoisoned_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8128b630)
Location: mm/page_isolation.c:187
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff8128b630-ffffffff8128b91e: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812a0580)
Location: mm/page_isolation.c:195
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812a0580-ffffffff812a0879: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812bb800)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812bb800-ffffffff812bbb07: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812cd6e0)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812cd6e0-ffffffff812cd9e7: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81303a80)
Location: mm/page_isolation.c:184
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff81303a80-ffffffff81303c21: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8130f970)
Location: mm/page_isolation.c:183
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff8130f970-ffffffff8130fb0a: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81315b70)
Location: mm/page_isolation.c:183
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81315b70-ffffffff81315d7b: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81361c40)
Location: mm/page_isolation.c:182
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff81361c40-ffffffff81361e6a: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype, int flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff813de820)
Location: mm/page_isolation.c:528
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff813de820-ffffffff813de97a: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype, int flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff814654c0)
Location: mm/page_isolation.c:529
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff814654c0-ffffffff81465628: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype, int flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8149af40)
Location: mm/page_isolation.c:528
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff8149af40-ffffffff8149b0aa: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype, int flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff814ca620)
Location: mm/page_isolation.c:529
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
```
**Symbols:**

```
ffffffff814ca620-ffffffff814ca78a: start_isolate_page_range (STB_GLOBAL)
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
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffff8000103719e0)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffff8000103719e0-ffff800010371dbc: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (c055e9a4)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
c055e9a4-c055ec30: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (c000000000463120)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
c000000000463120-c0000000004635bc: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffe00024aedc)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffe00024aedc-ffffffe00024b190: start_isolate_page_range (STB_GLOBAL)
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
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812c5cc0)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812c5cc0-ffffffff812c5fc7: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812b6d00)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812b6d00-ffffffff812b7007: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812c3ad0)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812c3ad0-ffffffff812c3dd7: start_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int start_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812d4570)
Location: mm/page_isolation.c:193
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812d4570-ffffffff812d4877: start_isolate_page_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool skip_hwpoisoned_pages</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp_flags</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int migratetype</code> ➡️ <code>int migratetype</code>
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
