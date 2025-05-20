# Function: <code>shmem_mfill_atomic_pte</code>

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
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811eea50)
Location: mm/shmem.c:2248
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff811eea50-ffffffff811ef010: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120f570)
Location: mm/shmem.c:2269
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8120f570-ffffffff8120fb4f: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812224a0)
Location: mm/shmem.c:2231
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff812224a0-ffffffff81222ae9: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81231aa0)
Location: mm/shmem.c:2312
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81231aa0-ffffffff812320e9: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8123fb60)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8123fb60-ffffffff812401a9: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8126e3e0)
Location: mm/shmem.c:2313
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8126e3e0-ffffffff8126ea09: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81278de0)
Location: mm/shmem.c:2355
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81278de0-ffffffff812793ff: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8127dd90)
Location: mm/shmem.c:2343
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8127dd90-ffffffff8127e425: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812bfe10)
Location: mm/shmem.c:2346
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812bfe10-ffffffff812c02af: shmem_mfill_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, bool wp_copy, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8131c6e0)
Location: mm/shmem.c:2342
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8131c6e0-ffffffff8131cc98: shmem_mfill_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, bool wp_copy, struct page **pagep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81390350)
Location: mm/shmem.c:2400
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81390350-ffffffff8139078b: shmem_mfill_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio **foliop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813c2cb0)
Location: mm/shmem.c:2433
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff813c2cb0-ffffffff813c3078: shmem_mfill_atomic_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, uffd_flags_t flags, struct folio **foliop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff813ed940)
Location: mm/shmem.c:2578
Inline: False
Direct callers:
  - mm/userfaultfd.c:mfill_atomic_zeropage
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff813ed940-ffffffff813edb9b: shmem_mfill_atomic_pte (STB_GLOBAL)
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
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffff8000102d2eb8)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffff8000102d2eb8-ffff8000102d365c: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c04fadf0)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
c04fadf0-c04fb57c: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (c000000000391840)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
c000000000391840-c00000000039217c: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffe0001ee138)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffe0001ee138-ffffffe0001ee696: shmem_mfill_atomic_pte (STB_LOCAL)
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
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812381b0)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff812381b0-ffffffff812387f9: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8122b1f0)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff8122b1f0-ffffffff8122b838: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81235f50)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81235f50-ffffffff81236599: shmem_mfill_atomic_pte (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shmem_mfill_atomic_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, long unsigned int src_addr, bool zeropage, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81246230)
Location: mm/shmem.c:2332
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_zeropage_pte
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81246230-ffffffff812468a0: shmem_mfill_atomic_pte (STB_LOCAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool wp_copy</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pmd, dst_vma, dst_addr, src_addr, zeropage, pagep</code> ➡️ <code>dst_mm, dst_pmd, dst_vma, dst_addr, src_addr, zeropage, wp_copy, pagep</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>uffd_flags_t flags</code>
</li>
<li>
<b>Param added. </b>
<code>struct folio **foliop</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool zeropage</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wp_copy</code>
</li>
<li>
<b>Param removed. </b>
<code>struct page **pagep</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pmd, dst_vma, dst_addr, src_addr, zeropage, wp_copy, pagep</code> ➡️ <code>dst_pmd, dst_vma, dst_addr, src_addr, flags, foliop</code>
</li>
</ul>
</details>
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
