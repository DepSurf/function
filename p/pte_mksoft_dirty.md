# Function: <code>pte_mksoft_dirty</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bff03)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mremap.c (ffffffff811c96c8)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff811f0d51)
Location: arch/x86/include/asm/pgtable.h:318
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d9f0c)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff811e5a7c)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff8120ffbb)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812163c4)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e9a33)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff811f5cd8)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff812220e3)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228972)
Location: arch/x86/include/asm/pgtable.h:347
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f4b11)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff81200ac3)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff8122df6a)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fea)
Location: arch/x86/include/asm/pgtable.h:468
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120cb83)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff81219511)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff81249cae)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252d6b)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff8123ada8)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff8126d4ea)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812771ed)
Location: arch/x86/include/asm/pgtable.h:483
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:485
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff8124ef9b)
Location: arch/x86/include/asm/pgtable.h:485
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff81281bda)
Location: arch/x86/include/asm/pgtable.h:485
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81288a31)
Location: arch/x86/include/asm/pgtable.h:485
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff812612fa)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff8129dce6)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3677)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff8126fa9d)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff812ad596)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4b77)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:541
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff812a00e2)
Location: arch/x86/include/asm/pgtable.h:541
Inline: True
```
```
In mm/migrate.c (ffffffff812e290d)
Location: arch/x86/include/asm/pgtable.h:541
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea11d)
Location: arch/x86/include/asm/pgtable.h:541
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff812ab542)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/migrate.c (ffffffff812edd3f)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f52f3)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff812b0945)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
```
```
In mm/migrate.c (ffffffff812f3eee)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb83d)
Location: arch/x86/include/asm/pgtable.h:540
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff812de95a)
Location: arch/x86/include/asm/pgtable.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mremap.c (ffffffff812f22d5)
Location: arch/x86/include/asm/pgtable.h:511
Inline: True
```
```
In mm/migrate.c (ffffffff8133e91f)
Location: arch/x86/include/asm/pgtable.h:511
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81345678)
Location: arch/x86/include/asm/pgtable.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff8133ebef)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mremap.c (ffffffff813560b6)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff813b1a04)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bb65f)
Location: arch/x86/include/asm/pgtable.h:514
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff813b5ecf)
Location: arch/x86/include/asm/pgtable.h:531
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mremap.c (ffffffff813d06f8)
Location: arch/x86/include/asm/pgtable.h:531
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:531
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff8143245a)
Location: arch/x86/include/asm/pgtable.h:531
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8143dc22)
Location: arch/x86/include/asm/pgtable.h:531
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (ffffffff813ea76a)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mremap.c (ffffffff81404bd9)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff81467bd4)
Location: arch/x86/include/asm/pgtable.h:532
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:532
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
In mm/memory.c (ffffffff81416969)
Location: arch/x86/include/asm/pgtable.h:701
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mremap.c (ffffffff814311bc)
Location: arch/x86/include/asm/pgtable.h:701
Inline: True
```
```
In mm/swapfile.c (0)
Location: arch/x86/include/asm/pgtable.h:701
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/migrate.c (ffffffff814978ac)
Location: arch/x86/include/asm/pgtable.h:701
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:701
Inline: True
```
</details>
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/huge_memory.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
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
In mm/memory.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:507
Inline: True
```
```
In mm/migrate.c (0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:507
Inline: True
```
```
In mm/huge_memory.c (c00000000043c3d8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:507
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:743
Inline: True
```
```
In mm/migrate.c (0)
Location: include/asm-generic/pgtable.h:743
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff812680ed)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff812a5b76)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad157)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff8125a339)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff81297659)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e162)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff81265e8d)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff812a3986)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaf67)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/memory.c:do_swap_page
```
```
In mm/mremap.c (ffffffff8127582f)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/migrate.c (ffffffff812b4196)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb2b7)
Location: arch/x86/include/asm/pgtable.h:502
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
