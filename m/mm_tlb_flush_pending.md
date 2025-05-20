# Function: <code>mm_tlb_flush_pending</code>

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
In mm/pgtable-generic.c (ffffffff811d0479)
Location: include/linux/mm_types.h:539
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/migrate.c (ffffffff811f32b4)
Location: include/linux/mm_types.h:539
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/pgtable-generic.c (ffffffff811ed629)
Location: include/linux/mm_types.h:546
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/migrate.c (ffffffff8121306f)
Location: include/linux/mm_types.h:546
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/pgtable-generic.c (ffffffff811f7a19)
Location: include/linux/mm_types.h:541
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/migrate.c (ffffffff812253df)
Location: include/linux/mm_types.h:541
Inline: True
Inline callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
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
In mm/pgtable-generic.c (ffffffff81202ba9)
Location: include/linux/mm_types.h:538
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff81221ad0)
Location: include/linux/mm_types.h:538
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81233b07)
Location: include/linux/mm_types.h:538
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff8121b911)
Location: include/linux/mm_types.h:594
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff8123cd6d)
Location: include/linux/mm_types.h:594
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff8125144e)
Location: include/linux/mm_types.h:594
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff8123d6f1)
Location: include/linux/mm_types.h:580
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff81260824)
Location: include/linux/mm_types.h:580
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff81275919)
Location: include/linux/mm_types.h:580
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff81251c41)
Location: include/linux/mm_types.h:592
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff81274f76)
Location: include/linux/mm_types.h:592
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In mm/huge_memory.c (ffffffff8128a873)
Location: include/linux/mm_types.h:592
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff81263f11)
Location: include/linux/mm_types.h:612
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff8128f02f)
Location: include/linux/mm_types.h:612
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a5496)
Location: include/linux/mm_types.h:612
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff81272781)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff8129edb8)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b6956)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff812a3541)
Location: include/linux/mm_types.h:634
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff812d391e)
Location: include/linux/mm_types.h:634
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/huge_memory.c (ffffffff812eba89)
Location: include/linux/mm_types.h:634
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff8129b9bb)
Location: include/linux/mm_types.h:658
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff812aee21)
Location: include/linux/mm_types.h:658
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff812df344)
Location: include/linux/mm_types.h:658
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/huge_memory.c (ffffffff812f6b39)
Location: include/linux/mm_types.h:658
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff812a0a9f)
Location: include/linux/mm_types.h:668
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff812b4351)
Location: include/linux/mm_types.h:668
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff812e6b18)
Location: include/linux/mm_types.h:668
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/huge_memory.c (ffffffff812fceed)
Location: include/linux/mm_types.h:668
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/memory.c (ffffffff812e1bbf)
Location: include/linux/mm_types.h:675
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/pgtable-generic.c (ffffffff812f5f31)
Location: include/linux/mm_types.h:675
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff8132ea38)
Location: include/linux/mm_types.h:675
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
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
In mm/memory.c (ffffffff81342a08)
Location: include/linux/mm_inline.h:296
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/ksm.c (ffffffff813a08be)
Location: include/linux/mm_inline.h:296
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
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
In mm/memory.c (ffffffff813baa84)
Location: include/linux/mm_inline.h:513
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/ksm.c (ffffffff81420108)
Location: include/linux/mm_inline.h:513
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
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
In mm/memory.c (ffffffff813ef594)
Location: include/linux/mm_inline.h:501
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/ksm.c (ffffffff81454d1e)
Location: include/linux/mm_inline.h:501
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
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
In mm/memory.c (ffffffff814199cb)
Location: include/linux/mm_inline.h:488
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
```
```
In mm/ksm.c (ffffffff8148ff27)
Location: include/linux/mm_inline.h:488
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
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
In mm/pgtable-generic.c (ffff800010307fec)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffff80001033e5d0)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (ffff800010357690)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (c05255d0)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (c0544b18)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
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
In mm/ksm.c (c00000000041a024)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (c00000000043f6c8)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/ksm.c (ffffffe000234758)
Location: include/linux/mm_types.h:620
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
In mm/pgtable-generic.c (ffffffff8126add1)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff81297398)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (ffffffff812aef36)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff8125ce01)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff81288f93)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a040c)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff81268b71)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff812951a8)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (ffffffff812acd46)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
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
In mm/pgtable-generic.c (ffffffff81278501)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/pgtable-generic.c:ptep_clear_flush
```
```
In mm/ksm.c (ffffffff812a4ffd)
Location: include/linux/mm_types.h:620
Inline: True
```
```
In mm/huge_memory.c (ffffffff812bd0b7)
Location: include/linux/mm_types.h:620
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_numa_page
```
</details>
</li>
</ul>

## Differences
