# Function: <code>is_write_migration_entry</code>

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
In mm/memory.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:117
Inline: True
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
In mm/memory.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/mprotect.c (ffffffff811e4c5a)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff811fc62f)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:117
Inline: True
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
In mm/memory.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/mprotect.c (ffffffff811f4c81)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8120d11b)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (0)
Location: include/linux/swapops.h:117
Inline: True
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
In mm/memory.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/mprotect.c (ffffffff811ffbcf)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff81218f79)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8122df83)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
In mm/memory.c (0)
Location: include/linux/swapops.h:197
Inline: True
```
```
In mm/mprotect.c (ffffffff81218272)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff81233f2a)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81249cc3)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81255c91)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:197
Inline: True
```
```
In mm/mprotect.c (ffffffff8123939a)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81256f18)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8126d4fc)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81279b3a)
Location: include/linux/swapops.h:197
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:193
Inline: True
```
```
In mm/mprotect.c (ffffffff8124db04)
Location: include/linux/swapops.h:193
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8126b58e)
Location: include/linux/swapops.h:193
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81281bec)
Location: include/linux/swapops.h:193
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8128e117)
Location: include/linux/swapops.h:193
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffff8125f93a)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128684d)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8129dcf8)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a8a99)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffff8126e14a)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8129643c)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812ad5a8)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ba019)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:180
Inline: True
```
```
In mm/mprotect.c (ffffffff8129e78e)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812c99df)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812e2931)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812eebf7)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:180
Inline: True
```
```
In mm/mprotect.c (ffffffff812a9b4b)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812d53e0)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812edd63)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fa257)
Location: include/linux/swapops.h:180
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:187
Inline: True
```
```
In mm/mprotect.c (ffffffff812aefd6)
Location: include/linux/swapops.h:187
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812dc3b2)
Location: include/linux/swapops.h:187
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812f3f12)
Location: include/linux/swapops.h:187
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81301022)
Location: include/linux/swapops.h:187
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffff800010305424)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/migrate.c (ffff80001034efcc)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: include/linux/swapops.h:178
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (c0523420)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/migrate.c (c0551734)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (c0000000003d26a4)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (c00000000040fe70)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (c0000000004314e8)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000044443c)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffe000211264)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (0)
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/migrate.c (ffffffe00023e29c)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffff8126679a)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128ea1c)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a5b88)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b25f9)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffff81258e4c)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff812807cf)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81297664)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3984)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffff8126453a)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128c82c)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812a3998)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b0409)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
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
Location: include/linux/swapops.h:178
Inline: True
```
```
In mm/mprotect.c (ffffffff81273ef8)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8129c60a)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff812b41a8)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812c0749)
Location: include/linux/swapops.h:178
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:copy_huge_pmd
```
</details>
</li>
</ul>

## Differences
