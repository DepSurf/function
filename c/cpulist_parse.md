# Function: <code>cpulist_parse</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81f7ce8c)
Location: include/linux/cpumask.h:599
Inline: True
Inline callers:
  - kernel/sched/core.c:isolated_cpu_setup
```
```
In kernel/cpuset.c (ffffffff8111c7f7)
Location: include/linux/cpumask.h:599
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8113e423)
Location: include/linux/cpumask.h:599
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81fa67d2)
Location: include/linux/cpumask.h:603
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff81fa7f3c)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cpuset.c (ffffffff811246f7)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff81146a73)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In kernel/sched/core.c (ffffffff81fe2320)
Location: include/linux/cpumask.h:603
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff81fe3ca6)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cpuset.c (ffffffff8112db70)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff811506d3)
Location: include/linux/cpumask.h:603
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff8104342b)
Location: include/linux/cpumask.h:631
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/topology.c (ffffffff820c3aa4)
Location: include/linux/cpumask.h:631
Inline: True
```
```
In kernel/irq/irqdesc.c (ffffffff820c479f)
Location: include/linux/cpumask.h:631
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8112f1f4)
Location: include/linux/cpumask.h:631
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff81152cc8)
Location: include/linux/cpumask.h:631
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81046a92)
Location: include/linux/cpumask.h:635
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff826cbbe2)
Location: include/linux/cpumask.h:635
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff826cca38)
Location: include/linux/cpumask.h:635
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8113c0a0)
Location: include/linux/cpumask.h:635
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8115f4e8)
Location: include/linux/cpumask.h:635
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049091)
Location: include/linux/cpumask.h:637
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff826f5d4b)
Location: include/linux/cpumask.h:637
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff826f6c20)
Location: include/linux/cpumask.h:637
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8114a92d)
Location: include/linux/cpumask.h:637
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8116e453)
Location: include/linux/cpumask.h:637
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059073)
Location: include/linux/cpumask.h:649
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828acb95)
Location: include/linux/cpumask.h:649
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828adb4c)
Location: include/linux/cpumask.h:649
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff81157642)
Location: include/linux/cpumask.h:649
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8117bf23)
Location: include/linux/cpumask.h:649
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c621)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828c54cb)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828c659b)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff811641db)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff81188d44)
Location: include/linux/cpumask.h:648
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cf1b)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828cdb34)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828cebc8)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8117001c)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff81194c84)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81062c87)
Location: include/linux/cpumask.h:683
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff82ceeef8)
Location: include/linux/cpumask.h:683
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff82cf007a)
Location: include/linux/cpumask.h:683
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff811819ed)
Location: include/linux/cpumask.h:683
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff811a9dd4)
Location: include/linux/cpumask.h:683
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061117)
Location: include/linux/cpumask.h:689
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff82fdb60f)
Location: include/linux/cpumask.h:689
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff82fdca65)
Location: include/linux/cpumask.h:689
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e8fd)
Location: include/linux/cpumask.h:689
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff811a73d4)
Location: include/linux/cpumask.h:689
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061647)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff831e6369)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff831e7776)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8117e90d)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff811a7f14)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8106b327)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff832ca47c)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff832cb868)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff811a662d)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff811d1a44)
Location: include/linux/cpumask.h:660
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8107862e)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/build_utility.c (ffffffff8347d672)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff8347ef42)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff811d7ac5)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff812061b3)
Location: include/linux/cpumask.h:686
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810892cd)
Location: include/linux/cpumask.h:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/build_utility.c (ffffffff83ea8f66)
Location: include/linux/cpumask.h:762
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff83eab119)
Location: include/linux/cpumask.h:762
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8121c7e9)
Location: include/linux/cpumask.h:762
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff8124e493)
Location: include/linux/cpumask.h:762
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108c1dd)
Location: include/linux/cpumask.h:814
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/build_utility.c (ffffffff836cda26)
Location: include/linux/cpumask.h:814
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff836d00d9)
Location: include/linux/cpumask.h:814
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff81232bd9)
Location: include/linux/cpumask.h:814
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff81265843)
Location: include/linux/cpumask.h:814
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In kernel/trace/trace_osnoise.c (ffffffff81297651)
Location: include/linux/cpumask.h:814
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81093f4d)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/workqueue.c (ffffffff838fba15)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_unbound_cpus_setup
```
```
In kernel/sched/build_utility.c (ffffffff838fee64)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff839014f9)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/rcu/tree.c (ffffffff8390207d)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ca88)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_exclusive_cpumask
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (ffffffff8127f6c5)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b2ca1)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/trace/trace_osnoise.c:osnoise_cpus_write
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c8260)
Location: include/linux/cpumask.h:830
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:parse_pred
```
</details>
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
In kernel/sched/isolation.c (ffff800011445414)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffff800011446478)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffff8000101e3aa0)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffff80001020ce98)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c151f54c)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (c1520b20)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (c04246dc)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (c044b884)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c000000001369e88)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (c00000000136b21c)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (c000000000252d48)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:update_cpumask
```
```
In kernel/taskstats.c (c00000000028ab3c)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe0000071f0)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffe000007ff8)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffe00015a07e)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffe00016e084)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105ca9b)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828b68c4)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828b78c0)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8116863c)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8118d2a4)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104cc6b)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828aeaba)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828afb40)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/rcu/tree.c (ffffffff828b05d3)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8115b84a)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff811803c4)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105cecb)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828c9768)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828ca7fc)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff8116640c)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff8118b074)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105e3eb)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_cpus_write
```
```
In kernel/sched/isolation.c (ffffffff828ceb1a)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/sched/isolation.c:housekeeping_setup
```
```
In kernel/irq/irqdesc.c (ffffffff828cfbf5)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_affinity_setup
```
```
In kernel/cgroup/cpuset.c (ffffffff81173a2e)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:cpuset_write_resmask
```
```
In kernel/taskstats.c (ffffffff811989e4)
Location: include/linux/cpumask.h:678
Inline: True
Inline callers:
  - kernel/taskstats.c:parse
```
</details>
</li>
</ul>

## Differences
