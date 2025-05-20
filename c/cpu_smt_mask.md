# Function: <code>cpu_smt_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050df0)
Location: include/linux/topology.h:202
Inline: False
```
```
In kernel/sched/core.c (ffffffff810a4880)
Location: include/linux/topology.h:202
Inline: False
```
**Symbols:**

```
ffffffff81050df0-ffffffff81050e08: cpu_smt_mask (STB_LOCAL)
ffffffff810a4880-ffffffff810a4898: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81050fa0)
Location: include/linux/topology.h:198
Inline: False
```
```
In kernel/sched/core.c (ffffffff810a7fa0)
Location: include/linux/topology.h:198
Inline: False
```
**Symbols:**

```
ffffffff81050fa0-ffffffff81050fb8: cpu_smt_mask (STB_LOCAL)
ffffffff810a7fa0-ffffffff810a7fb8: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053850)
Location: include/linux/topology.h:198
Inline: False
```
```
In kernel/sched/core.c (ffffffff81fe2a5c)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c5ccd)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
**Symbols:**

```
ffffffff81053850-ffffffff8105386c: cpu_smt_mask (STB_LOCAL)
ffffffff810adf80-ffffffff810adf9c: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810531b0)
Location: include/linux/topology.h:198
Inline: False
```
```
In kernel/sched/core.c (ffffffff820c3324)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810bf89d)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810caf00)
Location: include/linux/topology.h:198
Inline: False
```
**Symbols:**

```
ffffffff810531b0-ffffffff810531cc: cpu_smt_mask (STB_LOCAL)
ffffffff810caf00-ffffffff810caf1c: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81056f20)
Location: include/linux/topology.h:198
Inline: False
```
```
In kernel/sched/core.c (ffffffff826cb3d0)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
```
```
In kernel/sched/fair.c (ffffffff810c70a6)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810d2660)
Location: include/linux/topology.h:198
Inline: False
```
**Symbols:**

```
ffffffff81056f20-ffffffff81056f3c: cpu_smt_mask (STB_LOCAL)
ffffffff810d2660-ffffffff810d267c: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81059d90)
Location: include/linux/topology.h:198
Inline: False
```
```
In kernel/sched/core.c (ffffffff810c21c9)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810cefa6)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810da740)
Location: include/linux/topology.h:198
Inline: False
```
**Symbols:**

```
ffffffff81059d90-ffffffff81059dac: cpu_smt_mask (STB_LOCAL)
ffffffff810da740-ffffffff810da75c: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8105fa10)
Location: include/linux/topology.h:198
Inline: False
```
```
In kernel/sched/core.c (ffffffff810cb5e0)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810d8516)
Location: include/linux/topology.h:198
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810e4290)
Location: include/linux/topology.h:198
Inline: False
```
**Symbols:**

```
ffffffff8105fa10-ffffffff8105fa2c: cpu_smt_mask (STB_LOCAL)
ffffffff810e4290-ffffffff810e42ac: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81062e60)
Location: include/linux/topology.h:204
Inline: False
```
```
In kernel/sched/core.c (ffffffff810d35ef)
Location: include/linux/topology.h:204
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810df7b8)
Location: include/linux/topology.h:204
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810eaeb0)
Location: include/linux/topology.h:204
Inline: False
```
**Symbols:**

```
ffffffff81062e60-ffffffff81062e77: cpu_smt_mask (STB_LOCAL)
ffffffff810eaeb0-ffffffff810eaec7: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063510)
Location: include/linux/topology.h:219
Inline: False
```
```
In kernel/sched/core.c (ffffffff810ddb5f)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e9e58)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810f6850)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
ffffffff81063510-ffffffff81063527: cpu_smt_mask (STB_LOCAL)
ffffffff810f6850-ffffffff810f6867: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810696d0)
Location: include/linux/topology.h:202
Inline: False
```
```
In kernel/sched/core.c (ffffffff810e631f)
Location: include/linux/topology.h:202
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e9e31)
Location: include/linux/topology.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff811001f0)
Location: include/linux/topology.h:202
Inline: False
```
**Symbols:**

```
ffffffff810696d0-ffffffff810696e7: cpu_smt_mask (STB_LOCAL)
ffffffff811001f0-ffffffff81100207: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106b2b0)
Location: include/linux/topology.h:202
Inline: False
```
```
In kernel/sched/core.c (ffffffff810e413a)
Location: include/linux/topology.h:202
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e7fd7)
Location: include/linux/topology.h:202
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_smt
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff810fed50)
Location: include/linux/topology.h:202
Inline: False
```
**Symbols:**

```
ffffffff8106b2b0-ffffffff8106b2c7: cpu_smt_mask (STB_LOCAL)
ffffffff810fed50-ffffffff810fed67: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106bd30)
Location: include/linux/topology.h:203
Inline: False
```
```
In kernel/sched/core.c (ffffffff810e6112)
Location: include/linux/topology.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810ec3b6)
Location: include/linux/topology.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff81101130)
Location: include/linux/topology.h:203
Inline: False
```
**Symbols:**

```
ffffffff8106bd30-ffffffff8106bd47: cpu_smt_mask (STB_LOCAL)
ffffffff81101130-ffffffff81101147: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81076810)
Location: include/linux/topology.h:203
Inline: False
```
```
In kernel/sched/core.c (ffffffff810fd35e)
Location: include/linux/topology.h:203
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff81102cba)
Location: include/linux/topology.h:203
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/topology.c (ffffffff8111d2d0)
Location: include/linux/topology.h:203
Inline: False
```
**Symbols:**

