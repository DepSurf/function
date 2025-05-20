# Function: <code>copy_huge_pud</code>

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
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812333e0)
Location: mm/huge_memory.c:1032
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812333e0-ffffffff812334d4: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81250d30)
Location: mm/huge_memory.c:1044
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81250d30-ffffffff81250dc0: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812751f0)
Location: mm/huge_memory.c:1041
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812751f0-ffffffff81275282: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128a150)
Location: mm/huge_memory.c:1056
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8128a150-ffffffff8128a1e8: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a4d70)
Location: mm/huge_memory.c:1112
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812a4d70-ffffffff812a4e0a: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b6230)
Location: mm/huge_memory.c:1118
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812b6230-ffffffff812b62ca: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eb350)
Location: mm/huge_memory.c:1175
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812eb350-ffffffff812eb3ea: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7d80)
Location: mm/huge_memory.c:1185
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff812f7d80-ffffffff812f7f32: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fe330)
Location: mm/huge_memory.c:1193
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff812fe330-ffffffff812fe4e8: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81347ed0)
Location: mm/huge_memory.c:1194
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff81347ed0-ffffffff81348090: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bc860)
Location: mm/huge_memory.c:1175
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff813bc860-ffffffff813bc8fe: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143ee20)
Location: mm/huge_memory.c:1240
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff8143ee20-ffffffff8143eeca: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814745e0)
Location: mm/huge_memory.c:1225
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff814745e0-ffffffff81474690: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a3bb0)
Location: mm/huge_memory.c:1442
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff814a3bb0-ffffffff814a3c84: copy_huge_pud (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ae810)
Location: mm/huge_memory.c:1118
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812ae810-ffffffff812ae8aa: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129fda0)
Location: mm/huge_memory.c:1118
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8129fda0-ffffffff8129fe2d: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ac620)
Location: mm/huge_memory.c:1118
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812ac620-ffffffff812ac6ba: copy_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_huge_pud(struct mm_struct *dst_mm, struct mm_struct *src_mm, pud_t *dst_pud, pud_t *src_pud, long unsigned int addr, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bc9a0)
Location: mm/huge_memory.c:1118
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff812bc9a0-ffffffff812bca37: copy_huge_pud (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
