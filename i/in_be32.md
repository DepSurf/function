# Function: <code>in_be32</code>

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
In arch/powerpc/kernel/rtas_pci.c (c0000000000400a0)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
Inline callers:
  - arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb
  - arch/powerpc/kernel/rtas_pci.c:rtas_setup_phb
```
```
In arch/powerpc/sysdev/mpic.c (c0000000000b47d0)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_suspend
  - arch/powerpc/sysdev/mpic.c:mpic_suspend
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_get_priority
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
```
```
In arch/powerpc/sysdev/fsl_lbc.c (c0000000000b8960)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
Inline callers:
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_probe
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_ctrl_irq
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_upm_find
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_find
  - arch/powerpc/sysdev/fsl_lbc.c:fsl_lbc_find
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c0000000000baeb4)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_flush_interrupt
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_get_irq
```
```
In arch/powerpc/sysdev/xive/native.c (c0000000000bfe34)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/native.c:xive_native_setup_cpu
```
```
In arch/powerpc/sysdev/xive/spapr.c (c0000000000c1038)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
```
```
In lib/iomap.c (c0000000007e57d0)
Location: arch/powerpc/include/asm/io.h:153
Inline: True
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
