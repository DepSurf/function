# Function: <code>xive_do_source_set_mask</code>

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
In arch/powerpc/sysdev/xive/common.c (c0000000000bef50)
Location: arch/powerpc/sysdev/xive/common.c:434
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_teardown_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_vcpu_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_irq_mask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_shutdown
Direct callers:
  - arch/powerpc/sysdev/xive/common.c:xive_teardown_cpu
  - arch/powerpc/sysdev/xive/common.c:xive_setup_cpu_ipi
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_vcpu_affinity
  - arch/powerpc/sysdev/xive/common.c:xive_irq_mask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_unmask
  - arch/powerpc/sysdev/xive/common.c:xive_irq_shutdown
  - arch/powerpc/sysdev/xive/common.c:xive_irq_startup
```
**Symbols:**

```
c0000000000bd520-c0000000000bd584: xive_do_source_set_mask.part.0 (STB_LOCAL)
c0000000000bd700-c0000000000bd784: xive_do_source_set_mask.constprop.0 (STB_LOCAL)
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
