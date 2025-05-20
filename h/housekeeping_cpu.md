# Function: <code>housekeeping_cpu</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b64ec)
Location: include/linux/sched/isolation.h:42
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810c917b)
Location: include/linux/sched/isolation.h:42
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/core.c (ffffffff810be515)
Location: include/linux/sched/isolation.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810d136f)
Location: include/linux/sched/isolation.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:pick_next_task_fair
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
In kernel/sched/core.c (ffffffff810c77a5)
Location: include/linux/sched/isolation.h:43
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810dac8f)
Location: include/linux/sched/isolation.h:43
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:pick_next_task_fair
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048177)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff8109dae4)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810ce053)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810e205f)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:pick_next_task_fair
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048a27)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff810a4030)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810d7c53)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810ec286)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104cb0b)
Location: include/linux/sched/isolation.h:50
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff810ab29e)
Location: include/linux/sched/isolation.h:50
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810e1e8d)
Location: include/linux/sched/isolation.h:50
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810f5bd5)
Location: include/linux/sched/isolation.h:50
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104bf9f)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff810a6b2a)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810df24d)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810f3d25)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:nohz_newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8104dadf)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff810a7bc6)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810e0edd)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810f59c9)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff8105525c)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff810b9626)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810f6e6e)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff8110f4d4)
Location: include/linux/sched/isolation.h:51
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (ffffffff810d006e)
Location: include/linux/sched/isolation.h:52
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff8111327e)
Location: include/linux/sched/isolation.h:52
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff8112b68f)
Location: include/linux/sched/isolation.h:52
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (ffffffff810ee69f)
Location: include/linux/sched/isolation.h:52
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff8113ef97)
Location: include/linux/sched/isolation.h:52
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff8115505f)
Location: include/linux/sched/isolation.h:52
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (ffffffff810fa67f)
Location: include/linux/sched/isolation.h:58
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff81151ee7)
Location: include/linux/sched/isolation.h:58
Inline: True
Inline callers:
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff8116520b)
Location: include/linux/sched/isolation.h:58
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (ffffffff81103a9f)
Location: include/linux/sched/isolation.h:59
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff811593ac)
Location: include/linux/sched/isolation.h:59
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff81171f5b)
Location: include/linux/sched/isolation.h:59
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (ffff8000100f9c20)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffff800010138344)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffff80001014c744)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (c0357e64)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (c038701c)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (c039a3e0)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/cpu.c (c000000000140c60)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (c000000000183e70)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (c00000000019f17c)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In kernel/sched/core.c (ffffffe0000e8378)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffe0000f5c60)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81048b97)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff8109d950)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810d2123)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810e63e6)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81037f27)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff8108c370)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810c682f)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810d5586)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff810489d7)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff8109d900)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810cfed3)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810e27b6)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
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
In arch/x86/kernel/cpu/aperfmperf.c (ffffffff81049de7)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
```
```
In kernel/cpu.c (ffffffff810a5790)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/cpu.c:freeze_secondary_cpus
```
```
In kernel/sched/core.c (ffffffff810d9823)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
```
```
In kernel/sched/fair.c (ffffffff810ee1fe)
Location: include/linux/sched/isolation.h:49
Inline: True
Inline callers:
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
</details>
</li>
</ul>

## Differences
