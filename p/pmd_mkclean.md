# Function: <code>pmd_mkclean</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812183e6)
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/huge_memory.c (ffffffff8122a98a)
Location: arch/x86/include/asm/pgtable.h:296
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8129bbac)
Location: arch/x86/include/asm/pgtable.h:296
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
In mm/rmap.c (ffffffff81203285)
Location: arch/x86/include/asm/pgtable.h:353
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff81236606)
Location: arch/x86/include/asm/pgtable.h:353
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff812aaaf9)
Location: arch/x86/include/asm/pgtable.h:353
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
In mm/rmap.c (ffffffff8121be0a)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812555bb)
Location: arch/x86/include/asm/pgtable.h:368
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff812ce332)
Location: arch/x86/include/asm/pgtable.h:368
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
In mm/rmap.c (ffffffff8123dc55)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812793c2)
Location: arch/x86/include/asm/pgtable.h:378
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff812f86b9)
Location: arch/x86/include/asm/pgtable.h:378
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
In mm/rmap.c (ffffffff8125223b)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff8128da43)
Location: arch/x86/include/asm/pgtable.h:380
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8130c43f)
Location: arch/x86/include/asm/pgtable.h:380
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
In mm/rmap.c (ffffffff81264a9f)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812a82dd)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff81333981)
Location: arch/x86/include/asm/pgtable.h:397
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
In mm/rmap.c (ffffffff81273326)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812b97bd)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff81347546)
Location: arch/x86/include/asm/pgtable.h:397
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
In mm/rmap.c (ffffffff812a3f01)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812ee3ae)
Location: arch/x86/include/asm/pgtable.h:436
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8138d929)
Location: arch/x86/include/asm/pgtable.h:436
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
In mm/rmap.c (ffffffff812afc0b)
Location: arch/x86/include/asm/pgtable.h:435
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812f9a1e)
Location: arch/x86/include/asm/pgtable.h:435
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8139f3a9)
Location: arch/x86/include/asm/pgtable.h:435
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
In mm/rmap.c (ffffffff812b51ac)
Location: arch/x86/include/asm/pgtable.h:435
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812fff9a)
Location: arch/x86/include/asm/pgtable.h:435
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff813a6116)
Location: arch/x86/include/asm/pgtable.h:435
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
In mm/rmap.c (ffffffff812f6d48)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff81349bea)
Location: arch/x86/include/asm/pgtable.h:406
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff813f5b86)
Location: arch/x86/include/asm/pgtable.h:406
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
In mm/rmap.c (ffffffff8135b245)
Location: arch/x86/include/asm/pgtable.h:409
Inline: True
```
```
In mm/huge_memory.c (ffffffff813c04d3)
Location: arch/x86/include/asm/pgtable.h:409
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/rmap.c (ffffffff813d6143)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
```
```
In mm/huge_memory.c (ffffffff814426a5)
Location: arch/x86/include/asm/pgtable.h:426
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/rmap.c (ffffffff8140b247)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
```
```
In mm/huge_memory.c (ffffffff81477e80)
Location: arch/x86/include/asm/pgtable.h:432
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/rmap.c (ffffffff81437b9a)
Location: arch/x86/include/asm/pgtable.h:560
Inline: True
```
```
In mm/huge_memory.c (ffffffff814a75fd)
Location: arch/x86/include/asm/pgtable.h:560
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
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
In mm/rmap.c (ffffffff8126b976)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812b1d9d)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8133fb26)
Location: arch/x86/include/asm/pgtable.h:397
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
In mm/rmap.c (ffffffff8125d583)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812a31f3)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8133073f)
Location: arch/x86/include/asm/pgtable.h:397
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
In mm/rmap.c (ffffffff81269716)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812afbad)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8133d5f6)
Location: arch/x86/include/asm/pgtable.h:397
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
In mm/rmap.c (ffffffff8127922f)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
```
```
In mm/huge_memory.c (ffffffff812bfeec)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - mm/huge_memory.c:madvise_free_huge_pmd
```
```
In fs/dax.c (ffffffff8135050c)
Location: arch/x86/include/asm/pgtable.h:397
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
```
</details>
</li>
</ul>

## Differences
