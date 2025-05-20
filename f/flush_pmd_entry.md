# Function: <code>flush_pmd_entry</code>

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
In arch/arm/mm/fault.c (c0e9fc98)
Location: arch/arm/include/asm/tlbflush.h:577
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_translation_fault
```
```
In arch/arm/mm/init.c (c031a864)
Location: arch/arm/include/asm/tlbflush.h:577
Inline: True
```
```
In arch/arm/mm/idmap.c (c1507fec)
Location: arch/arm/include/asm/tlbflush.h:577
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:init_static_idmap
```
```
In arch/arm/mm/mmu.c (c1508a80)
Location: arch/arm/include/asm/tlbflush.h:577
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:__create_mapping
  - arch/arm/mm/mmu.c:arm_pte_alloc
  - arch/arm/mm/mmu.c:early_fixmap_init
```
```
In mm/memory.c (c051b518)
Location: arch/arm/include/asm/tlbflush.h:577
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:__pte_alloc_kernel
  - mm/memory.c:__pte_alloc
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
