# Function: <code>idle_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa665)
Location: kernel/sched/core.c:3567
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_tick
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:trigger_load_balance
```
**Symbols:**

```
ffffffff810ad8e0-ffffffff810ad92b: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810afd48)
Location: kernel/sched/core.c:3820
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
```
**Symbols:**

```
ffffffff810b0290-ffffffff810b02db: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5e88)
Location: kernel/sched/core.c:3857
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
```
**Symbols:**

```
ffffffff810b6420-ffffffff810b646b: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2131)
Location: kernel/sched/core.c:3863
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
```
**Symbols:**

```
ffffffff810b26a0-ffffffff810b26eb: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b94f7)
Location: kernel/sched/core.c:3907
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:trigger_load_balance
  - kernel/sched/fair.c:run_rebalance_domains
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:select_task_rq_fair
  - kernel/sched/fair.c:__update_idle_core
```
**Symbols:**

```
ffffffff810b9aa0-ffffffff810b9aeb: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c14c5)
Location: kernel/sched/core.c:4017
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:find_busiest_group
```
**Symbols:**

```
ffffffff810c1470-ffffffff810c14bb: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca7f5)
Location: kernel/sched/core.c:4002
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810ca7a0-ffffffff810ca7eb: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d24a5)
Location: kernel/sched/core.c:4421
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810d2450-ffffffff810d24a0: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc915)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810dc8c0-ffffffff810dc910: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5495)
Location: kernel/sched/core.c:4856
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
**Symbols:**

```
ffffffff810e5440-ffffffff810e548b: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2f45)
Location: kernel/sched/core.c:5629
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
**Symbols:**

```
ffffffff810e2ef0-ffffffff810e2f3b: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e4e15)
Location: kernel/sched/core.c:5844
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
**Symbols:**

```
ffffffff810e4dc0-ffffffff810e4e0b: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810fbd15)
Location: kernel/sched/core.c:7007
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/softirq.c:irq_exit_rcu
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
```
**Symbols:**

```
ffffffff810fbca0-ffffffff810fbd05: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811181b5)
Location: kernel/sched/core.c:7099
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/rcu/tree.c:print_cpu_stall
```
**Symbols:**

```
ffffffff81118130-ffffffff811181ad: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113f825)
Location: kernel/sched/core.c:7240
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/sched/fair.c:nohz_balancer_kick
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/rcu/tree.c:print_cpu_stall_info
```
**Symbols:**

```
ffffffff8113f790-ffffffff8113f80d: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114bd75)
Location: kernel/sched/core.c:7341
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - kernel/softirq.c:__irq_exit_rcu
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/rcu/tree.c:print_cpu_stall_info
```
**Symbols:**

```
ffffffff8114bce0-ffffffff8114bd5d: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81157c66)
Location: kernel/sched/core.c:7391
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_core_idle_cpu
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:nohz_csd_func
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_send_call_func_ipi
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:should_we_balance
  - kernel/sched/fair.c:update_sg_lb_stats
  - kernel/sched/fair.c:sched_use_asym_prio
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_compare
  - kernel/sched/fair.c:task_numa_assign
  - kernel/sched/fair.c:update_numa_stats
  - kernel/sched/fair.c:update_numa_stats
  - kernel/rcu/tree.c:print_cpu_stall_info
```
**Symbols:**

```
ffffffff81157a90-ffffffff81157b0d: idle_cpu (STB_GLOBAL)
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
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c488)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffff80001013c3f8-ffff80001013c46c: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c1a4)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
c038c130-c038c190: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018aa90)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
c00000000018aa10-c00000000018aa80: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000eb810)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffe0000eb798-ffffffe0000eb7fa: idle_cpu (STB_GLOBAL)
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
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6b25)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810d6ad0-ffffffff810d6b20: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c5415)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810c53c0-ffffffff810c5410: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3765)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810d3710-ffffffff810d3760: idle_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int idle_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de6e5)
Location: kernel/sched/core.c:4623
Inline: True
Inline callers:
  - kernel/sched/core.c:available_idle_cpu
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:scheduler_ipi
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_heartbeat
  - kernel/softirq.c:irq_exit
  - kernel/sched/fair.c:_nohz_idle_balance
  - kernel/sched/fair.c:kick_ilb
  - kernel/sched/fair.c:rebalance_domains
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:update_sd_lb_stats
```
**Symbols:**

```
ffffffff810de690-ffffffff810de6e0: idle_cpu (STB_GLOBAL)
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
