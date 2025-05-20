# Function: <code>pte_clear_savedwrite</code>

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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003be198)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:539
Inline: True
Inline callers:
  - mm/memory.c:copy_pte_range
```
```
In mm/rmap.c (c0000000003d7ae0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:539
Inline: True
Inline callers:
  - mm/rmap.c:page_mkclean_one
  - mm/rmap.c:page_mkclean_one
```
```
In mm/hugetlb.c (c000000000406b14)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:539
Inline: True
```
```
In mm/ksm.c (c00000000041a180)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:539
Inline: True
```
```
In mm/huge_memory.c (c00000000043c840)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:539
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:copy_huge_pmd
```
```
In fs/dax.c (c000000000512880)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:539
Inline: True
Inline callers:
  - fs/dax.c:dax_entry_mkclean
  - fs/dax.c:dax_entry_mkclean
```
</details>
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
