# Function: <code>early_radix_enabled</code>

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
In arch/powerpc/kernel/prom.c (c000000001349b78)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/kernel/prom.c:early_init_devtree
```
```
In arch/powerpc/kernel/traps.c (c00000000002f3c4)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:__die
```
```
In arch/powerpc/kernel/setup-common.c (c00000000134a950)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup-common.c:setup_arch
```
```
In arch/powerpc/kernel/setup_64.c (c00000000134b5a4)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:ppc64_bolted_size
```
```
In arch/powerpc/kernel/paca.c (c00000000134bdf4)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/kernel/paca.c:free_unused_pacas
  - arch/powerpc/kernel/paca.c:allocate_paca
```
```
In arch/powerpc/kernel/mce_power.c (c00000000003a990)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce_power.c:mce_handle_error
  - arch/powerpc/kernel/mce_power.c:mce_handle_error
```
```
In arch/powerpc/mm/init_64.c (c00000000135434c)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/mm/init_64.c:mmu_early_init_devtree
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008ce8c)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__early_init_mmu
```
```
In arch/powerpc/mm/book3s64/radix_pgtable.c (c000000000094fa8)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_mmu_secondary
  - arch/powerpc/mm/book3s64/radix_pgtable.c:radix__early_init_mmu
  - arch/powerpc/mm/book3s64/radix_pgtable.c:setup_kuap
  - arch/powerpc/mm/book3s64/radix_pgtable.c:setup_kuep
```
```
In arch/powerpc/platforms/powernv/opal.c (c0000000000c58b0)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_configure_cores
```
```
In arch/powerpc/xmon/xmon.c (c00000000010a824)
Location: arch/powerpc/include/asm/mmu.h:278
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:dump_one_paca
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
