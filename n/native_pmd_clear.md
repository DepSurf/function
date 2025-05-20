# Function: <code>native_pmd_clear</code>

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
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81a27072)
Location: arch/x86/include/asm/pgtable_64.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init_64.c:remove_pmd_table
  - arch/x86/mm/init_64.c:remove_pmd_table
```
```
In arch/x86/mm/pageattr.c (ffffffff81070583)
Location: arch/x86/include/asm/pgtable_64.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:unmap_pmd_range
  - arch/x86/mm/pageattr.c:unmap_pte_range
```
```
In arch/x86/mm/pgtable.c (ffffffff81075c73)
Location: arch/x86/include/asm/pgtable_64.h:80
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:pmd_free_pte_page
  - arch/x86/mm/pgtable.c:pud_free_pmd_page
  - arch/x86/mm/pgtable.c:pmd_clear_huge
```
```
In mm/memory.c (ffffffff81248c1c)
Location: arch/x86/include/asm/pgtable_64.h:80
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
```
In mm/mremap.c (ffffffff8125a811)
Location: arch/x86/include/asm/pgtable_64.h:80
Inline: True
Inline callers:
  - mm/mremap.c:move_page_tables
```
```
In mm/pgtable-generic.c (ffffffff8125d233)
Location: arch/x86/include/asm/pgtable_64.h:80
Inline: True
Inline callers:
  - mm/pgtable-generic.c:pmd_clear_bad
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
