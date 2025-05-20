# Function: <code>pmdp_invalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d0670)
Location: mm/pgtable-generic.c:191
Inline: False
Direct callers:
  - mm/huge_memory.c:split_huge_page_to_list
```
**Symbols:**

```
ffffffff811d0670-ffffffff811d06c0: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed7e0)
Location: mm/pgtable-generic.c:162
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811ed7e0-ffffffff811ed830: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f7bb0)
Location: mm/pgtable-generic.c:162
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd
```
**Symbols:**

```
ffffffff811f7bb0-ffffffff811f7c00: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202da0)
Location: mm/pgtable-generic.c:182
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81202da0-ffffffff81202df0: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121bb00)
Location: mm/pgtable-generic.c:184
Inline: False
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8121bb00-ffffffff8121bb26: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d8b0)
Location: mm/pgtable-generic.c:184
Inline: False
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8123d8b0-ffffffff8123d974: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251e60)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81251e60-ffffffff81251f4f: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81264140)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81264140-ffffffff8126423d: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812729b0)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812729b0-ffffffff81272aad: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a3770)
Location: mm/pgtable-generic.c:194
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812a3770-ffffffff812a3871: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812af050)
Location: mm/pgtable-generic.c:194
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812af050-ffffffff812af14c: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b4580)
Location: mm/pgtable-generic.c:194
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812b4580-ffffffff812b45f5: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f6160)
Location: mm/pgtable-generic.c:194
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff812f6160-ffffffff812f61d5: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8135a170)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8135a170-ffffffff8135a1f5: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d4bf0)
Location: mm/pgtable-generic.c:195
Inline: False
Direct callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff813d4bf0-ffffffff813d4c72: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff814095c0)
Location: mm/pgtable-generic.c:197
Inline: False
Direct callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff814095c0-ffffffff814096e0: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435db0)
Location: mm/pgtable-generic.c:198
Inline: False
Direct callers:
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81435db0-ffffffff81435ed0: pmdp_invalidate (STB_GLOBAL)
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
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010308440)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
ffff800010308440-ffff800010308570: pmdp_invalidate (STB_GLOBAL)
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
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/pgtable.c (c000000000090c60)
Location: arch/powerpc/mm/book3s64/pgtable.c:105
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
c000000000090c60-c000000000090d68: pmdp_invalidate (STB_GLOBAL)
```
</details>
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
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126b000)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8126b000-ffffffff8126b0fd: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125d030)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff8125d030-ffffffff8125d101: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268da0)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81268da0-ffffffff81268e9d: pmdp_invalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pmd_t pmdp_invalidate(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81278730)
Location: mm/pgtable-generic.c:185
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
  - fs/dax.c:dax_entry_mkclean
  - fs/proc/task_mmu.c:clear_refs_pte_range
```
**Symbols:**

```
ffffffff81278730-ffffffff8127882d: pmdp_invalidate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>pmd_t</code>
</li>
</ul>
</details>
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
