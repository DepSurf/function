# Function: <code>find_zone_movable_pfns_for_nodes</code>

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
In mm/page_alloc.c (ffffffff81f87494)
Location: mm/page_alloc.c:5468
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81fb03bb)
Location: mm/page_alloc.c:6056
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff81fb03bb-ffffffff81fb07b8: find_zone_movable_pfns_for_nodes (STB_LOCAL)
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
In mm/page_alloc.c (ffffffff81fecfdd)
Location: mm/page_alloc.c:6095
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
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
In mm/page_alloc.c (ffffffff820cec43)
Location: mm/page_alloc.c:6392
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
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
In mm/page_alloc.c (ffffffff826d765e)
Location: mm/page_alloc.c:6404
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
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
In mm/page_alloc.c (ffffffff82701aac)
Location: mm/page_alloc.c:6547
Inline: True
Inline callers:
  - mm/page_alloc.c:free_area_init_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828b8578)
Location: mm/page_alloc.c:6857
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828b8578-ffffffff828b8b84: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d5696)
Location: mm/page_alloc.c:7053
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828d5696-ffffffff828d5c8a: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828ddb0a)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828ddb0a-ffffffff828de0fe: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82cfaddd)
Location: mm/page_alloc.c:7099
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff82cfaddd-ffffffff82cfb3d7: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff82fe7a52)
Location: mm/page_alloc.c:7246
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff82fe7a52-ffffffff82fe804c: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff831f21b9)
Location: mm/page_alloc.c:7462
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff831f21b9-ffffffff831f2790: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff832d7f25)
Location: mm/page_alloc.c:7704
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff832d7f25-ffffffff832d86d5: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8348d3fa)
Location: mm/page_alloc.c:7855
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff8348d3fa-ffffffff8348dc5e: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff83ebf200)
Location: mm/page_alloc.c:8029
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init
```
**Symbols:**

```
ffffffff83ebf200-ffffffff83ebfc29: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff836e15d0)
Location: mm/mm_init.c:340
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init
```
**Symbols:**

```
ffffffff836e15d0-ffffffff836e1ff7: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mm_init.c (ffffffff83913ed0)
Location: mm/mm_init.c:340
Inline: False
Direct callers:
  - mm/mm_init.c:free_area_init
```
**Symbols:**

```
ffffffff83913ed0-ffffffff83914901: find_zone_movable_pfns_for_nodes (STB_LOCAL)
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
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800011456900)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffff800011456900-ffff800011456d30: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c00000000137f70c)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
c00000000137f70c-c00000000137fd1c: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe000015644)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffe000015644-ffffffe0000158d4: find_zone_movable_pfns_for_nodes (STB_LOCAL)
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
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828c69be)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828c69be-ffffffff828c6fb2: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828bf0e3)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828bf0e3-ffffffff828bf6d7: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828d973e)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828d973e-ffffffff828d9d32: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void find_zone_movable_pfns_for_nodes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff828deb5f)
Location: mm/page_alloc.c:7083
Inline: False
Direct callers:
  - mm/page_alloc.c:free_area_init_nodes
```
**Symbols:**

```
ffffffff828deb5f-ffffffff828df153: find_zone_movable_pfns_for_nodes (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
