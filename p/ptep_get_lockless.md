# Function: <code>ptep_get_lockless</code>

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
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123cbd2)
Location: include/linux/pgtable.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81291cbd)
Location: include/linux/pgtable.h:310
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
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
In kernel/events/core.c (ffffffff81243ee7)
Location: include/linux/pgtable.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812977dd)
Location: include/linux/pgtable.h:310
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
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
In kernel/events/core.c (ffffffff8127e857)
Location: include/linux/pgtable.h:329
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff812d819d)
Location: include/linux/pgtable.h:329
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
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
In kernel/events/core.c (ffffffff812d34c4)
Location: include/linux/pgtable.h:337
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff81338096)
Location: include/linux/pgtable.h:337
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
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
In kernel/events/core.c (ffffffff8133b742)
Location: include/linux/pgtable.h:392
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff813af833)
Location: include/linux/pgtable.h:392
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
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
In kernel/events/core.c (ffffffff8136d101)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff813e3fb8)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff813f150f)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
```
```
In mm/swap_state.c (ffffffff8142c78a)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff814321ef)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff81441aab)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/khugepaged.c (ffffffff8147c75d)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/ptdump.c (ffffffff814a6bb5)
Location: include/linux/pgtable.h:400
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
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
In kernel/events/core.c (ffffffff81396341)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - kernel/events/core.c:perf_get_pgtable_size
```
```
In mm/gup.c (ffffffff8140e818)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/gup.c:gup_pte_range
```
```
In mm/memory.c (ffffffff81420a1f)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:alloc_anon_folio
```
```
In mm/swap_state.c (ffffffff81465eda)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/swap_state.c:swap_vma_readahead
```
```
In mm/swapfile.c (ffffffff8146b5df)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte_range
```
```
In mm/hugetlb.c (ffffffff8147bd1b)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/hugetlb.c:huge_pte_alloc
```
```
In mm/khugepaged.c (ffffffff814abe31)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
```
In mm/ptdump.c (ffffffff814d7bb5)
Location: include/linux/pgtable.h:509
Inline: True
Inline callers:
  - mm/ptdump.c:ptdump_pte_entry
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
