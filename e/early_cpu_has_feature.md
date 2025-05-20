# Function: <code>early_cpu_has_feature</code>

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
In arch/powerpc/kernel/setup_64.c (c00000000134b1c0)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/kernel/setup_64.c:record_spr_defaults
```
```
In arch/powerpc/kernel/paca.c (c00000000134bb98)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/kernel/paca.c:allocate_paca
  - arch/powerpc/kernel/paca.c:setup_paca
```
```
In arch/powerpc/kernel/mce_power.c (c00000000003a680)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/kernel/mce_power.c:flush_erat
```
```
In arch/powerpc/mm/book3s64/hash_utils.c (c00000000008e89c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__setup_initial_memory_limit
  - arch/powerpc/mm/book3s64/hash_utils.c:hash__setup_initial_memory_limit
```
```
In arch/powerpc/mm/book3s64/hash_native.c (c000000000094578)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/hash_native.c:hash__tlbiel_all
  - arch/powerpc/mm/book3s64/hash_native.c:hash__tlbiel_all
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c00000000009ab24)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlbiel_all
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix__tlbiel_all
```
```
In arch/powerpc/platforms/powernv/setup.c (c00000000135ac8c)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/setup.c:pnv_tm_init
```
```
In arch/powerpc/platforms/powernv/opal.c (c0000000000c5850)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:opal_configure_cores
```
```
In arch/powerpc/xmon/xmon.c (c00000000010a924)
Location: arch/powerpc/include/asm/cpu_has_feature.h:10
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:dump_one_paca
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
