# Function: <code>arch_asym_cpu_priority</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81069940)
Location: arch/x86/kernel/itmt.c:180
Inline: False
Direct callers:
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/core.c:build_sched_domains
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff81069940-ffffffff81069960: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81068bb0)
Location: arch/x86/kernel/itmt.c:178
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81068bb0-ffffffff81068bd0: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8106ce00)
Location: arch/x86/kernel/itmt.c:178
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8106ce00-ffffffff8106ce20: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8106fca0)
Location: arch/x86/kernel/itmt.c:177
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8106fca0-ffffffff8106fcc0: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81075d00)
Location: arch/x86/kernel/itmt.c:177
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81075d00-ffffffff81075d20: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81079900)
Location: arch/x86/kernel/itmt.c:171
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81079900-ffffffff81079920: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8107a950)
Location: arch/x86/kernel/itmt.c:171
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8107a950-ffffffff8107a970: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81081d60)
Location: arch/x86/kernel/itmt.c:170
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:init_sched_groups_capacity
```
**Symbols:**

```
ffffffff81081d60-ffffffff81081d80: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81081830)
Location: arch/x86/kernel/itmt.c:170
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/topology.c:init_sched_groups_capacity
  - kernel/sched/topology.c:init_sched_groups_capacity
```
**Symbols:**

```
ffffffff81081830-ffffffff81081850: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81082650)
Location: arch/x86/kernel/itmt.c:170
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81082650-ffffffff81082670: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81091690)
Location: arch/x86/kernel/itmt.c:170
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81091690-ffffffff810916d1: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810a2810)
Location: arch/x86/kernel/itmt.c:170
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff810a2810-ffffffff810a2859: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810baa40)
Location: arch/x86/kernel/itmt.c:170
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff810baa40-ffffffff810baa89: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810bdc20)
Location: arch/x86/kernel/itmt.c:161
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:build_sched_domains
```
**Symbols:**

```
ffffffff810bdc20-ffffffff810bdc69: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810c4da0)
Location: arch/x86/kernel/itmt.c:160
Inline: False
Direct callers:
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:need_active_balance
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:find_busiest_queue
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sd_pick_busiest
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/build_utility.c:init_sched_groups_capacity
  - kernel/sched/build_utility.c:init_sched_groups_capacity
```
**Symbols:**

```
ffffffff810c4da0-ffffffff810c4de9: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff8000101485f0)
Location: kernel/sched/fair.c:93
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffff8000101485f0-ffff800010148618: arch_asym_cpu_priority (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0396d6c)
Location: kernel/sched/fair.c:93
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
c0396d6c-c0396d88: arch_asym_cpu_priority (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000199f80)
Location: kernel/sched/fair.c:93
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
c000000000199f80-c000000000199f94: arch_asym_cpu_priority (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f2fdc)
Location: kernel/sched/fair.c:93
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffe0000f2fdc-ffffffe0000f3000: arch_asym_cpu_priority (STB_WEAK)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81079950)
Location: arch/x86/kernel/itmt.c:171
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81079950-ffffffff81079970: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff810690c0)
Location: arch/x86/kernel/itmt.c:171
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff810690c0-ffffffff810690e0: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff81079900)
Location: arch/x86/kernel/itmt.c:171
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff81079900-ffffffff81079920: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_asym_cpu_priority(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/itmt.c (ffffffff8107ba00)
Location: arch/x86/kernel/itmt.c:171
Inline: False
Direct callers:
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/topology.c:build_sched_domains
  - kernel/sched/topology.c:build_sched_domains
```
**Symbols:**

```
ffffffff8107ba00-ffffffff8107ba20: arch_asym_cpu_priority (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
