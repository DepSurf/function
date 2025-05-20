# Function: <code>find_biggest_section_pfn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811ef210)
Location: mm/memory_hotplug.c:557
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff811ef210-ffffffff811ef2b8: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120e4c0)
Location: mm/memory_hotplug.c:616
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8120e4c0-ffffffff8120e569: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81220500)
Location: mm/memory_hotplug.c:602
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81220500-ffffffff812205a5: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122c1b0)
Location: mm/memory_hotplug.c:359
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8122c1b0-ffffffff8122c250: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81247970)
Location: mm/memory_hotplug.c:368
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81247970-ffffffff81247a17: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8126b450)
Location: mm/memory_hotplug.c:346
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8126b450-ffffffff8126b4ed: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8127fce0)
Location: mm/memory_hotplug.c:346
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8127fce0-ffffffff8127fd7d: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129c230)
Location: mm/memory_hotplug.c:352
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8129c230-ffffffff8129c301: find_biggest_section_pfn (STB_LOCAL)
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
In mm/memory_hotplug.c (ffffffff81ac8e1b)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0a60)
Location: mm/memory_hotplug.c:377
Inline: False
Direct callers:
  - mm/memory_hotplug.c:shrink_zone_span
```
**Symbols:**

```
ffffffff812e0a60-ffffffff812e0b46: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int find_biggest_section_pfn(int nid, struct zone *zone, long unsigned int start_pfn, long unsigned int end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812eb770)
Location: mm/memory_hotplug.c:377
Inline: False
Direct callers:
  - mm/memory_hotplug.c:shrink_zone_span
```
**Symbols:**

```
ffffffff812eb770-ffffffff812eb856: find_biggest_section_pfn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c6596)
Location: mm/memory_hotplug.c:420
Inline: True
Inline callers:
  - mm/memory_hotplug.c:shrink_zone_span
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81d4b463)
Location: mm/memory_hotplug.c:369
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81f1ad35)
Location: mm/memory_hotplug.c:380
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff820c2bf5)
Location: mm/memory_hotplug.c:368
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82146994)
Location: mm/memory_hotplug.c:367
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff82229124)
Location: mm/memory_hotplug.c:435
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
In mm/memory_hotplug.c (ffff800010d9cb40)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042f8d0)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a67c8b)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
In mm/memory_hotplug.c (ffffffff81a2474b)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
In mm/memory_hotplug.c (ffffffff81ad409b)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
In mm/memory_hotplug.c (ffffffff81ae057e)
Location: mm/memory_hotplug.c:352
Inline: True
Inline callers:
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
