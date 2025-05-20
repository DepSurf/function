# Function: <code>isolate_single_pageblock</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int isolate_single_pageblock(long unsigned int boundary_pfn, int flags, gfp_t gfp_flags, bool isolate_before, bool skip_isolation);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:304
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff813de180-ffffffff813de762: isolate_single_pageblock (STB_LOCAL)
ffffffff81e759f0-ffffffff81e75a45: isolate_single_pageblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int isolate_single_pageblock(long unsigned int boundary_pfn, int flags, gfp_t gfp_flags, bool isolate_before, bool skip_isolation, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:305
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff81464e10-ffffffff814653eb: isolate_single_pageblock (STB_LOCAL)
ffffffff8206842c-ffffffff82068481: isolate_single_pageblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int isolate_single_pageblock(long unsigned int boundary_pfn, int flags, gfp_t gfp_flags, bool isolate_before, bool skip_isolation, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:305
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff8149a8e0-ffffffff8149ae67: isolate_single_pageblock (STB_LOCAL)
ffffffff820e7d2f-ffffffff820e7d84: isolate_single_pageblock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int isolate_single_pageblock(long unsigned int boundary_pfn, int flags, gfp_t gfp_flags, bool isolate_before, bool skip_isolation, int migratetype);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/page_isolation.c (0)
Location: mm/page_isolation.c:306
Inline: False
Direct callers:
  - mm/page_isolation.c:start_isolate_page_range
  - mm/page_isolation.c:start_isolate_page_range
```
**Symbols:**

```
ffffffff814c9fd0-ffffffff814ca54b: isolate_single_pageblock (STB_LOCAL)
ffffffff821c4a75-ffffffff821c4aca: isolate_single_pageblock.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int migratetype</code>
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