```
ffffffff81076810-ffffffff8107684c: cpu_smt_mask (STB_LOCAL)
ffffffff8111d2d0-ffffffff8111d30c: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81085640)
Location: include/linux/topology.h:237
Inline: False
```
```
In kernel/sched/core.c (ffffffff81119d51)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff8111e1f6)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff8114baf5)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/stop_machine.c (ffffffff811dda1e)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
```
**Symbols:**

```
ffffffff81085640-ffffffff81085684: cpu_smt_mask (STB_LOCAL)
ffffffff8113b580-ffffffff8113b5c4: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81098980)
Location: include/linux/topology.h:237
Inline: False
```
```
In kernel/sched/core.c (ffffffff81141697)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff81147504)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff8117a5a5)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/stop_machine.c (ffffffff8122349e)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
```
**Symbols:**

```
ffffffff81098980-ffffffff810989c4: cpu_smt_mask (STB_LOCAL)
ffffffff81165ef0-ffffffff81165f34: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8109bb30)
Location: include/linux/topology.h:237
Inline: False
```
```
In kernel/sched/core.c (ffffffff8114d32b)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff81157396)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff8118b105)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
```
```
In kernel/stop_machine.c (ffffffff812399ee)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
```
**Symbols:**

```
ffffffff8109bb30-ffffffff8109bb74: cpu_smt_mask (STB_LOCAL)
ffffffff81176360-ffffffff811763a4: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810a30b0)
Location: include/linux/topology.h:237
Inline: False
```
```
In kernel/workqueue.c (ffffffff838fb908)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/workqueue.c:cpus_share_smt
```
```
In kernel/sched/core.c (ffffffff81158feb)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_core_cpu_deactivate
  - kernel/sched/core.c:sched_core_cpu_starting
  - kernel/sched/core.c:pick_next_task
  - kernel/sched/core.c:__sched_core_flip
  - kernel/sched/core.c:sched_core_unlock
  - kernel/sched/core.c:sched_core_lock
```
```
In kernel/sched/fair.c (ffffffff81163111)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:find_idlest_group
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:task_hot
  - kernel/sched/fair.c:select_idle_sibling
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:select_idle_core
  - kernel/sched/fair.c:__update_idle_core
  - kernel/sched/fair.c:find_idlest_group_cpu
  - kernel/sched/fair.c:update_numa_stats
```
```
In kernel/sched/build_utility.c (ffffffff81199a35)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__sched_core_account_forceidle
  - kernel/sched/build_utility.c:init_sched_groups_capacity
```
```
In kernel/stop_machine.c (ffffffff812536be)
Location: include/linux/topology.h:237
Inline: True
Inline callers:
  - kernel/stop_machine.c:stop_core_cpuslocked
```
**Symbols:**

```
ffffffff810a30b0-ffffffff810a30f4: cpu_smt_mask (STB_LOCAL)
ffffffff811845c0-ffffffff81184604: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: include/linux/topology.h:219
Inline: True
```
```
In kernel/sched/fair.c (ffff80001014a018)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffff80001015a9d8)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
ffff80001015a9d8-ffff80001015a9f4: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/smp.c (c000000000053db0)
Location: include/linux/topology.h:219
Inline: False
```
```
In kernel/sched/core.c (c00000000018c198)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (c00000000019c05c)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (c0000000001aec40)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
c000000000053db0-c000000000053dd8: cpu_smt_mask (STB_LOCAL)
c0000000001aec40-c0000000001aec68: cpu_smt_mask (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81063000)
Location: include/linux/topology.h:219
Inline: False
```
```
In kernel/sched/core.c (ffffffff810d7d4f)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e3fb8)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810efc50)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
ffffffff81063000-ffffffff81063017: cpu_smt_mask (STB_LOCAL)
ffffffff810efc50-ffffffff810efc67: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81053310)
Location: include/linux/topology.h:219
Inline: False
```
```
In kernel/sched/core.c (ffffffff810c666f)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810d3168)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810dfcc0)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
ffffffff81053310-ffffffff81053327: cpu_smt_mask (STB_LOCAL)
ffffffff810dfcc0-ffffffff810dfcd7: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff810634b0)
Location: include/linux/topology.h:219
Inline: False
```
```
In kernel/sched/core.c (ffffffff810d453f)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810e0388)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810ecd80)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
ffffffff810634b0-ffffffff810634c7: cpu_smt_mask (STB_LOCAL)
ffffffff810ecd80-ffffffff810ecd97: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
const struct cpumask *cpu_smt_mask(int cpu);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff81064a70)
Location: include/linux/topology.h:219
Inline: False
```
```
In kernel/sched/core.c (ffffffff810df94f)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
```
In kernel/sched/fair.c (ffffffff810ebf0d)
Location: include/linux/topology.h:219
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_idle_core
```
```
In kernel/sched/topology.c (ffffffff810f7dc0)
Location: include/linux/topology.h:219
Inline: False
```
**Symbols:**

```
ffffffff81064a70-ffffffff81064a87: cpu_smt_mask (STB_LOCAL)
ffffffff810f7dc0-ffffffff810f7dd7: cpu_smt_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
