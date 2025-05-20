# Function: <code>zone_span_writelock</code>

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
In mm/memory_hotplug.c (ffffffff81208f2b)
Location: include/linux/memory_hotplug.h:71
Inline: True
Inline callers:
  - mm/memory_hotplug.c:resize_zone
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:__remove_pages
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
In mm/memory_hotplug.c (ffffffff8120e708)
Location: include/linux/memory_hotplug.h:71
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
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
In mm/memory_hotplug.c (ffffffff81220748)
Location: include/linux/memory_hotplug.h:71
Inline: True
Inline callers:
  - mm/memory_hotplug.c:__remove_pages
  - mm/memory_hotplug.c:__add_pages
  - mm/memory_hotplug.c:resize_zone
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
In mm/memory_hotplug.c (ffffffff818ff4b4)
Location: include/linux/memory_hotplug.h:85
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819895b4)
Location: include/linux/memory_hotplug.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff819e5e87)
Location: include/linux/memory_hotplug.h:69
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:__remove_pages
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
In mm/memory_hotplug.c (ffffffff81a21213)
Location: include/linux/memory_hotplug.h:71
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81a918b8)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81ac9058)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81bc1778)
Location: include/linux/memory_hotplug.h:86
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
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
In mm/memory_hotplug.c (ffffffff81c3a77c)
Location: include/linux/memory_hotplug.h:99
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
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
In mm/memory_hotplug.c (ffffffff81c2cd5c)
Location: include/linux/memory_hotplug.h:95
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:shrink_zone_span
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
In mm/memory_hotplug.c (ffff800010d9cca0)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (c00000000042fb44)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81a67ec8)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81a24988)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81ad42d8)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
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
In mm/memory_hotplug.c (ffffffff81ae07c6)
Location: include/linux/memory_hotplug.h:81
Inline: True
Inline callers:
  - mm/memory_hotplug.c:move_pfn_range_to_zone
  - mm/memory_hotplug.c:remove_pfn_range_from_zone
```
</details>
</li>
</ul>

## Differences
