# Function: <code>adjust_present_page_count</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void adjust_present_page_count(struct zone *zone, long int nr_pages);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c2d08e)
Location: mm/memory_hotplug.c:866
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff812c70d0-ffffffff812c711c: adjust_present_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void adjust_present_page_count(struct page *page, struct memory_group *group, long int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130bd50)
Location: mm/memory_hotplug.c:1010
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff8130bd50-ffffffff8130be55: adjust_present_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void adjust_present_page_count(struct page *page, struct memory_group *group, long int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81374cc0)
Location: mm/memory_hotplug.c:1009
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81374cc0-ffffffff81374e03: adjust_present_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void adjust_present_page_count(struct page *page, struct memory_group *group, long int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2610)
Location: mm/memory_hotplug.c:1005
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff813f2610-ffffffff813f2753: adjust_present_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void adjust_present_page_count(struct page *page, struct memory_group *group, long int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426050)
Location: mm/memory_hotplug.c:999
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81426050-ffffffff81426193: adjust_present_page_count (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void adjust_present_page_count(struct page *page, struct memory_group *group, long int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81453290)
Location: mm/memory_hotplug.c:1068
Inline: False
Direct callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_block_online
```
**Symbols:**

```
ffffffff81453290-ffffffff814533d3: adjust_present_page_count (STB_GLOBAL)
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
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct page *page</code>
</li>
<li>
<b>Param added. </b>
<code>struct memory_group *group</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, nr_pages</code> ➡️ <code>page, group, nr_pages</code>
</li>
</ul>
</details>
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
