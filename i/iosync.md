# Function: <code>iosync</code>

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
In arch/powerpc/sysdev/xics/icp-native.c (c0000000000baba4)
Location: arch/powerpc/include/asm/io.h:643
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_eoi
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_set_cpu_priority
```
```
In arch/powerpc/sysdev/xics/icp-hv.c (c0000000000bb2e8)
Location: arch/powerpc/include/asm/io.h:643
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_set_cpu_priority
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_eoi
```
```
In arch/powerpc/sysdev/xics/icp-opal.c (c0000000000bc4e0)
Location: arch/powerpc/include/asm/io.h:643
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_eoi
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_set_cpu_priority
```
```
In arch/powerpc/kvm/book3s_hv_rm_xics.c (c000000000123efc)
Location: arch/powerpc/include/asm/io.h:643
Inline: True
Inline callers:
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:kvmppc_deliver_irq_passthru
  - arch/powerpc/kvm/book3s_hv_rm_xics.c:kvmppc_deliver_irq_passthru
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
