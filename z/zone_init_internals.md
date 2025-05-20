# Function: <code>zone_init_internals</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b944e)
Location: mm/page_alloc.c:6481
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff828d6545)
Location: mm/page_alloc.c:6673
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff828de9d4)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff82cfb900)
Location: mm/page_alloc.c:6720
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff82fe83a7)
Location: mm/page_alloc.c:6950
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff831f3120)
Location: mm/page_alloc.c:7168
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void zone_init_internals(struct zone *zone, enum zone_type idx, int nid, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81d4ede4)
Location: mm/page_alloc.c:7412
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81d4ede4-ffffffff81d4eea1: zone_init_internals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void zone_init_internals(struct zone *zone, enum zone_type idx, int nid, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81f1ecb7)
Location: mm/page_alloc.c:7537
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
ffffffff81f1ecb7-ffffffff81f1ed81: zone_init_internals (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff83ebe3f5)
Location: mm/page_alloc.c:7722
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_core
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/mm_init.c (ffffffff836e1224)
Location: mm/mm_init.c:1364
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
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
In mm/mm_init.c (ffffffff83913b24)
Location: mm/mm_init.c:1373
Inline: True
Inline callers:
  - mm/mm_init.c:free_area_init_core
  - mm/mm_init.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffff8000114576f0)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c1531bd8)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void zone_init_internals(struct zone *zone, enum zone_type idx, int nid, long unsigned int remaining_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000000eec3dc)
Location: mm/page_alloc.c:6693
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
**Symbols:**

```
c000000000eec3dc-c000000000eec48c: zone_init_internals (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0000161a4)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
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
In mm/page_alloc.c (ffffffff828c7888)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff828bffad)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff828da608)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
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
In mm/page_alloc.c (ffffffff828dfa29)
Location: mm/page_alloc.c:6693
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_core_hotplug
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
