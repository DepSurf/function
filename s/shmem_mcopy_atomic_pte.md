# Function: <code>shmem_mcopy_atomic_pte</code>

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
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dcb60)
Location: mm/shmem.c:2237
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811dcb60-ffffffff811dd02b: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2a10)
Location: mm/shmem.c:2358
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff811f2a10-ffffffff811f2a25: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213e70)
Location: mm/shmem.c:2379
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81213e70-ffffffff81213e85: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81226e30)
Location: mm/shmem.c:2363
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81226e30-ffffffff81226e45: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81236990)
Location: mm/shmem.c:2444
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81236990-ffffffff812369a5: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244bd0)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81244bd0-ffffffff81244be5: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81272890)
Location: mm/shmem.c:2436
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81272890-ffffffff812728a5: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127cd30)
Location: mm/shmem.c:2478
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8127cd30-ffffffff8127cd45: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281ed0)
Location: mm/shmem.c:2476
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81281ed0-ffffffff81281ee5: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d7260)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffff8000102d7260-ffff8000102d72c8: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04ff080)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c04ff080-c04ff0bc: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000397490)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c000000000397490-c0000000003974ac: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f2524)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe0001f2524-ffffffe0001f2578: shmem_mcopy_atomic_pte (STB_GLOBAL)
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
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d220)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8123d220-ffffffff8123d235: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230220)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81230220-ffffffff81230235: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123afc0)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8123afc0-ffffffff8123afd5: shmem_mcopy_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_mcopy_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124a6d0)
Location: mm/shmem.c:2464
Inline: False
Direct callers:
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8124a6d0-ffffffff8124a6e5: shmem_mcopy_atomic_pte (STB_GLOBAL)
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
