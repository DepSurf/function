# Function: <code>ClearPageAnonExclusive</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813402e4)
Location: include/linux/page-flags.h:1033
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135e7c4)
Location: include/linux/page-flags.h:1033
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81391b84)
Location: include/linux/page-flags.h:1033
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a094a)
Location: include/linux/page-flags.h:1033
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff813b7a87)
Location: include/linux/page-flags.h:1033
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff813c1c4e)
Location: include/linux/page-flags.h:1033
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/memory.c (ffffffff813b8274)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff813d99e1)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8140ebd5)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff814200b1)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8143970a)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff81443df7)
Location: include/linux/page-flags.h:1012
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/memory.c (ffffffff813ed162)
Location: include/linux/page-flags.h:1001
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8140debc)
Location: include/linux/page-flags.h:1001
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff81441f8c)
Location: include/linux/page-flags.h:1001
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81454cbf)
Location: include/linux/page-flags.h:1001
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8146fb70)
Location: include/linux/page-flags.h:1001
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff8147933f)
Location: include/linux/page-flags.h:1001
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
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
In mm/memory.c (ffffffff814185a0)
Location: include/linux/page-flags.h:1047
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8143ac84)
Location: include/linux/page-flags.h:1047
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/hugetlb.c (ffffffff8147c2d5)
Location: include/linux/page-flags.h:1047
Inline: True
Inline callers:
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff8148ff91)
Location: include/linux/page-flags.h:1047
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/migrate_device.c (ffffffff8149e241)
Location: include/linux/page-flags.h:1047
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_collect_pmd
```
```
In mm/huge_memory.c (ffffffff814a88a7)
Location: include/linux/page-flags.h:1047
Inline: True
Inline callers:
  - mm/huge_memory.c:set_pmd_migration_entry
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
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
