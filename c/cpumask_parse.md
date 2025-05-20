# Function: <code>cpumask_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c61c)
Location: include/linux/cpumask.h:584
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_cpumask_store
  - kernel/workqueue.c:wq_unbound_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a0a06)
Location: include/linux/cpumask.h:588
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81044407)
Location: include/linux/cpumask.h:588
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810a5b00)
Location: include/linux/cpumask.h:588
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810433ab)
Location: include/linux/cpumask.h:616
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810a2b69)
Location: include/linux/cpumask.h:616
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810469ff)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810a9499)
Location: include/linux/cpumask.h:620
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048fc2)
Location: include/linux/cpumask.h:622
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810afbd5)
Location: include/linux/cpumask.h:622
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058fa4)
Location: include/linux/cpumask.h:634
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810b8d45)
Location: include/linux/cpumask.h:634
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c55b)
Location: include/linux/cpumask.h:634
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810be857)
Location: include/linux/cpumask.h:634
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce55)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810c4e07)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062c14)
Location: include/linux/cpumask.h:671
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810cc829)
Location: include/linux/cpumask.h:671
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff82cf70c2)
Location: include/linux/cpumask.h:671
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff819fd4f8)
Location: include/linux/cpumask.h:671
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810610a4)
Location: include/linux/cpumask.h:677
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810c79a9)
Location: include/linux/cpumask.h:677
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff82fe3c1f)
Location: include/linux/cpumask.h:677
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff819fd182)
Location: include/linux/cpumask.h:677
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810615d4)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810c9439)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff831ee359)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff819e39f3)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106b2b4)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810dc139)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff832d3020)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff81a93fa3)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810785bc)
Location: include/linux/cpumask.h:674
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810f587f)
Location: include/linux/cpumask.h:674
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff834874c9)
Location: include/linux/cpumask.h:674
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff81c0a384)
Location: include/linux/cpumask.h:674
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108925b)
Location: include/linux/cpumask.h:750
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff81117da4)
Location: include/linux/cpumask.h:750
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff83eb6f86)
Location: include/linux/cpumask.h:750
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff81dba481)
Location: include/linux/cpumask.h:750
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c16b)
Location: include/linux/cpumask.h:802
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff81124fc4)
Location: include/linux/cpumask.h:802
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff836dc522)
Location: include/linux/cpumask.h:802
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff81e2abe5)
Location: include/linux/cpumask.h:802
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093edb)
Location: include/linux/cpumask.h:818
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff8112db8e)
Location: include/linux/cpumask.h:818
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
```
In kernel/trace/trace_boot.c (ffffffff8390eb52)
Location: include/linux/cpumask.h:818
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
```
In net/core/sysctl_net_core.c (ffffffff81ee89f5)
Location: include/linux/cpumask.h:818
Inline: True
Inline callers:
  - net/core/sysctl_net_core.c:flow_limit_cpu_sysctl
  - net/core/sysctl_net_core.c:rps_default_mask_sysctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff8000101232e0)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0376be8)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016d1dc)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dbac2)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c9d5)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810bf177)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104cba5)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810ad997)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ce05)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810be6d7)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e325)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff810c6a47)
Location: include/linux/cpumask.h:664
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_unbound_cpumask_store
  - kernel/workqueue.c:wq_cpumask_store
```
</details>
</li>
</ul>

## Differences
