# Function: <code>subsection_mask_set</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8128d9e0)
Location: mm/sparse.c:220
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff8128d9e0-ffffffff8128da0b: subsection_mask_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8129d630)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff8129d630-ffffffff8129d65b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d1260)
Location: mm/sparse.c:212
Inline: False
Direct callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff812d1260-ffffffff812d128b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812dcd80)
Location: mm/sparse.c:211
Inline: False
Direct callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:clear_subsection_map
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff812dcd80-ffffffff812dcdab: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812e45f0)
Location: mm/sparse.c:211
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff812e45f0-ffffffff812e461b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8132b900)
Location: mm/sparse.c:185
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff8132b900-ffffffff8132b92b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8139b520)
Location: mm/sparse.c:185
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff8139b520-ffffffff8139b557: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8141b550)
Location: mm/sparse.c:185
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff8141b550-ffffffff8141b587: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8144eaf0)
Location: mm/sparse.c:185
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff8144eaf0-ffffffff8144eb27: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81488690)
Location: mm/sparse.c:184
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff81488690-ffffffff814886c7: subsection_mask_set (STB_LOCAL)
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
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffff80001033c6d8)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffff80001033c6d8-ffff80001033c730: subsection_mask_set (STB_LOCAL)
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
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (c0000000004177d0)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:section_activate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
c0000000004177d0-c000000000417820: subsection_mask_set (STB_LOCAL)
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
In mm/sparse.c (ffffffe000018542)
Location: mm/sparse.c:222
Inline: True
Inline callers:
  - mm/sparse.c:subsection_map_init
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
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81295c10)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff81295c10-ffffffff81295c3b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81287820)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff81287820-ffffffff8128784b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81293a20)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff81293a20-ffffffff81293a4b: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void subsection_mask_set(long unsigned int *map, long unsigned int pfn, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812a3880)
Location: mm/sparse.c:222
Inline: False
Direct callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:section_deactivate
  - mm/sparse.c:subsection_map_init
```
**Symbols:**

```
ffffffff812a3880-ffffffff812a38ab: subsection_mask_set (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
