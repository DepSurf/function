# Function: <code>pte_mkclean</code>

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
In mm/memory.c (ffffffff811c1295)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (0)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
```
```
In mm/ksm.c (ffffffff811e5596)
Location: arch/x86/include/asm/pgtable.h:198
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/memory.c (ffffffff811dcceb)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffff811e7593)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff811eee44)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81204267)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_with_ksm_page
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
In mm/memory.c (ffffffff811ec7e3)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffff811f8923)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff811ff7ee)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81216414)
Location: arch/x86/include/asm/pgtable.h:212
Inline: True
Inline callers:
  - mm/ksm.c:try_to_merge_one_page
```
```
In fs/dax.c (ffffffff8129bafe)
Location: arch/x86/include/asm/pgtable.h:212
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
In mm/memory.c (ffffffff811f7723)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffff812031bb)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8120a379)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
```
```
In fs/dax.c (ffffffff812aa974)
Location: arch/x86/include/asm/pgtable.h:269
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
In mm/memory.c (ffffffff8120a514)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff8121bd73)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812235ef)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
```
```
In fs/dax.c (ffffffff812ce249)
Location: arch/x86/include/asm/pgtable.h:284
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In mm/rmap.c (ffffffff8123dbb2)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812466db)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
```
```
In fs/dax.c (ffffffff812f8807)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
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
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
```
```
In mm/rmap.c (ffffffff8125219c)
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8125aafe)
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
```
```
In fs/dax.c (ffffffff8130c500)
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In mm/rmap.c (ffffffff81264a04)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81275a96)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In fs/dax.c (ffffffff81333a3f)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In mm/rmap.c (ffffffff81273281)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff81284a66)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In fs/dax.c (ffffffff81347605)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In mm/memory.c (ffffffff8128ec44)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/memory.c:copy_one_pte
```
```
In mm/rmap.c (ffffffff812a3e61)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812b6c52)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812d3839)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8130c6fc)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff8138da0c)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812afb78)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c2e20)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131863c)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff8139f48c)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812b5112)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff812c9c99)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff812e6a27)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8131e82c)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff813a61f6)
Location: arch/x86/include/asm/pgtable.h:334
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:305
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff812f6cae)
Location: arch/x86/include/asm/pgtable.h:305
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8130ecb9)
Location: arch/x86/include/asm/pgtable.h:305
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8132e947)
Location: arch/x86/include/asm/pgtable.h:305
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff8136bc0c)
Location: arch/x86/include/asm/pgtable.h:305
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
```
```
In fs/dax.c (ffffffff813f5c66)
Location: arch/x86/include/asm/pgtable.h:305
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8135b199)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
```
```
In mm/madvise.c (ffffffff81376d98)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff813a071f)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff813e9dd3)
Location: arch/x86/include/asm/pgtable.h:308
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff813d6095)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
```
```
In mm/madvise.c (ffffffff813f441c)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8141ff18)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff81471e50)
Location: arch/x86/include/asm/pgtable.h:325
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff8140b19b)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
```
```
In mm/madvise.c (ffffffff81427921)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff81454b2f)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff814a6793)
Location: arch/x86/include/asm/pgtable.h:331
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
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
In mm/memory.c (ffffffff814184f9)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
Inline callers:
  - mm/memory.c:copy_present_pte
```
```
In mm/rmap.c (ffffffff81437ac9)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
```
```
In mm/madvise.c (ffffffff8146111d)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffff8148fd25)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
Inline callers:
  - mm/ksm.c:write_protect_page
```
```
In mm/mapping_dirty_helpers.c (ffffffff814d7811)
Location: arch/x86/include/asm/pgtable.h:421
Inline: True
Inline callers:
  - mm/mapping_dirty_helpers.c:clean_record_pte
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
Location: arch/arm64/include/asm/pgtable.h:152
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffff800010308b8c)
Location: arch/arm64/include/asm/pgtable.h:152
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffff80001031ec4c)
Location: arch/arm64/include/asm/pgtable.h:152
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/arm64/include/asm/pgtable.h:152
Inline: True
```
```
In mm/huge_memory.c (ffff800010359ff8)
Location: arch/arm64/include/asm/pgtable.h:152
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffff8000104077b4)
Location: arch/arm64/include/asm/pgtable.h:152
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
In mm/memory.c (c0518620)
Location: arch/arm/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (c0525ba8)
Location: arch/arm/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0537868)
Location: arch/arm/include/asm/pgtable.h:291
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (c0544a34)
Location: arch/arm/include/asm/pgtable.h:291
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
In mm/memory.c (c0000000003bdf34)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:635
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (c0000000003d79e8)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:635
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (c0000000003f37bc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:635
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (c000000000419f40)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:635
Inline: True
```
```
In mm/huge_memory.c (c000000000443a24)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:635
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (c0000000005126bc)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:635
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
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
In mm/memory.c (ffffffe000209e6e)
Location: arch/riscv/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
```
In mm/rmap.c (ffffffe000213138)
Location: arch/riscv/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffe00022064e)
Location: arch/riscv/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (ffffffe0002346f4)
Location: arch/riscv/include/asm/pgtable.h:266
Inline: True
```
```
In fs/dax.c (ffffffe0002b2db4)
Location: arch/riscv/include/asm/pgtable.h:266
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In mm/rmap.c (ffffffff8126b8d1)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127d0b6)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In fs/dax.c (ffffffff8133fbe5)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (ffffffff8125d4fc)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8126ef37)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In fs/dax.c (ffffffff81330885)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In mm/rmap.c (ffffffff81269671)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8127ae56)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In fs/dax.c (ffffffff8133d6b5)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
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
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In mm/rmap.c (ffffffff81279194)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/madvise.c (ffffffff8128aa2f)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_pte_range
```
```
In mm/ksm.c (0)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
```
```
In fs/dax.c (ffffffff813505c8)
Location: arch/x86/include/asm/pgtable.h:313
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
</details>
</li>
</ul>

## Differences
