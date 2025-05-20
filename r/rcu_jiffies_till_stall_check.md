# Function: <code>rcu_jiffies_till_stall_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e35a0)
Location: kernel/rcu/update.c:456
Inline: False
Direct callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:synchronize_sched_expedited
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff810e35a0-ffffffff810e35e5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810e98c0)
Location: kernel/rcu/update.c:455
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810e98c0-ffffffff810e9905: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0770)
Location: kernel/rcu/update.c:458
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f0770-ffffffff810f07b5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810f0770)
Location: kernel/rcu/update.c:502
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810f0770-ffffffff810f07b5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff810fa3b0)
Location: kernel/rcu/update.c:506
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff810fa3b0-ffffffff810fa3f5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811028b0)
Location: kernel/rcu/update.c:458
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_implicit_dynticks_qs
```
**Symbols:**

```
ffffffff811028b0-ffffffff811028f5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8110da70)
Location: kernel/rcu/update.c:452
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8110da70-ffffffff8110dab5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81119b25)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff811199f0-ffffffff81119a35: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81125eb5)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81125d80-ffffffff81125dc5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81137805)
Location: kernel/rcu/tree_stall.h:26
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81133670-ffffffff811336b5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132e35)
Location: kernel/rcu/tree_stall.h:27
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff8112ed10-ffffffff8112ed55: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bd4c1b)
Location: kernel/rcu/tree_stall.h:27
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff8112f370-ffffffff8112f3b5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81caf2dd)
Location: kernel/rcu/tree_stall.h:29
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited_wait
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_stall_reset
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81150920-ffffffff81150965: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117bf46)
Location: kernel/rcu/tree_stall.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_stall_reset
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff81178020-ffffffff81178071: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b51c6)
Location: kernel/rcu/tree_stall.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_stall_reset
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811af890-ffffffff811af8e1: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c9c16)
Location: kernel/rcu/tree_stall.h:57
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_cpu_stall_reset
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811c1900-ffffffff811c1951: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d8fb3)
Location: kernel/rcu/tree_stall.h:58
Inline: True
Inline callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/rcu/tree.c:print_cpu_stall
  - kernel/rcu/tree.c:print_other_cpu_stall
  - kernel/rcu/tree.c:rcu_gp_might_be_stalled
  - kernel/rcu/tree.c:rcu_exp_jiffies_till_stall_check
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_gp_fqs_loop
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
ffffffff811d1e00-ffffffff811d1e51: rcu_jiffies_till_stall_check (STB_GLOBAL)
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
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018d1ac)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffff80001018bd38-ffff80001018bd9c: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03da678)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_init
```
**Symbols:**

```
c03d9ef8-c03d9f50: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6bbc)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
c0000000001e6560-c0000000001e65cc: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120658)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffe0001204be-ffffffe00012051e: rcu_jiffies_till_stall_check (STB_GLOBAL)
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
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e495)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111e360-ffffffff8111e3a5: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f6c5)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8110f3c0-ffffffff8110f405: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c385)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff8111c250-ffffffff8111c295: rcu_jiffies_till_stall_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rcu_jiffies_till_stall_check();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81127c35)
Location: kernel/rcu/tree_stall.h:24
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:synchronize_sched_expedited_wait
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff81127960-ffffffff811279a5: rcu_jiffies_till_stall_check (STB_GLOBAL)
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
