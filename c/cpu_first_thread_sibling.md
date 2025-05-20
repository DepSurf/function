# Function: <code>cpu_first_thread_sibling</code>

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
In arch/powerpc/kernel/smp.c (c000000000055f80)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:start_secondary
  - arch/powerpc/kernel/smp.c:smp_prepare_cpus
```
```
In arch/powerpc/mm/book3s64/radix_tlb.c (c000000000097d2c)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_tlb.c:radix_kvm_prefetch_workaround
```
```
In arch/powerpc/mm/numa.c (c0000000000a1be4)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/mm/numa.c:ppc_numa_cpu_prepare
```
```
In arch/powerpc/platforms/powernv/idle.c (c00000000135bc18)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/platforms/pseries/lpar.c (c0000000000e8560)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
  - arch/powerpc/platforms/pseries/lpar.c:update_vcpu_disp_stat
```
```
In arch/powerpc/kvm/book3s_hv_rm_mmu.c (c00000000011c7a8)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000120e24)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_check_need_tlb_flush
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123c20)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:xics_rm_h_eoi
```
```
In drivers/cpufreq/powernv-cpufreq.c (c000000000c1bd94)
Location: arch/powerpc/include/asm/cputhreads.h:93
Inline: True
Inline callers:
  - drivers/cpufreq/powernv-cpufreq.c:powernv_cpufreq_cpu_init
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
