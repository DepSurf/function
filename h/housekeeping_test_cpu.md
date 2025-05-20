# Function: <code>housekeeping_test_cpu</code>

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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810dbfe0)
Location: kernel/sched/isolation.c:47
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff810dbfe0-ffffffff810dc00f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810e4620)
Location: kernel/sched/isolation.c:42
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810e4620-ffffffff810e464f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eeda0)
Location: kernel/sched/isolation.c:42
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810eeda0-ffffffff810eedcf: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f5bd0)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810f5bd0-ffffffff810f5bff: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81101940)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff81101940-ffffffff8110196f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110c1d0)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff8110c1d0-ffffffff8110c1ff: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff811093f0)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:nohz_newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff811093f0-ffffffff8110941f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110b290)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff8110b290-ffffffff8110b2bf: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81129af0)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff81129af0-ffffffff81129b1c: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:73
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff81e56940-ffffffff81e56958: housekeeping_test_cpu.cold (STB_LOCAL)
ffffffff8113c4f0-ffffffff8113c56f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/isolation.c:73
Inline: False
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff82057b60-ffffffff82057b78: housekeeping_test_cpu.cold (STB_LOCAL)
ffffffff81167110-ffffffff8116718e: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117940a)
Location: kernel/sched/isolation.c:73
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_shepherd
```
**Symbols:**

```
ffffffff820d6443-ffffffff820d645b: housekeeping_test_cpu.cold (STB_LOCAL)
ffffffff811793c0-ffffffff81179443: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81186f4a)
Location: kernel/sched/isolation.c:73
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:scheduler_tick
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
  - mm/vmstat.c:vmstat_shepherd
  - mm/vmstat.c:vmstat_shepherd
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:lookup_bh_lru
  - fs/buffer.c:bh_lru_install
  - fs/buffer.c:bh_lru_install
```
**Symbols:**

```
ffffffff821b1595-ffffffff821b15ad: housekeeping_test_cpu.cold (STB_LOCAL)
ffffffff81186f00-ffffffff81186f83: housekeeping_test_cpu (STB_GLOBAL)
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffff800010166528)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffff800010166528-ffff800010166594: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c03b2974)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
c03b2974-c03b29d8: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c0000000001bdc50)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
c0000000001bdc50-c0000000001bdcb4: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe0001087fc)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffe0001087fc-ffffffe000108864: housekeeping_test_cpu (STB_GLOBAL)
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
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810fac50)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff810fac50-ffffffff810fac7f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eae70)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:sched_cpu_dying
  - kernel/sched/core.c:sched_cpu_starting
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff810eae70-ffffffff810eae9f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f7e10)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff810f7e10-ffffffff810f7e3f: housekeeping_test_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool housekeeping_test_cpu(int cpu, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81102f50)
Location: kernel/sched/isolation.c:57
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_get_on_cpu
  - arch/x86/kernel/cpu/aperfmperf.c:arch_freq_prepare_all
  - arch/x86/kernel/cpu/aperfmperf.c:aperfmperf_get_khz
  - kernel/cpu.c:freeze_secondary_cpus
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/core.c:get_nohz_timer_target
  - kernel/sched/fair.c:newidle_balance
  - kernel/sched/fair.c:nohz_balance_enter_idle
```
**Symbols:**

```
ffffffff81102f50-ffffffff81102f7f: housekeeping_test_cpu (STB_GLOBAL)
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
