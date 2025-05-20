# Function: <code>sched_clock_idle_wakeup_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sched_clock_idle_wakeup_event(u64 delta_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b1510)
Location: kernel/sched/clock.c:351
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - kernel/time/tick-sched.c:tick_irq_enter
```
**Symbols:**

```
ffffffff810b1510-ffffffff810b152b: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sched_clock_idle_wakeup_event(u64 delta_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b3f90)
Location: kernel/sched/clock.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810b3f90-ffffffff810b3fab: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sched_clock_idle_wakeup_event(u64 delta_ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810ba5d0)
Location: kernel/sched/clock.c:357
Inline: False
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
```
**Symbols:**

```
ffffffff810ba5d0-ffffffff810ba5eb: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810b4df0)
Location: kernel/sched/clock.c:431
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810b4df0-ffffffff810b4e2a: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810bc0e0)
Location: kernel/sched/clock.c:431
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810bc0e0-ffffffff810bc11a: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c3770)
Location: kernel/sched/clock.c:419
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810c3770-ffffffff810c37aa: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810cca50)
Location: kernel/sched/clock.c:434
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810cca50-ffffffff810cca8a: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d4e40)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810d4e40-ffffffff810d4e79: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810df400)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810df400-ffffffff810df439: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e7700)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810e7700-ffffffff810e772b: sched_clock_idle_wakeup_event.part.0 (STB_LOCAL)
ffffffff810e7730-ffffffff810e774c: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e5340)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810e5340-ffffffff810e536b: sched_clock_idle_wakeup_event.part.0 (STB_LOCAL)
ffffffff810e5370-ffffffff810e538c: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e72f0)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810e72f0-ffffffff810e7334: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810fe910)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:time_cpufreq_notifier
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810fe910-ffffffff810fe951: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811453a0)
Location: kernel/sched/clock.c:433
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff811453a0-ffffffff811453d0: sched_clock_idle_wakeup_event.part.0 (STB_LOCAL)
ffffffff811453d0-ffffffff811453fb: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81172490)
Location: kernel/sched/clock.c:433
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff81172490-ffffffff811724c8: sched_clock_idle_wakeup_event.part.0 (STB_LOCAL)
ffffffff811724e0-ffffffff8117250b: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811834f0)
Location: kernel/sched/clock.c:458
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff811834f0-ffffffff81183528: sched_clock_idle_wakeup_event.part.0 (STB_LOCAL)
ffffffff81183540-ffffffff8118356b: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81191c30)
Location: kernel/sched/clock.c:458
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_nohz_stop_idle
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff81191c30-ffffffff81191c68: sched_clock_idle_wakeup_event.part.0 (STB_LOCAL)
ffffffff81191c80-ffffffff81191cab: sched_clock_idle_wakeup_event (STB_GLOBAL)
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
In kernel/time/tick-sched.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
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
In kernel/time/tick-sched.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
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
In kernel/time/tick-sched.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
```
```
In drivers/cpuidle/cpuidle.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
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
In kernel/time/tick-sched.c (0)
Location: include/linux/sched/clock.h:39
Inline: True
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
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d95f0)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810d95f0-ffffffff810d9629: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810c7fe0)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810c7fe0-ffffffff810c8003: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810d5930)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810d5930-ffffffff810d5969: sched_clock_idle_wakeup_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sched_clock_idle_wakeup_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/clock.c (ffffffff810e1220)
Location: kernel/sched/clock.c:435
Inline: True
Direct callers:
  - arch/x86/kernel/tsc.c:set_cyc2ns_scale
  - kernel/time/tick-sched.c:tick_irq_enter
  - kernel/time/tick-sched.c:tick_nohz_idle_exit
  - drivers/cpuidle/cpuidle.c:cpuidle_enter_state
```
**Symbols:**

```
ffffffff810e1220-ffffffff810e1259: sched_clock_idle_wakeup_event (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 delta_ns</code>
</li>
</ul>
</details>
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
