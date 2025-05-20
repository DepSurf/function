# Function: <code>copy_nonpresent_pte</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81297500)
Location: mm/memory.c:698
Inline: True
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff81297500-ffffffff81297819: copy_nonpresent_pte.constprop.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8129da80)
Location: mm/memory.c:710
Inline: True
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff8129da80-ffffffff8129dd69: copy_nonpresent_pte.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int copy_nonpresent_pte(struct mm_struct *dst_mm, struct mm_struct *src_mm, pte_t *dst_pte, pte_t *src_pte, struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, long unsigned int addr, int *rss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dea30)
Location: mm/memory.c:771
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff812dea30-ffffffff812ded5f: copy_nonpresent_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int copy_nonpresent_pte(struct mm_struct *dst_mm, struct mm_struct *src_mm, pte_t *dst_pte, pte_t *src_pte, struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, long unsigned int addr, int *rss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8133eee0)
Location: mm/memory.c:777
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff8133eee0-ffffffff8133f2b4: copy_nonpresent_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int copy_nonpresent_pte(struct mm_struct *dst_mm, struct mm_struct *src_mm, pte_t *dst_pte, pte_t *src_pte, struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, long unsigned int addr, int *rss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b62c0)
Location: mm/memory.c:738
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff813b62c0-ffffffff813b667c: copy_nonpresent_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int copy_nonpresent_pte(struct mm_struct *dst_mm, struct mm_struct *src_mm, pte_t *dst_pte, pte_t *src_pte, struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, long unsigned int addr, int *rss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ebc20)
Location: mm/memory.c:769
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff813ebc20-ffffffff813ec0a8: copy_nonpresent_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int copy_nonpresent_pte(struct mm_struct *dst_mm, struct mm_struct *src_mm, pte_t *dst_pte, pte_t *src_pte, struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, long unsigned int addr, int *rss);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81416af0)
Location: mm/memory.c:779
Inline: False
Direct callers:
  - mm/memory.c:copy_pte_range
```
**Symbols:**

```
ffffffff81416af0-ffffffff81416f8a: copy_nonpresent_pte (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
