# Function: <code>_mpic_write</code>

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
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/powerpc/sysdev/mpic.c (c0000000000b49a0)
Location: arch/powerpc/sysdev/mpic.c:190
Inline: True
Inline callers:
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_resume
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:mpic_reset_core
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:smp_mpic_message_pass
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:_mpic_get_one_irq
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_teardown_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_cpu_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_setup_this_cpu
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_irq_set_priority
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_host_map
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
  - arch/powerpc/sysdev/mpic.c:mpic_set_vector
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
  - arch/powerpc/sysdev/mpic.c:mpic_set_irq_type
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_set_affinity
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_mask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_tm
  - arch/powerpc/sysdev/mpic.c:mpic_end_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_end_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_ipi
  - arch/powerpc/sysdev/mpic.c:mpic_end_irq
  - arch/powerpc/sysdev/mpic.c:mpic_end_irq
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_mask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
  - arch/powerpc/sysdev/mpic.c:mpic_unmask_irq
Direct callers:
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_init
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
  - arch/powerpc/sysdev/mpic.c:mpic_alloc
```
**Symbols:**

```
c0000000000b4650-c0000000000b466c: _mpic_write.isra.0.part.0 (STB_LOCAL)
c0000000000b4870-c0000000000b48b4: _mpic_write.isra.0 (STB_LOCAL)
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
