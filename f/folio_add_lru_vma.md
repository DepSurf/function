# Function: <code>folio_add_lru_vma</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void folio_add_lru_vma(struct folio *folio, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81370ab0)
Location: mm/swap.c:560
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/memory.c:do_swap_page
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff81370ab0-ffffffff81370aec: folio_add_lru_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void folio_add_lru_vma(struct folio *folio, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813a2c90)
Location: mm/swap.c:530
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/folio-compat.c:lru_cache_add_inactive_or_unevictable
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff813a2c90-ffffffff813a2ccc: folio_add_lru_vma (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void folio_add_lru_vma(struct folio *folio, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff813cc910)
Location: mm/swap.c:530
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__replace_page
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/swapfile.c:unuse_pte
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff813cc910-ffffffff813cc94c: folio_add_lru_vma (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
