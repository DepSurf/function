# Function: <code>undo_isolate_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81203e70)
Location: mm/page_isolation.c:191
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81203e70-ffffffff81203f1a: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81228e20)
Location: mm/page_isolation.c:195
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81228e20-ffffffff81228eca: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8123b3e0)
Location: mm/page_isolation.c:195
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff8123b3e0-ffffffff8123b479: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81246ee0)
Location: mm/page_isolation.c:207
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffff81246ee0-ffffffff81246fd8: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81267050)
Location: mm/page_isolation.c:208
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff81267050-ffffffff81267149: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8128b920)
Location: mm/page_isolation.c:224
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff8128b920-ffffffff8128ba19: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812a0880)
Location: mm/page_isolation.c:235
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812a0880-ffffffff812a0979: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812bbb10)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812bbb10-ffffffff812bbc07: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812cd9f0)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812cd9f0-ffffffff812cdae7: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81303c30)
Location: mm/page_isolation.c:224
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff81303c30-ffffffff81303d42: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8130fb10)
Location: mm/page_isolation.c:221
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8130fb10-ffffffff8130fc1d: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81315d80)
Location: mm/page_isolation.c:221
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81315d80-ffffffff81315e1b: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81361e70)
Location: mm/page_isolation.c:220
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81361e70-ffffffff81361f0b: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff813de770)
Location: mm/page_isolation.c:574
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff813de770-ffffffff813de811: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff81465400)
Location: mm/page_isolation.c:577
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81465400-ffffffff814654a1: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff8149ae80)
Location: mm/page_isolation.c:582
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8149ae80-ffffffff8149af21: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff814ca560)
Location: mm/page_isolation.c:583
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff814ca560-ffffffff814ca601: undo_isolate_page_range (STB_GLOBAL)
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
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffff800010371dc0)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffff800010371dc0-ffff800010371ed0: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (c055ec30)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
c055ec30-c055ed1c: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (c0000000004635c0)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
c0000000004635c0-c00000000046375c: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffe00024b190)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/page_alloc.c:alloc_contig_range
```
**Symbols:**

```
ffffffe00024b190-ffffffe00024b29c: undo_isolate_page_range (STB_GLOBAL)
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
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812c5fd0)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812c5fd0-ffffffff812c60c7: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812b7010)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812b7010-ffffffff812b7107: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812c3de0)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812c3de0-ffffffff812c3ed7: undo_isolate_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void undo_isolate_page_range(long unsigned int start_pfn, long unsigned int end_pfn, unsigned int migratetype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_isolation.c (ffffffff812d4880)
Location: mm/page_isolation.c:233
Inline: False
Direct callers:
  - mm/page_alloc.c:alloc_contig_range
  - mm/memory_hotplug.c:__offline_pages
```
**Symbols:**

```
ffffffff812d4880-ffffffff812d4977: undo_isolate_page_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
