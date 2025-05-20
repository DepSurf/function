# Function: <code>xive_enabled</code>

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
In arch/powerpc/platforms/powernv/setup.c (c0000000000c1afc)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
```
```
In arch/powerpc/platforms/powernv/smp.c (c00000000135ec74)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_probe
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_prepare_cpu
  - arch/powerpc/platforms/powernv/smp.c:pnv_flush_interrupts
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_disable
```
```
In arch/powerpc/platforms/pseries/smp.c (c0000000013637f4)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/smp.c:pSeries_smp_probe
  - arch/powerpc/platforms/pseries/smp.c:pseries_smp_prepare_cpu
  - arch/powerpc/platforms/pseries/smp.c:smp_setup_cpu
```
```
In arch/powerpc/platforms/pseries/kexec.c (c0000000000f8990)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/kexec.c:pseries_kexec_cpu_down
```
```
In arch/powerpc/platforms/pseries/hotplug-cpu.c (c0000000000f9a14)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_cpu_disable
  - arch/powerpc/platforms/pseries/hotplug-cpu.c:pseries_mach_cpu_die
```
```
In arch/powerpc/xmon/xmon.c (c00000000010dd28)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/xmon/xmon.c:dump
```
```
In arch/powerpc/kvm/book3s_hv_builtin.c (c000000000122028)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_eoi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_cppr
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_ipi
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_ipoll
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_xirr_x
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_rm_h_xirr
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmppc_read_intr
  - arch/powerpc/kvm/book3s_hv_builtin.c:kvmhv_rm_send_ipi
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000122828)
Location: arch/powerpc/include/asm/xive.h:88
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:icp_rm_set_vcpu_irq
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
