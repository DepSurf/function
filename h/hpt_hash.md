# Function: <code>hpt_hash</code>

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
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008e448)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:433
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:flush_hash_hugepage
  - arch/powerpc/mm/book3s64/hash_utils.c:pte_get_hash_gslot
  - arch/powerpc/mm/book3s64/hash_utils.c:htab_bolt_mapping
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000092560)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:433
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:native_flush_hash_range
  - arch/powerpc/mm/book3s64/hash_native.c:native_hugepage_invalidate
  - arch/powerpc/mm/book3s64/hash_native.c:native_hpte_find
```
```
In arch/powerpc/mm/book3s64/hash_64k.c (c00000000009dfb0)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:433
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_64K
  - arch/powerpc/mm/book3s64/hash_64k.c:__hash_page_4K
```
```
In arch/powerpc/mm/book3s64/hash_hugetlbpage.c (c00000000009e54c)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:433
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugetlbpage.c:__hash_page_huge
```
```
In arch/powerpc/mm/book3s64/hash_hugepage.c (c00000000009f340)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:433
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_hugepage.c:__hash_page_thp
  - arch/powerpc/mm/book3s64/hash_hugepage.c:__hash_page_thp
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000e9da0)
Location: arch/powerpc/include/asm/book3s/64/mmu-hash.h:433
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_flush_hash_range
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_flush_hash_range
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_hugepage_invalidate
  - arch/powerpc/platforms/pseries/lpar.c:pSeries_lpar_hpte_find
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
