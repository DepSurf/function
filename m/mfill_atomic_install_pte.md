# Function: <code>mfill_atomic_install_pte</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mfill_atomic_install_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, struct page *page, bool newly_allocated, bool wp_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff81366cc0)
Location: mm/userfaultfd.c:57
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff81366cc0-ffffffff8136700b: mfill_atomic_install_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mfill_atomic_install_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, struct page *page, bool newly_allocated, bool wp_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff813e4130)
Location: mm/userfaultfd.c:58
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffffffff813e4130-ffffffff813e4576: mfill_atomic_install_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mfill_atomic_install_pte(struct mm_struct *dst_mm, pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, struct page *page, bool newly_allocated, bool wp_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff8146bbb0)
Location: mm/userfaultfd.c:58
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/userfaultfd.c:mcopy_continue
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8146bbb0-ffffffff8146c047: mfill_atomic_install_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mfill_atomic_install_pte(pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, struct page *page, bool newly_allocated, uffd_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff814a09c0)
Location: mm/userfaultfd.c:54
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff814a09c0-ffffffff814a0df1: mfill_atomic_install_pte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mfill_atomic_install_pte(pmd_t *dst_pmd, struct vm_area_struct *dst_vma, long unsigned int dst_addr, struct page *page, bool newly_allocated, uffd_flags_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/userfaultfd.c (ffffffff814d0110)
Location: mm/userfaultfd.c:70
Inline: False
Direct callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/userfaultfd.c:mfill_atomic_continue
  - mm/userfaultfd.c:mfill_atomic_copy
```
**Symbols:**

```
ffffffff814d0110-ffffffff814d0589: mfill_atomic_install_pte (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>uffd_flags_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool wp_copy</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, dst_pmd, dst_vma, dst_addr, page, newly_allocated, wp_copy</code> ➡️ <code>dst_pmd, dst_vma, dst_addr, page, newly_allocated, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
