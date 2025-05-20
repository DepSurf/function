# Function: <code>__ll_sc_atomic_or</code>

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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/membarrier.c (ffff800010166398)
Location: arch/arm64/include/asm/atomic_ll_sc.h:123
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:__arm64_sys_membarrier
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
```
```
In drivers/pci/hotplug/pciehp_ctrl.c (ffff80001070ab3c)
Location: arch/arm64/include/asm/atomic_ll_sc.h:123
Inline: True
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bf68)
Location: arch/arm64/include/asm/atomic_ll_sc.h:123
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
