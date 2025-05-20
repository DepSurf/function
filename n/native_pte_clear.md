# Function: <code>native_pte_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bd9dd)
Location: arch/x86/include/asm/pgtable_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
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
In mm/memory.c (ffffffff811d915f)
Location: arch/x86/include/asm/pgtable_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811eef82)
Location: arch/x86/include/asm/pgtable_64.h:47
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff811e85f0)
Location: arch/x86/include/asm/pgtable_64.h:47
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/madvise.c (ffffffff811ff8e3)
Location: arch/x86/include/asm/pgtable_64.h:47
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff811f3716)
Location: arch/x86/include/asm/pgtable_64.h:56
Inline: True
```
```
In mm/madvise.c (ffffffff8120a5ef)
Location: arch/x86/include/asm/pgtable_64.h:56
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8120b07b)
Location: arch/x86/include/asm/pgtable_64.h:58
Inline: True
```
```
In mm/madvise.c (ffffffff812235e8)
Location: arch/x86/include/asm/pgtable_64.h:58
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8122be78)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
```
```
In mm/madvise.c (ffffffff812467d6)
Location: arch/x86/include/asm/pgtable_64.h:59
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8123f28f)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
```
```
In mm/madvise.c (ffffffff8125abfd)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff81250bcf)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
```
```
In mm/madvise.c (ffffffff81275a8f)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
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
In mm/memory.c (ffffffff8125f1a9)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
```
```
In mm/madvise.c (ffffffff81284a5f)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff8128f583)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812b6c4b)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff8129a08e)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c2e19)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff8129f2b2)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff812c9c92)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff812e0518)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8130ecb2)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff81340b97)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81376f7f)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff813b8b3c)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff813f4415)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff813ed776)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81427bf1)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff81418d48)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff81461407)
Location: arch/x86/include/asm/pgtable_64.h:70
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812577f9)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
```
```
In mm/madvise.c (ffffffff8127d0af)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In arch/x86/kernel/ldt.c (ffffffff8102695f)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/ldt.c:write_ldt
```
```
In arch/x86/kernel/alternative.c (ffffffff81029ac9)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:__text_poke
  - arch/x86/kernel/alternative.c:__text_poke
```
```
In arch/x86/mm/init_64.c (ffffffff81a27240)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/ioremap.c (ffffffff828a61cb)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/mm/ioremap.c:__early_set_fixmap
```
```
In arch/x86/mm/kmmio.c (ffffffff81078c83)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In mm/memory.c (ffffffff8124a180)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/madvise.c (ffffffff8126ee08)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
```
In mm/hugetlb.c (ffffffff8127f51e)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
```
In mm/khugepaged.c (ffffffff812a68f3)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
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
In mm/memory.c (ffffffff81255599)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
```
```
In mm/madvise.c (ffffffff8127ae4f)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
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
In mm/memory.c (ffffffff81265048)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
```
```
In mm/madvise.c (ffffffff8128aa28)
Location: arch/x86/include/asm/pgtable_64.h:64
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
```
</details>
</li>
</ul>

## Differences
