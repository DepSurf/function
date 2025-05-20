# Function: <code>shmem_mfill_zeropage_pte</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2a30)
Location: mm/shmem.c:2369
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff811f2a30-ffffffff811f2a7d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81213e90)
Location: mm/shmem.c:2390
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81213e90-ffffffff81213edd: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81226e50)
Location: mm/shmem.c:2374
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81226e50-ffffffff81226e9d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812369b0)
Location: mm/shmem.c:2455
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff812369b0-ffffffff812369fd: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81244bf0)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81244bf0-ffffffff81244c3d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812728b0)
Location: mm/shmem.c:2447
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff812728b0-ffffffff812728fd: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127cd50)
Location: mm/shmem.c:2489
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff8127cd50-ffffffff8127cd9d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81281ef0)
Location: mm/shmem.c:2487
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81281ef0-ffffffff81281f3d: shmem_mfill_zeropage_pte (STB_GLOBAL)
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
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d72c8)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffff8000102d72c8-ffff8000102d7350: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04ff0bc)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
c04ff0bc-c04ff12c: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c0000000003974b0)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
c0000000003974b0-c00000000039751c: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001f2578)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffe0001f2578-ffffffe0001f25c6: shmem_mfill_zeropage_pte (STB_GLOBAL)
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
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123d240)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff8123d240-ffffffff8123d28d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81230240)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff81230240-ffffffff8123028d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123afe0)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff8123afe0-ffffffff8123b02d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_mfill_zeropage_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8124a6f0)
Location: mm/shmem.c:2475
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
```
**Symbols:**

```
ffffffff8124a6f0-ffffffff8124a73d: shmem_mfill_zeropage_pte (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
