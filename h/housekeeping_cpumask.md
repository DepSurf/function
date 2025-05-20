# Function: <code>housekeeping_cpumask</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810dbfb0)
Location: kernel/sched/isolation.c:30
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810dbfb0-ffffffff810dbfde: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810e45f0)
Location: kernel/sched/isolation.c:25
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810e45f0-ffffffff810e461e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eed70)
Location: kernel/sched/isolation.c:25
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/cgroup/cpuset.c:rebuild_sched_domains_locked
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810eed70-ffffffff810eed9e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f5ba0)
Location: kernel/sched/isolation.c:32
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:partition_sched_domains
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810f5ba0-ffffffff810f5bce: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81101910)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff81101910-ffffffff8110193e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110c1a0)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:hk_should_isolate
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff8110c1a0-ffffffff8110c1ce: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff811093c0)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:hk_should_isolate
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff811093c0-ffffffff811093ee: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110b260)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff8110b260-ffffffff8110b28e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81129ac0)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/sched/topology.c:asym_cpu_capacity_scan
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_device_probe
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81129ac0-ffffffff81129aeb: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114b385)
Location: kernel/sched/isolation.c:56
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff81e56928-ffffffff81e56940: housekeeping_cpumask.cold (STB_LOCAL)
ffffffff8113c470-ffffffff8113c4e2: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179da6)
Location: kernel/sched/isolation.c:56
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:store_rps_map
  - net/core/net-sysfs.c:store_rps_map
```
**Symbols:**

```
ffffffff82057b48-ffffffff82057b60: housekeeping_cpumask.cold (STB_LOCAL)
ffffffff81167080-ffffffff811670f1: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118a8c2)
Location: kernel/sched/isolation.c:56
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:kick_ilb
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
**Symbols:**

```
ffffffff820d636e-ffffffff820d6386: housekeeping_cpumask.cold (STB_LOCAL)
ffffffff81177550-ffffffff811775cb: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811991d8)
Location: kernel/sched/isolation.c:56
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:partition_sched_domains_locked
  - kernel/sched/build_utility.c:sched_init_domains
  - kernel/sched/build_utility.c:asym_cpu_capacity_scan
Direct callers:
  - kernel/cpu.c:cpu_down_maps_locked
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:kick_ilb
  - kernel/irq/manage.c:irq_do_set_affinity
  - kernel/irq/cpuhotplug.c:irq_affinity_online_cpu
  - kernel/cgroup/cpuset.c:prstate_housekeeping_conflict
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/pci/pci-driver.c:pci_call_probe
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/base/cpu.c:print_cpus_isolated
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
  - net/core/net-sysfs.c:rps_cpumask_housekeeping
```
**Symbols:**

```
ffffffff821b1536-ffffffff821b154e: housekeeping_cpumask.cold (STB_LOCAL)
ffffffff811852f0-ffffffff8118536b: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffff8000101664c8)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffff8000101664c8-ffff800010166524: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c03b2924)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
c03b2924-c03b2974: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c0000000001bdbf0)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
c0000000001bdbf0-c0000000001bdc48: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe0001087aa)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffe0001087aa-ffffffe0001087fc: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810fac20)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810fac20-ffffffff810fac4e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eae40)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810eae40-ffffffff810eae6e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f7de0)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff810f7de0-ffffffff810f7e0e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct cpumask *housekeeping_cpumask(enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81102f20)
Location: kernel/sched/isolation.c:40
Inline: True
Direct callers:
  - kernel/workqueue.c:workqueue_init_early
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:partition_sched_domains_locked
  - kernel/sched/topology.c:sched_init_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/cgroup/cpuset.c:generate_sched_domains
  - kernel/watchdog.c:lockup_detector_init
  - drivers/base/cpu.c:print_cpus_isolated
```
**Symbols:**

```
ffffffff81102f20-ffffffff81102f4e: housekeeping_cpumask (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
