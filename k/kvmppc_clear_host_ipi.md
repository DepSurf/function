# Function: <code>kvmppc_clear_host_ipi</code>

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
In arch/powerpc/kernel/dbell.c (c00000000005032c)
Location: arch/powerpc/include/asm/kvm_ppc.h:540
Inline: True
Inline callers:
  - arch/powerpc/kernel/dbell.c:doorbell_exception
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c0000000000bac4c)
Location: arch/powerpc/include/asm/kvm_ppc.h:540
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_ipi_action
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_flush_interrupt
```
```
In arch/powerpc/sysdev/xics/icp-opal.c (c0000000000bc82c)
Location: arch/powerpc/include/asm/kvm_ppc.h:540
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_flush_interrupt
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_ipi_action
```
```
In arch/powerpc/platforms/powernv/smp.c (c0000000000cdf64)
Location: arch/powerpc/include/asm/kvm_ppc.h:540
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/smp.c:pnv_smp_cpu_kill_self
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
