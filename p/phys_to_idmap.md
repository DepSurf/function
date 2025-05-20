# Function: <code>phys_to_idmap</code>

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
In arch/arm/kernel/reboot.c (c030d264)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/kernel/reboot.c:__soft_restart
```
```
In arch/arm/kernel/setup.c (c1504a94)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
  - arch/arm/kernel/setup.c:setup_arch
```
```
In arch/arm/kernel/hibernate.c (c0311d78)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/kernel/hibernate.c:arch_restore_image
```
```
In arch/arm/kernel/machine_kexec.c (c0315574)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/kernel/machine_kexec.c:machine_kexec
```
```
In arch/arm/kernel/psci_smp.c (c031a0d4)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/kernel/psci_smp.c:psci_boot_secondary
```
```
In arch/arm/mm/idmap.c (c1507f68)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/mm/idmap.c:init_static_idmap
  - arch/arm/mm/idmap.c:init_static_idmap
```
```
In arch/arm/mm/mmu.c (c150983c)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - arch/arm/mm/mmu.c:paging_init
```
```
In kernel/kexec_core.c (c040fb40)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_add_entry
  - kernel/kexec_core.c:sanity_check_segment_list
  - kernel/kexec_core.c:sanity_check_segment_list
```
```
In kernel/kexec.c (c0410eac)
Location: arch/arm/include/asm/memory.h:313
Inline: True
Inline callers:
  - kernel/kexec.c:do_kexec_load
  - kernel/kexec.c:do_kexec_load
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
