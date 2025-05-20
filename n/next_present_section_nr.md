# Function: <code>next_present_section_nr</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
int next_present_section_nr(int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8121f651)
Location: mm/sparse.c:191
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
```
**Symbols:**

```
ffffffff8121f651-ffffffff8121f694: next_present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int next_present_section_nr(int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff8123a85d)
Location: mm/sparse.c:187
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
```
**Symbols:**

```
ffffffff8123a85d-ffffffff8123a892: next_present_section_nr (STB_LOCAL)
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
In mm/sparse.c (ffffffff827088dc)
Location: mm/sparse.c:187
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
  - mm/sparse.c:alloc_usemap_and_memmap
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
In mm/sparse.c (ffffffff828bfcd9)
Location: mm/sparse.c:188
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff828d9041)
Location: mm/sparse.c:199
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff828e1494)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff812d16f1)
Location: include/linux/mmzone.h:1346
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff812d16f1-ffffffff812d172a: next_present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81be8aed)
Location: include/linux/mmzone.h:1384
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81be8aed-ffffffff81be8b26: next_present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81bdab19)
Location: include/linux/mmzone.h:1454
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81bdab19-ffffffff81bdab52: next_present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81cc05bc)
Location: include/linux/mmzone.h:1511
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81cc05bc-ffffffff81cc05f5: next_present_section_nr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int next_present_section_nr(long unsigned int section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/sparse.c (ffffffff81e729ad)
Location: include/linux/mmzone.h:1557
Inline: False
Direct callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
**Symbols:**

```
ffffffff81e729ad-ffffffff81e729e5: next_present_section_nr (STB_LOCAL)
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
In mm/sparse.c (ffffffff83ec5634)
Location: include/linux/mmzone.h:1896
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff836ea656)
Location: include/linux/mmzone.h:2021
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff8391da16)
Location: include/linux/mmzone.h:2039
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffff80001145a668)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (c0000000013846e0)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffe0000187a4)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff828ca348)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff828c2a6d)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff828dd0c8)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
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
In mm/sparse.c (ffffffff828e24df)
Location: mm/sparse.c:201
Inline: True
Inline callers:
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
  - mm/sparse.c:sparse_init_nid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
