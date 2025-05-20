# Function: <code>pgdat_resize_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8181f060)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_one_section
  - mm/sparse.c:sparse_remove_one_section
```
```
In mm/memory_hotplug.c (ffffffff818197a8)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
```
```
In lib/show_mem.c (ffffffff813f16a1)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8120229e)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff81893810)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
```
In lib/show_mem.c (ffffffff8143802f)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812140de)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff818c820b)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
```
```
In lib/show_mem.c (ffffffff8145501f)
Location: include/linux/memory_hotplug.h:47
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f4e0)
Location: include/linux/memory_hotplug.h:61
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff818ff832)
Location: include/linux/memory_hotplug.h:61
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In lib/show_mem.c (ffffffff818f5155)
Location: include/linux/memory_hotplug.h:61
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a711)
Location: include/linux/memory_hotplug.h:62
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff81989d01)
Location: include/linux/memory_hotplug.h:62
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In lib/show_mem.c (ffffffff8197bb55)
Location: include/linux/memory_hotplug.h:62
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8125dcb4)
Location: include/linux/memory_hotplug.h:284
Inline: True
Inline callers:
  - mm/sparse.c:sparse_remove_one_section
  - mm/sparse.c:sparse_add_one_section
```
```
In mm/memory_hotplug.c (ffffffff819e6842)
Location: include/linux/memory_hotplug.h:284
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
```
In lib/show_mem.c (ffffffff819d80d0)
Location: include/linux/memory_hotplug.h:284
Inline: True
Inline callers:
  - lib/show_mem.c:show_mem
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a21d93)
Location: include/linux/memory_hotplug.h:286
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81a923f4)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
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
In mm/memory_hotplug.c (ffffffff81ac9b85)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81bc2158)
Location: include/linux/memory_hotplug.h:304
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81c3b23e)
Location: include/linux/memory_hotplug.h:301
Inline: True
Inline callers:
  - mm/memory_hotplug.c:offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
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
In mm/memory_hotplug.c (ffffffff81c2d0b6)
Location: include/linux/memory_hotplug.h:308
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In mm/memory_hotplug.c (ffff800010d9d0a4)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
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
In mm/memory_hotplug.c (c000000000430b38)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
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
In mm/memory_hotplug.c (ffffffff81a689f5)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
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
In mm/memory_hotplug.c (ffffffff81a254b5)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
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
In mm/memory_hotplug.c (ffffffff81ad4e05)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
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
In mm/memory_hotplug.c (ffffffff81ae12e0)
Location: include/linux/memory_hotplug.h:298
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__offline_pages
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
</ul>

## Differences
