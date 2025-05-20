# Function: <code>xics_push_cppr</code>

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
In arch/powerpc/sysdev/xics/xics-common.c (c0000000000ba920)
Location: arch/powerpc/include/asm/xics.h:108
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/xics-common.c:xics_retrigger
```
```
In arch/powerpc/sysdev/xics/icp-native.c (c0000000000bad58)
Location: arch/powerpc/include/asm/xics.h:108
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-native.c:icp_native_get_irq
```
```
In arch/powerpc/sysdev/xics/icp-hv.c (c0000000000bb1a0)
Location: arch/powerpc/include/asm/xics.h:108
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-hv.c:icp_hv_get_irq
```
```
In arch/powerpc/sysdev/xics/icp-opal.c (c0000000000bc688)
Location: arch/powerpc/include/asm/xics.h:108
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xics/icp-opal.c:icp_opal_get_irq
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
