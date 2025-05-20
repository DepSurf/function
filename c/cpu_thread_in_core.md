# Function: <code>cpu_thread_in_core</code>

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
In arch/powerpc/kernel/dbell.c (c0000000000501c0)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
Inline callers:
  - arch/powerpc/kernel/dbell.c:doorbell_core_ipi
```
```
In arch/powerpc/kernel/smp.c (0)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
```
```
In arch/powerpc/platforms/powernv/idle.c (c00000000135c0e4)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/idle.c:pnv_init_idle_states
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power9_idle_stop
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
  - arch/powerpc/platforms/powernv/idle.c:power7_idle_insn
```
```
In arch/powerpc/platforms/powernv/subcore.c (c0000000000cf044)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/subcore.c:update_subcore_sibling_mask
  - arch/powerpc/platforms/powernv/subcore.c:cpu_do_split
  - arch/powerpc/platforms/powernv/subcore.c:cpu_do_split
```
```
In arch/powerpc/platforms/pseries/smp.c (c000000001363960)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:smp_init_pseries
```
```
In arch/powerpc/kvm/book3s_hv_ras.c (c000000000120cac)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_realmode_hmi_handler
  - arch/powerpc/kvm/book3s_hv_ras.c:kvmppc_subcore_enter_guest
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c0000000001217b0)
Location: arch/powerpc/include/asm/cputhreads.h:83
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
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
