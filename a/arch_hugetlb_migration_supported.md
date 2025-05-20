# Function: <code>arch_hugetlb_migration_supported</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81272dd2)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81282e7a)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff8129f99e)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81281c32)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8129299a)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff812b0d3e)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b4027)
Location: include/linux/hugetlb.h:650
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812c715d)
Location: include/linux/hugetlb.h:650
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812ce748)
Location: include/linux/hugetlb.h:650
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff812e5e81)
Location: include/linux/hugetlb.h:650
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bfabc)
Location: include/linux/hugetlb.h:648
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812cfa80)
Location: include/linux/hugetlb.h:648
Inline: True
Inline callers:
  - mm/hugetlb.c:allowed_mems_nr
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff812da088)
Location: include/linux/hugetlb.h:648
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff812f1246)
Location: include/linux/hugetlb.h:648
Inline: True
Inline callers:
  - mm/migrate.c:unmap_and_move_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c521c)
Location: include/linux/hugetlb.h:750
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff812d963a)
Location: include/linux/hugetlb.h:750
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff812e18e8)
Location: include/linux/hugetlb.h:750
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff812f376d)
Location: include/linux/hugetlb.h:750
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81309769)
Location: include/linux/hugetlb.h:773
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff813200dd)
Location: include/linux/hugetlb.h:773
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/mempolicy.c (ffffffff813289b8)
Location: include/linux/hugetlb.h:773
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff8133dccf)
Location: include/linux/hugetlb.h:773
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8138d00d)
Location: include/linux/hugetlb.h:803
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff81397bfc)
Location: include/linux/hugetlb.h:803
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff813b17bd)
Location: include/linux/hugetlb.h:803
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_isolation.c (ffffffff813ddd4e)
Location: include/linux/hugetlb.h:803
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff83ec3172)
Location: include/linux/hugetlb.h:855
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_huge_page_vma
```
```
In mm/mempolicy.c (ffffffff81417809)
Location: include/linux/hugetlb.h:855
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff81432b23)
Location: include/linux/hugetlb.h:855
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:unmap_and_move_huge_page
```
```
In mm/page_isolation.c (ffffffff814649f2)
Location: include/linux/hugetlb.h:855
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff836e8252)
Location: include/linux/hugetlb.h:883
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_hugetlb_folio_vma
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/mempolicy.c (ffffffff8144ad9c)
Location: include/linux/hugetlb.h:883
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
```
```
In mm/migrate.c (ffffffff8146748e)
Location: include/linux/hugetlb.h:883
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_hugetlbs
```
```
In mm/page_isolation.c (ffffffff8149a4f2)
Location: include/linux/hugetlb.h:883
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8147a279)
Location: include/linux/hugetlb.h:905
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_hugetlb_folio
  - mm/hugetlb.c:alloc_and_dissolve_hugetlb_folio
  - mm/hugetlb.c:gather_surplus_pages
  - mm/hugetlb.c:alloc_pool_huge_folio
  - mm/hugetlb.c:dequeue_hugetlb_folio_vma
```
```
In mm/mempolicy.c (ffffffff814847dc)
Location: include/linux/hugetlb.h:905
Inline: True
Inline callers:
  - mm/mempolicy.c:vma_migratable
  - mm/mempolicy.c:alloc_migration_target_by_mpol
```
```
In mm/migrate.c (ffffffff81496618)
Location: include/linux/hugetlb.h:905
Inline: True
Inline callers:
  - mm/migrate.c:alloc_migration_target
  - mm/migrate.c:migrate_hugetlbs
```
```
In mm/page_isolation.c (ffffffff814c9cd8)
Location: include/linux/hugetlb.h:905
Inline: True
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
bool arch_hugetlb_migration_supported(struct hstate *h);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/hugetlbpage.c (ffff8000100b09d0)
Location: arch/arm64/mm/hugetlbpage.c:23
Inline: False
Direct callers:
  - mm/page_alloc.c:has_unmovable_pages
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
  - mm/migrate.c:migrate_pages
```
**Symbols:**

```
ffff8000100b09d0-ffff8000100b0a54: arch_hugetlb_migration_supported (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ed490)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (c000000000408e98)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (c000000000437530)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (0)
Location: include/linux/hugetlb.h:498
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/hugetlb.h:498
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:498
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127a282)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8128af7a)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff812a931e)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126c172)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff8127cdaa)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff8129ac7e)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278022)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81288d8a)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff812a712e)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81287c12)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/page_alloc.c:has_unmovable_pages
```
```
In mm/hugetlb.c (ffffffff81298b31)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_acct_memory
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:alloc_huge_page_vma
  - mm/hugetlb.c:alloc_huge_page_nodemask
  - mm/hugetlb.c:alloc_huge_page_node
  - mm/hugetlb.c:alloc_pool_huge_page
```
```
In mm/migrate.c (ffffffff812b743e)
Location: include/linux/hugetlb.h:487
Inline: True
Inline callers:
  - mm/migrate.c:migrate_pages
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
