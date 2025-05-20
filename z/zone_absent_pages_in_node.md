# Function: <code>zone_absent_pages_in_node</code>

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
In mm/page_alloc.c (ffffffff8181d3fb)
Location: mm/page_alloc.c:4993
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff81897730)
Location: mm/page_alloc.c:5529
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff818cbd8e)
Location: mm/page_alloc.c:5573
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff81903306)
Location: mm/page_alloc.c:5870
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff8198d216)
Location: mm/page_alloc.c:5842
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff819e9b66)
Location: mm/page_alloc.c:5980
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff828b91f0)
Location: mm/page_alloc.c:6226
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff828d62e0)
Location: mm/page_alloc.c:6414
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff828de761)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int zone_absent_pages_in_node(int nid, long unsigned int zone_type, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfbb7f)
Location: mm/page_alloc.c:6492
Inline: False
Direct callers:
  - mm/page_alloc.c:calculate_node_totalpages
```
**Symbols:**

```
ffffffff82cfbb7f-ffffffff82cfbcbf: zone_absent_pages_in_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int zone_absent_pages_in_node(int nid, long unsigned int zone_type, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe859f)
Location: mm/page_alloc.c:6723
Inline: False
Direct callers:
  - mm/page_alloc.c:calculate_node_totalpages
```
**Symbols:**

```
ffffffff82fe859f-ffffffff82fe86df: zone_absent_pages_in_node (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff831f2f60)
Location: mm/page_alloc.c:6944
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff832d909e)
Location: mm/page_alloc.c:7186
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff8348de8e)
Location: mm/page_alloc.c:7307
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int zone_absent_pages_in_node(int nid, long unsigned int zone_type, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebfd40)
Location: mm/page_alloc.c:7491
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff83ebfd40-ffffffff83ebff5d: zone_absent_pages_in_node (STB_LOCAL)
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
In mm/mm_init.c (ffffffff836e0c63)
Location: mm/mm_init.c:1167
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
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
In mm/mm_init.c (ffffffff83913563)
Location: mm/mm_init.c:1177
Inline: True
Inline callers:
  - mm/mm_init.c:calculate_node_totalpages
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
In mm/page_alloc.c (ffff80001145748c)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (c15319ec)
Location: mm/page_alloc.c:6503
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c000000001380a48)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffe000015e62)
Location: mm/page_alloc.c:6432
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
In mm/page_alloc.c (ffffffff828c7615)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff828bfd3a)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff828da395)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (ffffffff828df7b6)
Location: mm/page_alloc.c:6432
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
