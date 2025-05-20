# Function: <code>copy_page_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c0d00)
Location: mm/memory.c:1006
Inline: False
Direct callers:
  - kernel/fork.c:copy_process
```
**Symbols:**

```
ffffffff811c0d00-ffffffff811c1753: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dc6f0)
Location: mm/memory.c:1042
Inline: False
```
**Symbols:**

```
ffffffff811dc6f0-ffffffff811dd223: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ec200)
Location: mm/memory.c:1044
Inline: False
```
**Symbols:**

```
ffffffff811ec200-ffffffff811ecd19: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f7110)
Location: mm/memory.c:1144
Inline: False
```
**Symbols:**

```
ffffffff811f7110-ffffffff811f7c31: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120f6b0)
Location: mm/memory.c:1212
Inline: False
```
**Symbols:**

```
ffffffff8120f6b0-ffffffff8120fd44: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81230480)
Location: mm/memory.c:1226
Inline: False
Direct callers:
  - kernel/fork.c:copy_mm
```
**Symbols:**

```
ffffffff81230480-ffffffff81230a98: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812437e0)
Location: mm/memory.c:969
Inline: False
```
**Symbols:**

```
ffffffff812437e0-ffffffff81243e3a: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81255630)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81255630-ffffffff81255cc1: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81263ba0)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81263ba0-ffffffff8126425a: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81293d50)
Location: mm/memory.c:965
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81293d50-ffffffff8129463a: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129ec20)
Location: mm/memory.c:1127
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8129ec20-ffffffff8129eeb9: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a4f00)
Location: mm/memory.c:1134
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff812a4f00-ffffffff812a519e: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1225
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81cbc413-ffffffff81cbc4fe: copy_page_range.cold (STB_LOCAL)
ffffffff812e4100-ffffffff812e43bd: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1264
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81e6e14f-ffffffff81e6e25f: copy_page_range.cold (STB_LOCAL)
ffffffff81347200-ffffffff813474fc: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1221
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff82064150-ffffffff82064260: copy_page_range.cold (STB_LOCAL)
ffffffff813bf600-ffffffff813bf8ee: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1268
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff820e384e-ffffffff820e393b: copy_page_range.cold (STB_LOCAL)
ffffffff813f4280-ffffffff813f45a1: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int copy_page_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory.c (0)
Location: mm/memory.c:1288
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff821c0283-ffffffff821c0370: copy_page_range.cold (STB_LOCAL)
ffffffff8141ef10-ffffffff8141f22f: copy_page_range (STB_GLOBAL)
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
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fa460)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffff8000102fa460-ffff8000102fa84c: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0518a9c)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
c0518a9c-c0518c9c: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c4600)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
c0000000003c4600-c0000000003c4e94: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000209c18)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffe000209c18-ffffffe00020a316: copy_page_range (STB_GLOBAL)
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
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125c1f0)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8125c1f0-ffffffff8125c8aa: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124e780)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff8124e780-ffffffff8124edac: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81259f90)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81259f90-ffffffff8125a64a: copy_page_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_page_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81269990)
Location: mm/memory.c:937
Inline: False
Direct callers:
  - kernel/fork.c:dup_mmap
```
**Symbols:**

```
ffffffff81269990-ffffffff8126a021: copy_page_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *dst_vma</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *src_vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *src_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
