# Function: <code>mmu_notifier_invalidate_range_only_end</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812090dc)
Location: include/linux/mmu_notifier.h:275
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff8124c7eb)
Location: include/linux/mmu_notifier.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff812527c5)
Location: include/linux/mmu_notifier.h:275
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a02c)
Location: include/linux/mmu_notifier.h:294
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff81270364)
Location: include/linux/mmu_notifier.h:294
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
```
In mm/huge_memory.c (ffffffff81276bee)
Location: include/linux/mmu_notifier.h:294
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123d608)
Location: include/linux/mmu_notifier.h:295
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff81284a19)
Location: include/linux/mmu_notifier.h:295
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
```
```
In mm/huge_memory.c (ffffffff8128bb2c)
Location: include/linux/mmu_notifier.h:295
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f294)
Location: include/linux/mmu_notifier.h:337
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/huge_memory.c (ffffffff812a6765)
Location: include/linux/mmu_notifier.h:337
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8125d851)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812af6ce)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812b7c3e)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8128d137)
Location: include/linux/mmu_notifier.h:477
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812e57c7)
Location: include/linux/mmu_notifier.h:477
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812ece21)
Location: include/linux/mmu_notifier.h:477
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
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
In mm/memory.c (ffffffff812980f5)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812f0b98)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812f8072)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
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
In mm/memory.c (ffffffff8129d780)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812f6eea)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812fe622)
Location: include/linux/mmu_notifier.h:483
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
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
In mm/memory.c (ffffffff812dde64)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff8134154a)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff813481c3)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
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
In mm/memory.c (ffffffff8133decf)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate_device.c (ffffffff813b849e)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff813be4d9)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
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
In mm/memory.c (ffffffff813b6fa9)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate_device.c (ffffffff8143a274)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
```
```
In mm/huge_memory.c (ffffffff81440d2e)
Location: include/linux/mmu_notifier.h:489
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
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
In mm/memory.c (ffffffff813eb8ec)
Location: include/linux/mmu_notifier.h:488
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate_device.c (ffffffff8146eee9)
Location: include/linux/mmu_notifier.h:488
Inline: True
Inline callers:
  - mm/migrate_device.c:__migrate_device_pages
```
```
In mm/huge_memory.c (ffffffff814765d2)
Location: include/linux/mmu_notifier.h:488
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:__split_huge_pud
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f4e74)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/huge_memory.c (ffff8000103584f0)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0517018)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bbb78)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (c000000000433a68)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (c000000000440dc4)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002062ac)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
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
In mm/memory.c (ffffffff81255ea1)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812a7cae)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812b021e)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8124852e)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff8129966e)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812a16ef)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff81253c41)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812a5abe)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812ae02e)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
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
In mm/memory.c (ffffffff8126365e)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/memory.c:wp_page_copy
```
```
In mm/migrate.c (ffffffff812b5232)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_pages
```
```
In mm/huge_memory.c (ffffffff812be383)
Location: include/linux/mmu_notifier.h:381
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pud
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
</details>
</li>
</ul>

## Differences
