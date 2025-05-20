# Function: <code>get_cr</code>

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
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/setup.c (c1503fd4)
Location: arch/arm/include/asm/cp15.h:75
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_processor
```
```
In arch/arm/mm/init.c (c031a7d8)
Location: arch/arm/include/asm/cp15.h:75
Inline: True
```
```
In arch/arm/mm/pgd.c (c031f844)
Location: arch/arm/include/asm/cp15.h:75
Inline: True
Inline callers:
  - arch/arm/mm/pgd.c:pgd_alloc
```
```
In arch/arm/mm/mmu.c (c1509648)
Location: arch/arm/include/asm/cp15.h:75
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
  - arch/arm/mm/mmu.c:create_mapping
  - arch/arm/mm/mmu.c:build_mem_type_table
```
```
In arch/arm/mm/alignment.c (c1509960)
Location: arch/arm/include/asm/cp15.h:75
Inline: True
Inline callers:
  - arch/arm/mm/alignment.c:alignment_init
  - arch/arm/mm/alignment.c:alignment_init
```
```
In arch/arm/mm/cache-feroceon-l2.c (c1509aa4)
Location: arch/arm/include/asm/cp15.h:75
Inline: True
Inline callers:
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_init
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_init
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_init
  - arch/arm/mm/cache-feroceon-l2.c:feroceon_l2_init
```
</details>
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
