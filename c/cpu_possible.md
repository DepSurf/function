# Function: <code>cpu_possible</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/smp_pv.c (ffffffff831c4427)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffff810a7552)
Location: include/linux/cpumask.h:898
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff81233ab2)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/percpu.c (ffffffff831f0ed8)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In security/selinux/selinuxfs.c (ffffffff814df9c9)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8171215b)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cpu.c (ffffffff817b5f11)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
```
```
In net/core/neighbour.c (ffffffff819f92da)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/route.c (ffffffff81a86a79)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_next
  - net/ipv4/route.c:rt_cpu_seq_start
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
In arch/x86/xen/smp_pv.c (ffffffff832a504d)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffff810b8f44)
Location: include/linux/cpumask.h:898
Inline: True
```
```
In kernel/bpf/cpumap.c (ffffffff8126da72)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/percpu.c (ffffffff832d6863)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In security/selinux/selinuxfs.c (ffffffff815388f5)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
```
In drivers/xen/cpu_hotplug.c (ffffffff8178ebcb)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cpu.c (ffffffff8183f42d)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
```
```
In net/core/neighbour.c (ffffffff81aaaebe)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/route.c (ffffffff81b411b5)
Location: include/linux/cpumask.h:898
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_next
  - net/ipv4/route.c:rt_cpu_seq_start
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
In arch/x86/xen/smp_pv.c (ffffffff834540a6)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffff810cf890)
Location: include/linux/cpumask.h:924
Inline: True
```
```
In kernel/rcu/update.c (ffffffff81172f38)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/bpf/cpumap.c (ffffffff812bc907)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/percpu.c (ffffffff8348b221)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In security/selinux/selinuxfs.c (ffffffff815cfe75)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
```
In drivers/xen/cpu_hotplug.c (ffffffff818c6bec)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cpu.c (ffffffff819824fd)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
```
```
In net/core/neighbour.c (ffffffff81c23a64)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/route.c (ffffffff81ccdc75)
Location: include/linux/cpumask.h:924
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_next
  - net/ipv4/route.c:rt_cpu_seq_start
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
In arch/x86/xen/smp_pv.c (ffffffff83e718e4)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffff810edc40)
Location: include/linux/cpumask.h:1033
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811a9568)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/bpf/cpumap.c (ffffffff8131fca7)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/percpu.c (ffffffff83ebbd0d)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In security/selinux/selinuxfs.c (ffffffff8167db55)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a175ac)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cpu.c (ffffffff81af035d)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
```
```
In net/core/neighbour.c (ffffffff81dd5ab4)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/route.c (ffffffff81e8dd05)
Location: include/linux/cpumask.h:1033
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_next
  - net/ipv4/route.c:rt_cpu_seq_start
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
In arch/x86/xen/smp_pv.c (ffffffff836927c9)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffff810f9d30)
Location: include/linux/cpumask.h:1085
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811bb2e8)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/bpf/cpumap.c (ffffffff8134fcc7)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/percpu.c (ffffffff836e435b)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In security/selinux/selinuxfs.c (ffffffff816b5d55)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81a6063c)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cpu.c (ffffffff81b3e4bd)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
```
```
In net/core/neighbour.c (ffffffff81e468d7)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/route.c (ffffffff81eec445)
Location: include/linux/cpumask.h:1085
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_next
  - net/ipv4/route.c:rt_cpu_seq_start
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
In arch/x86/xen/smp_pv.c (ffffffff838c2317)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:xen_pv_smp_prepare_cpus
```
```
In kernel/cpu.c (ffffffff81103140)
Location: include/linux/cpumask.h:1107
Inline: True
```
```
In kernel/rcu/update.c (ffffffff811cb368)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
```
```
In kernel/bpf/cpumap.c (ffffffff8137714a)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
```
In mm/percpu.c (ffffffff83916beb)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_setup_first_chunk
```
```
In security/selinux/selinuxfs.c (ffffffff816f28e5)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_next
  - security/selinux/selinuxfs.c:sel_avc_stats_seq_start
```
```
In drivers/xen/cpu_hotplug.c (ffffffff81ab2e7c)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - drivers/xen/cpu_hotplug.c:handle_vcpu_hotplug_event
```
```
In drivers/base/cpu.c (ffffffff81b9615b)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_is_hotpluggable
```
```
In net/core/neighbour.c (ffffffff81f05577)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_stat_seq_next
  - net/core/neighbour.c:neigh_stat_seq_start
```
```
In net/ipv4/route.c (ffffffff81fb0495)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - net/ipv4/route.c:rt_cpu_seq_next
  - net/ipv4/route.c:rt_cpu_seq_start
```
```
In lib/objpool.c (ffffffff8219198e)
Location: include/linux/cpumask.h:1107
Inline: True
Inline callers:
  - lib/objpool.c:objpool_init_percpu_slots
```
</details>
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
