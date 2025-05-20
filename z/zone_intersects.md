# Function: <code>zone_intersects</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff818ff631)
Location: include/linux/mmzone.h:539
Inline: True
Inline callers:
  - mm/memory_hotplug.c:online_pages
  - mm/memory_hotplug.c:online_pages
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
In mm/memory_hotplug.c (ffffffff8124888e)
Location: include/linux/mmzone.h:548
Inline: True
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
In mm/memory_hotplug.c (ffffffff8126c2c9)
Location: include/linux/mmzone.h:549
Inline: True
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
In mm/memory_hotplug.c (ffffffff81280b69)
Location: include/linux/mmzone.h:558
Inline: True
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
In mm/memory_hotplug.c (ffffffff8129cf79)
Location: include/linux/mmzone.h:614
Inline: True
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
In mm/memory_hotplug.c (ffffffff812ac749)
Location: include/linux/mmzone.h:615
Inline: True
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
In mm/memory_hotplug.c (ffffffff812e1898)
Location: include/linux/mmzone.h:580
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
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
In mm/memory_hotplug.c (ffffffff812ec7e5)
Location: include/linux/mmzone.h:631
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
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
In mm/memory_hotplug.c (ffffffff812c707d)
Location: include/linux/mmzone.h:680
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
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
In mm/memory_hotplug.c (ffffffff8130ba0b)
Location: include/linux/mmzone.h:716
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81374a06)
Location: include/linux/mmzone.h:737
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
```
In drivers/base/memory.c (ffffffff819a4a79)
Location: include/linux/mmzone.h:737
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2346)
Location: include/linux/mmzone.h:1037
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
```
In drivers/base/memory.c (ffffffff81b16b49)
Location: include/linux/mmzone.h:1037
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81425d86)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
```
In drivers/base/memory.c (ffffffff81b658b9)
Location: include/linux/mmzone.h:1153
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81452fc6)
Location: include/linux/mmzone.h:1163
Inline: True
Inline callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
```
In drivers/base/memory.c (ffffffff81bb9739)
Location: include/linux/mmzone.h:1163
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_block_add_nid
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
In mm/memory_hotplug.c (ffff80001034e350)
Location: include/linux/mmzone.h:615
Inline: True
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
In mm/memory_hotplug.c (c00000000042eae4)
Location: include/linux/mmzone.h:615
Inline: True
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
In mm/memory_hotplug.c (ffffffff812a4d29)
Location: include/linux/mmzone.h:615
Inline: True
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
In mm/memory_hotplug.c (ffffffff812967f9)
Location: include/linux/mmzone.h:615
Inline: True
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
In mm/memory_hotplug.c (ffffffff812a2b39)
Location: include/linux/mmzone.h:615
Inline: True
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
In mm/memory_hotplug.c (ffffffff812b2dc9)
Location: include/linux/mmzone.h:615
Inline: True
```
</details>
</li>
</ul>

## Differences
