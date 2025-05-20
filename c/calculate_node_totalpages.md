# Function: <code>calculate_node_totalpages</code>

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
In mm/page_alloc.c (ffffffff8181d3f0)
Location: mm/page_alloc.c:5040
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
In mm/page_alloc.c (ffffffff81897682)
Location: mm/page_alloc.c:5619
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
In mm/page_alloc.c (ffffffff818cbd7e)
Location: mm/page_alloc.c:5658
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
In mm/page_alloc.c (ffffffff819032ef)
Location: mm/page_alloc.c:5955
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
In mm/page_alloc.c (ffffffff8198d1ff)
Location: mm/page_alloc.c:5927
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
In mm/page_alloc.c (ffffffff819e9abf)
Location: mm/page_alloc.c:6065
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
In mm/page_alloc.c (ffffffff828b9150)
Location: mm/page_alloc.c:6311
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
In mm/page_alloc.c (ffffffff828d622d)
Location: mm/page_alloc.c:6499
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
In mm/page_alloc.c (ffffffff828de692)
Location: mm/page_alloc.c:6517
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
void calculate_node_totalpages(struct pglist_data *pgdat, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfbcbf)
Location: mm/page_alloc.c:6542
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff82cfbcbf-ffffffff82cfbe49: calculate_node_totalpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void calculate_node_totalpages(struct pglist_data *pgdat, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe86df)
Location: mm/page_alloc.c:6773
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_node
```
**Symbols:**

```
ffffffff82fe86df-ffffffff82fe8869: calculate_node_totalpages (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff831f2e61)
Location: mm/page_alloc.c:6994
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
In mm/page_alloc.c (ffffffff832d8f8d)
Location: mm/page_alloc.c:7236
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7357
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
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
In mm/page_alloc.c (0)
Location: mm/page_alloc.c:7541
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_node
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void calculate_node_totalpages(struct pglist_data *pgdat, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e0b40)
Location: mm/mm_init.c:1259
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init_node
```
**Symbols:**

```
ffffffff836e0b40-ffffffff836e1177: calculate_node_totalpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void calculate_node_totalpages(struct pglist_data *pgdat, long unsigned int node_start_pfn, long unsigned int node_end_pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83913440)
Location: mm/mm_init.c:1268
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init_node
```
**Symbols:**

```
ffffffff83913440-ffffffff83913a77: calculate_node_totalpages (STB_LOCAL)
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
In mm/page_alloc.c (ffff8000114573d4)
Location: mm/page_alloc.c:6517
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
In mm/page_alloc.c (c15319d0)
Location: mm/page_alloc.c:6517
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
In mm/page_alloc.c (c000000001380988)
Location: mm/page_alloc.c:6517
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
Location: mm/page_alloc.c:6517
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
In mm/page_alloc.c (ffffffff828c7546)
Location: mm/page_alloc.c:6517
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
In mm/page_alloc.c (ffffffff828bfc6b)
Location: mm/page_alloc.c:6517
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
In mm/page_alloc.c (ffffffff828da2c6)
Location: mm/page_alloc.c:6517
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
In mm/page_alloc.c (ffffffff828df6e7)
Location: mm/page_alloc.c:6517
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
