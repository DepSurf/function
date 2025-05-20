# Function: <code>mem_cgroup_try_charge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81200120)
Location: mm/memcontrol.c:5286
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81200120-ffffffff812002ca: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81223ed0)
Location: mm/memcontrol.c:5364
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81223ed0-ffffffff81224078: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812363c0)
Location: mm/memcontrol.c:5349
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812363c0-ffffffff81236573: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81241ec0)
Location: mm/memcontrol.c:5406
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_mcopy_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81241ec0-ffffffff81242026: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81261bf0)
Location: mm/memcontrol.c:5489
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_mm
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81261bf0-ffffffff81261d6f: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81285bf0)
Location: mm/memcontrol.c:5557
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/shmem.c:shmem_mfill_atomic_pte
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/swapfile.c:unuse_vma
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff81285bf0-ffffffff81285d7a: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129ab00)
Location: mm/memcontrol.c:5875
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swapfile.c:unuse_vma
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff8129ab00-ffffffff8129ac8a: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b5da0)
Location: mm/memcontrol.c:6167
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812b5da0-ffffffff812b5f2d: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7c90)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812c7c90-ffffffff812c7e1d: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
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
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036ab68)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swapfile.c:unuse_pte_range
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic_pte
```
**Symbols:**

```
ffff80001036ab68-ffff80001036acf0: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055c174)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swapfile.c:unuse_mm
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c055c174-c055c374: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000459f90)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swapfile.c:unuse_pte_range
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
c000000000459f90-c00000000045a29c: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000248326)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swapfile.c:unuse_pte_range
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffe000248326-ffffffe0002484c2: mem_cgroup_try_charge (STB_GLOBAL)
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
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0270)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812c0270-ffffffff812c03fd: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1340)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/swapfile.c:unuse_pte_range
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812b1340-ffffffff812b14cd: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be080)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812be080-ffffffff812be20d: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_try_charge(struct page *page, struct mm_struct *mm, gfp_t gfp_mask, struct mem_cgroup **memcgp, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cea20)
Location: mm/memcontrol.c:6507
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/filemap.c:__add_to_page_cache_locked
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_huge_page
  - mm/memcontrol.c:mem_cgroup_try_charge_delay
  - mm/userfaultfd.c:mcopy_atomic
```
**Symbols:**

```
ffffffff812cea20-ffffffff812cebf3: mem_cgroup_try_charge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool compound</code>
</li>
</ul>
</details>
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
