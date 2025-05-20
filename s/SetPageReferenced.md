# Function: <code>SetPageReferenced</code>

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
In arch/x86/mm/gup.c (ffffffff8107151b)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_pte_range
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
```
```
In mm/swap.c (ffffffff8119de81)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811a33bd)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/migrate.c (ffffffff811f1c31)
Location: include/linux/page-flags.h:211
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
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
In arch/x86/mm/gup.c (ffffffff81071b43)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/swap.c (ffffffff811b363a)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811b9d12)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/migrate.c (ffffffff81210604)
Location: include/linux/page-flags.h:257
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff812160c6)
Location: include/linux/page-flags.h:257
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
In arch/x86/mm/gup.c (ffffffff810756bd)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - arch/x86/mm/gup.c:gup_huge_pud
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
```
In mm/swap.c (ffffffff811c3cba)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811ca39d)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/migrate.c (ffffffff81222741)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff81228688)
Location: include/linux/page-flags.h:267
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
In mm/swap.c (ffffffff811cc06a)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811d2b58)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff811f0be8)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff8122e1df)
Location: include/linux/page-flags.h:267
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_copy
```
```
In mm/huge_memory.c (ffffffff8123201c)
Location: include/linux/page-flags.h:267
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
In mm/swap.c (ffffffff811e105a)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff811e808c)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff81205767)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff812492b3)
Location: include/linux/page-flags.h:268
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff81252e0f)
Location: include/linux/page-flags.h:268
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
In mm/swap.c (ffffffff812028e6)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81209744)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff81226b9f)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff8126cd33)
Location: include/linux/page-flags.h:275
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812772d6)
Location: include/linux/page-flags.h:275
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
In mm/swap.c (ffffffff81215266)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8121c424)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff81239ca0)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff81281535)
Location: include/linux/page-flags.h:284
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8128863b)
Location: include/linux/page-flags.h:284
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
In mm/swap.c (ffffffff81224c92)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8122c021)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff8124af28)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff8129d7c7)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812a3279)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff81232a22)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81239ee3)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff81259418)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff812ad0e5)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812b4779)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8125fed9)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81263d90)
Location: include/linux/page-flags.h:323
Inline: True
```
```
In mm/gup.c (ffffffff8128ab99)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff812e2c25)
Location: include/linux/page-flags.h:323
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812e9d27)
Location: include/linux/page-flags.h:323
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
In mm/swap.c (ffffffff81269639)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8126e707)
Location: include/linux/page-flags.h:331
Inline: True
```
```
In mm/gup.c (ffffffff81294859)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff812ee055)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812f4f07)
Location: include/linux/page-flags.h:331
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
In mm/swap.c (ffffffff8126ea9b)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812759a2)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff8129a2a3)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff812f3b45)
Location: include/linux/page-flags.h:331
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812fb46d)
Location: include/linux/page-flags.h:331
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
In mm/swap.c (ffffffff812abaeb)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812b3622)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff812dac46)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
```
In mm/migrate.c (ffffffff8133e4e5)
Location: include/linux/page-flags.h:345
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8134529c)
Location: include/linux/page-flags.h:345
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
In mm/gup.c (ffffffff8133a447)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
```
```
In mm/huge_memory.c (ffffffff813bb960)
Location: include/linux/page-flags.h:495
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
In mm/gup.c (ffffffff813b1efa)
Location: include/linux/page-flags.h:474
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
```
```
In mm/huge_memory.c (ffffffff8143de9e)
Location: include/linux/page-flags.h:474
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
In mm/gup.c (ffffffff813e6c9a)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
```
```
In mm/huge_memory.c (ffffffff81473779)
Location: include/linux/page-flags.h:468
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8141192a)
Location: include/linux/page-flags.h:470
Inline: True
Inline callers:
  - mm/gup.c:__gup_device_huge
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
In mm/swap.c (ffff8000102c28b4)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffff8000102cad60)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffff8000102f11d0)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/migrate.c (ffff80001034f3a8)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffff800010355d24)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
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
In mm/swap.c (c04edb00)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (c04f4b70)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/migrate.c (c0551328)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (c00000000037c95c)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (c000000000387b18)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (c0000000003b7870)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
```
In mm/migrate.c (c0000000004317ac)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (c00000000043c02c)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffe0001e3c52)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffe0001e9d16)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/migrate.c (ffffffe00023e3fe)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
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
In mm/swap.c (ffffffff8122b072)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff81232533)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff81251a68)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff812a56c5)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812acd59)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff8121e182)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812255df)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff812448fb)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff81297195)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff8129de22)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff81228e12)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff812302d3)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff8124f808)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff812a34d5)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812aab69)
Location: include/linux/page-flags.h:315
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
In mm/swap.c (ffffffff812381b2)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/swap.c:mark_page_accessed
```
```
In mm/vmscan.c (ffffffff8123f71c)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_page_list
```
```
In mm/gup.c (ffffffff8125f178)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
```
In mm/migrate.c (ffffffff812b3ce5)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/migrate.c:migrate_page_states
```
```
In mm/huge_memory.c (ffffffff812baeb9)
Location: include/linux/page-flags.h:315
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
</details>
</li>
</ul>

## Differences
